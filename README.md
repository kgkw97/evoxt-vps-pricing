# Buy Cheap VPS: What's the Cheapest Plan Actually Worth, Is 2 GB Enough, and Will Renewal Double the Bill? (Full Plan Table)

A cheap VPS starts at roughly $2.50 to $4 a month, and most people end up paying $6 to $12 once they pick a plan that can run something real. Evoxt's smallest machine, VM-0.5, is $2.99/month for 512 MB of RAM, 5 GB of storage and 250 GB of monthly transfer; the plan most buyers should actually take, VM-1, is $5.99/month for 2 GB of RAM. Whether the $2.99 tier is enough depends entirely on what you're putting on it, and that's the part the "top 10 budget hosts" lists tend to skip.

Below you'll find every plan Evoxt currently lists, the renewal-price trap that turns a $9.99 plan into a $29 one elsewhere, the add-ons that quietly add $10–$20 a month, and how to check a budget host in your first week before the refund window closes.

> **Quick pick:** if you're buying a cheap VPS to run a website, a small app or a database, start with **VM-1 at $5.99/month** (1 core, 2 GB RAM, 20 GB storage, 500 GB transfer). It's the cheapest Evoxt plan that handles WordPress with a handful of plugins or a Docker container with a real workload. For a Linux sandbox, a WireGuard endpoint or a static site, **VM-0.5 at $2.99** is genuinely enough. 👉 [Check the VM-1 plan and current Evoxt pricing](https://bit.ly/EvoXt)

## Every Evoxt plan, side by side

Evoxt sells one Standard line of KVM virtual machines with advertised CPU clocks up to 6.0 GHz, weekly offsite backups included at no extra cost, and billing terms from monthly up to three years. The prices below are the monthly rates shown on its pricing page; paying for longer terms is handled through account credit rather than a separate discounted column.

| Plan | vCPU / RAM | Storage | Monthly transfer | Price (USD/mo) | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 core / 512 MB | 5 GB | 250 GB | $2.99 | [Deploy VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core / 1 GB | 10 GB | 250 GB | $4.99 | [Deploy VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 core / 2 GB | 20 GB | 500 GB | $5.99 | [Deploy VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores / 2 GB | 20 GB | 500 GB | $6.95 | [Deploy VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 cores / 4 GB | 30 GB | 1,000 GB | $11.99 | [Deploy VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 cores / 4 GB | 30 GB | 1,000 GB | $14.99 | [Deploy VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 cores / 8 GB | 60 GB | 2,000 GB | $23.99 | [Deploy VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 cores / 8 GB | 60 GB | 2,000 GB | $29.99 | [Deploy VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 cores / 16 GB | 80 GB | 3,000 GB | $47.99 | [Deploy VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 cores / 16 GB | 80 GB | 3,000 GB | $60.95 | [Deploy VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 cores / 32 GB | 100 GB | 5,000 GB | $95.99 | [Deploy VM-16](https://bit.ly/EvoXt) |

Two things in that table are worth pointing out because they don't match the usual budget-host ladder. The first is where the price jumps and where it doesn't: going from VM-1 to VM-1.5 costs $0.96 for a second core, and VM-2 to VM-3 costs $3 for two more. Extra cores are cheap on this line-up; extra RAM is what pushes you up the table. The second is the top end. VM-12 to VM-16 costs $35.04 more per month for double the RAM, 20 GB more storage and 2 TB more transfer, which is a much steeper step than anything below VM-8.

Evoxt also advertises Premium and Premium Plus lines alongside Standard, with higher per-terabyte transfer rates for add-on bandwidth. The table above covers the Standard plans; if you need a specific Premium configuration, compare it on the pricing page directly.

Prices are as published on Evoxt's pricing page and can change. Confirm the total in the cart before paying, especially if you're prepaying for a year or more.

## The renewal price is where cheap VPS bills go wrong

Evoxt lists one monthly price per plan and doesn't publish a separate renewal rate. That's the good pattern, but it's rare enough that you should check for it on any host before you buy.

The opposite pattern is common. Gizmodo's September 2026 VPS pricing table lists Hosting.com's 8 GB self-managed plan at $9.99/month on a three-year term, renewing at $29. That's 2.9× the advertised figure. DreamHost's four VPS tiers bill at $15, $30, $60 and $90 for the first month, then renew at $37.99, $69.99, $137.99 and $169.99. On the 4 GB tier, year one comes to $15 plus eleven payments of $37.99, or about $432.89, and year two runs $455.88.

AlphaVPS takes the opposite approach and says so on its own site: "the sticker price is the forever price," with the annual 15% discount locked for the life of the service. Its C2G plan is €2.99/month or €2.54/month billed annually at €30.50/year, and the same flat pricing applies at €11.99 monthly or €10.19 monthly for the 16 GB C16G.

To compare two hosts honestly, use this:

**(months at the promo rate × promo price) + (remaining months × renewal price) + (add-ons × months)**

Run that across 24 months instead of 12 and promotional pricing loses most of its advantage. The number that matters is the second-year bill, because that's the one you'll still be paying after the migration hassle is behind you.

## The line items that aren't in the headline price

A $2.99 VPS is the server. Everything around it may be billed separately, and the add-ons can easily exceed the plan itself:

1. **Control panel licence.** cPanel, Plesk and DirectAdmin are frequently extra on budget plans. If you don't want to administer a server from the command line, price the licence before you commit.
2. **Backups and snapshots.** Often sold as a per-GB add-on. Evoxt includes weekly offsite backups on every VM at no cost, which is unusual at this price.
3. **Extra IPv4 addresses.** Evoxt charges $3/month per additional IP; one IPv4 and a /64 IPv6 block come with the machine.
4. **Migration.** Some hosts charge to move your data in. Ask before you sign up if you're bringing sites with you.
5. **Security add-ons.** Malware scanning and advanced DDoS protection are paid extras at many providers.
6. **Bandwidth overage.** This is the one that produces surprise invoices. A third-party review of Evoxt reports that its model is allowance-then-throttle: exceed your monthly transfer and the port slows down rather than the meter running. Confirm that behaviour still applies to your plan before you rely on it.
7. **Managed support.** Unmanaged plans cover hardware and network only. If you want someone to patch your OS, that's a different product at a different price.

Evoxt also sells resources à la carte rather than forcing a plan change: the same third-party review lists extra vCPU at $3/month and extra RAM at $2/GB/month. Adding 4 GB of RAM to VM-1 that way costs $8/month, which is more than upgrading to VM-2 at $11.99 outright. Do the arithmetic before you scale sideways.

## Which plan fits which job

The RAM thresholds the hosting industry uses are consistent enough to plan against. One gigabyte covers testing and tiny sites, 2 GB covers a small WordPress install, and 4 GB or more is the starting point for WooCommerce or several sites on one box. In capacity terms, a 1–2 GB VPS handles roughly 5–10 lightweight sites, a 4–8 GB machine handles 20–50, and 8 GB+ with multiple cores can carry 50 or more with caching and load balancing in place.

Mapped onto Evoxt's line-up:

- **Learning Linux, running a VPN, hosting a static page or a staging box:** VM-0.5 at $2.99, or VM-0.75 at $4.99 if you want a full gigabyte.
- **One small WordPress site or a light app with a database:** VM-1 at $5.99. This is the crossover point where a budget VPS stops being a toy.
- **WooCommerce, a busy WordPress site, or two or three sites on one server:** VM-2 at $11.99 for 4 GB, or VM-3 at $14.99 if CPU is the bottleneck rather than memory.
- **Agencies and multi-site setups:** VM-4 at $23.99 is where 8 GB starts, and the 20–50 site range becomes realistic.

Worth knowing before you over-buy: a VPS generally only becomes the right answer over shared hosting once a site passes roughly 90,000 monthly visits, or when you need root, a specific PHP module, a development environment, or handling for sensitive data. If you're under that line with a brochure site, a cheap VPS is more server than you need, and more maintenance than you want.

## How to tell whether a cheap VPS host will hold up

Four checks catch most of the problems, and none of them require trusting the marketing page: provider reputation (consistent reviews, years in business, policies that are easy to find), infrastructure transparency (data centre locations, CPU model, storage type, virtualisation, bandwidth rules), payment and refund terms (money-back window, renewal price, accepted methods), and your own measurements during the first week of uptime, response time and disk performance.

On virtualisation, KVM gives each VM its own kernel with RAM and storage reserved, which is what stops one tenant's workload from bleeding into yours. Container-based virtualisation shares the host kernel and is where "noisy neighbour" complaints come from. Evoxt runs KVM, according to a third-party review of the service, and its control panel includes a firewall you configure without logging into the server, VNC access, VM cloning and rescue mode.

On reputation, Evoxt's Trustpilot page shows **3.1 out of 5 from 7 reviews**, three of them written in the twelve months before September 2026. The mix is uneven: one reviewer complains about withheld affiliate commissions, another says remaining account credit was non-refundable, a third describes slow support after a bandwidth-related suspension; three others report a smooth refund in 2025, more than a year of service without major issues, and good CPU and disk speed. Seven reviews is too small a sample to settle anything, and it's a fair reason to start on the cheapest monthly plan rather than prepaying three years.

One more structural point: a VPS lives on a single physical server, so a hardware failure takes it down until the host intervenes. Cloud hosting spreads across multiple machines and survives one of them failing. If your project can't tolerate that, budget for cloud rather than the cheapest VPS you can find.

👉 [Start on a monthly Evoxt plan and test it before prepaying](https://bit.ly/EvoXt)

## How Evoxt's entry pricing compares

The sub-$5 tier is crowded, and the headline number rarely tells you what you get. Entry-level configurations at the same price can differ by a factor of four in RAM.

| Provider | Entry price | What the entry tier includes | Policy worth noting |
| --- | --- | --- | --- |
| Evoxt | $2.99/mo | 1 core, 512 MB, 5 GB, 250 GB transfer | Weekly offsite backups included; monthly to 3-year terms |
| AlphaVPS | €2.54/mo annual (€2.99 monthly) | 2 GB, 2 vCPU, 30 GB NVMe, 3 TB transfer | Flat renewal; 14-day money-back; 7 locations |
| Netcup | €3.35/mo | 2 vCore, 2 GB, 64 GB SSD | Popular in Europe |
| Hetzner Cloud | €4.35/mo | NVMe storage, AMD EPYC | Germany, Finland, US regions |
| Vultr | $2.50/mo | Smallest SSD instance | Fine-grained resource tuning |
| IONOS | From $2/mo | 1 GB RAM at the bottom of a $2–$90 range | Unlimited traffic up to 1 Gbit/s; backups cost extra |
| Hostinger | $6.49/mo (1 vCPU / 4 GB) | 100 GB NVMe class storage on larger tiers | 30-day money-back; no managed VPS |
| Hostwinds | $4.99/mo | 1 GB RAM at entry | Three-day refund window |
| DigitalOcean | $4/mo | 512 MiB RAM at entry | No refunds |
| Hosting.com | $9.99/mo on a 3-year term | 4 cores, 8 GB, 160 GB NVMe | Renews at $29 |

Hostinger's pricing is reported two ways in recent coverage: $6.49/month for 1 vCPU and 4 GB from Gizmodo's September 2026 review, and $4.99–$19.99/month for the first 24 months from Liquid Web's October 2026 comparison. The difference comes from which tier and term each is quoting, so check the configuration attached to any figure you see.

If you want the absolute lowest monthly number and only need a Linux shell, Vultr at $2.50 or Evoxt at $2.99 are the realistic floor. If you want 2 GB of RAM for under $3, AlphaVPS's annual C2G is the outlier. Evoxt's advantage sits in the middle of the table: 2 GB for $5.99 with backups included, and cheap core upgrades above that.

## Questions people actually ask before buying

**What's the cheapest VPS you can buy right now?**
Around $2 to $3 a month. IONOS starts at $2, Vultr at $2.50, Evoxt at $2.99. At that price you're getting 512 MB to 1 GB of RAM and a small disk, which is a working server but not a website host.

**Is 2 GB of RAM enough for a VPS?**
For a single small WordPress site, a lightweight app or a database with modest traffic, yes. For WooCommerce, multiple sites, or anything running a control panel plus a stack of services, 4 GB is the safer floor.

**Will the price go up when I renew?**
It depends on the host. Evoxt publishes one monthly rate per plan with no separate renewal column, AlphaVPS states flat renewal explicitly, and Hosting.com and DreamHost both renew well above their introductory rates. Ask support in writing before you prepay.

**Can I get a refund if it doesn't work out?**
Evoxt's public pages don't state a money-back window, and its Trustpilot reviews include both a smooth 2025 refund and a complaint that account credit isn't refundable. Confirm the terms before paying, and start monthly. For comparison, AlphaVPS offers 14 days, Hostinger 30 days, Hostwinds three days, and DigitalOcean none at all.

**Do I need cPanel on a cheap VPS?**
Only if you want a graphical interface for sites, email and databases. The licence is usually billed separately and can cost more per month than the server. Server control panels like Evoxt's cover reboots, firewalls, VNC and snapshots but not website management.

**What's the difference between self-managed and managed?**
On a managed plan the host handles the operating system, security patches and troubleshooting. On a self-managed plan support covers hardware, network and the data centre only; everything above that is yours. Evoxt's feature set is self-service throughout, so budget your own time for updates.

**Can I run Windows on a cheap VPS?**
Evoxt offers Windows RDP images alongside Linux distributions. Windows licensing usually pushes the real cost above the Linux price, so check the plan before assuming the $2.99 figure applies.

## Picking a tier in one line

Learning Linux, running a VPN, or hosting a static page: take the smallest plan, $2.99 at Evoxt. One small WordPress site or a light app: 2 GB, $5.99. WooCommerce, multiple sites, or anything with a control panel on top: 4 GB or more, from $11.99.

Before you pay, confirm three things in the cart: the renewal price and not just the first-term price, the refund window and what it excludes, and the region your server will sit in relative to your visitors. Then test uptime and disk speed for a week while you can still walk away.

👉 [Compare Evoxt's plans and deploy a VM](https://bit.ly/EvoXt)
