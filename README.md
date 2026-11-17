# Cheap shared web hosting: what RackNerd's $5.59 plan actually includes, which of the three tiers you need, and how renewal pricing works (full plan table and terms)

RackNerd's shared hosting starts at **$5.59/month** for 30 GB of SSD storage, 2 TB of monthly transfer, cPanel, LiteSpeed and daily offsite backups. Three plans exist, and the other two cost $9.59 and $15.59/month.

That first price buys a small site: a blog, a brochure site, a portfolio, a handful of low-traffic WordPress installs. It does not buy a managed WordPress experience, phone support, or a written uptime credit policy, and none of those are included at any tier here.

What follows is the full plan lineup with billing cycles, the three-year cost math against the hosts that advertise $2.99 headlines, the specs that actually constrain a small site, and the terms you want in writing before you prepay a year.

> **Quick pick:** one small or medium site, no desire to manage a server — the **30 GB plan at $5.59/month**. Already hosting several sites or storing large media — the **100 GB plan at $9.59/month**, which adds 70 GB and 1 TB of transfer for $4 more.
>
> 👉 [See RackNerd's three shared hosting plans and current prices](https://bit.ly/RacKnerd)

## RackNerd shared hosting plans compared

| Plan | Storage and monthly transfer | Domains and databases | Price | Order |
| --- | --- | --- | --- | --- |
| Shared 30 GB | 30 GB SSD · 2 TB | Unlimited domains and databases | **$5.59/month**, billed monthly | [Start with the 30 GB plan](https://bit.ly/RacKnerd) |
| Shared 100 GB | 100 GB SSD · 3 TB | Unlimited domains and databases | **$9.59/month**, billed monthly | [Choose the 100 GB plan](https://bit.ly/RacKnerd) |
| Shared 200 GB | 200 GB SSD · 5 TB | Unlimited domains and databases | **$15.59/month**, billed monthly | [Choose the 200 GB plan](https://bit.ly/RacKnerd) |

Every tier runs in US, European and Asian datacenters, and the plan you pick does not restrict which of the three you use.

Here is what all three plans include, since the differences above are the only ones that separate them:

- cPanel control panel
- LiteSpeed web server with CloudLinux
- Free SSL certificates via Let's Encrypt
- JetBackup daily backups, stored offsite
- DDoS protection
- Softaculous one-click installer
- Free cPanel-to-cPanel website migrations
- 24/7 ticket support, with RackNerd's ordering guide quoting a 10-minute average response
- Automatic activation, typically 5–15 minutes after checkout

The backup line is the one worth pausing on. Daily offsite backups are an add-on or a higher-tier feature at most hosts in this price bracket, and they are standard here on the cheapest plan.

## What three years actually costs, at RackNerd and at the $2.99 competitors

RackNerd bills these plans monthly, so there is no intro price that jumps at renewal: $5.59/month is the recurring rate, and three years of the 30 GB plan comes to **$201.24**. The 100 GB plan runs $345.24 over three years, the 200 GB plan $561.24.

Now compare that with the hosts whose ads you have probably already seen, using their verified intro and renewal rates:

| Host and plan | Intro price | Renewal price | Jump | Three-year total |
| --- | --- | --- | --- | --- |
| RackNerd 30 GB | $5.59/mo | $5.59/mo | none | $201.24 |
| SiteGround StartUp | $2.99/mo (12 months) | $17.99/mo | 6.0× | $467.64 |
| DreamHost Launch | $2.89/mo (first year) | $10.99/mo | 3.8× | $298.44 |
| Hostinger Premium | $2.99/mo (48 months upfront) | $10.99/mo | 4.1× | $143.52 for the first four years, then $131.88/year |

The pattern is consistent across that list. A low first-year number is a customer acquisition cost, and the renewal rate is where the host makes it back. SiteGround's StartUp is the extreme case: $35.88 for year one, then $215.88 each year after.

RackNerd's structure is different in a way that matters more than the headline. There is no documented renewal hike because there is no discounted first term to hike from, at least on monthly billing. What RackNerd does instead is rotate prepaid annual promos: the 30 GB tier has been listed at **$10.49/year** on an annual prepay, which is dramatically cheaper than twelve months at the monthly rate. Promo pricing rotates around sales periods, the specs printed on a promo card can differ from the standard plan card (storage type, how many domains you may host), and renewal terms on promo purchases are not spelled out in the ordering documentation.

So the honest version: monthly billing is predictable and cheap relative to the field; annual promos are far cheaper still, and a reviewer on Trustpilot reports a Black Friday rate that held at renewal as promised, but that is one customer's experience rather than a published policy. If you buy a promo, open a ticket and ask what the renewal invoice will say.

👉 [Check the 30 GB plan at $5.59/month, or the current annual promo rate](https://bit.ly/RacKnerd)

## Which tier you need, and what the upgrade buys

Storage and transfer are the only variables. The jump from 30 GB to 100 GB costs $4/month ($144 over three years) and adds 70 GB of disk plus 1 TB of transfer. The jump from 100 GB to 200 GB costs $6/month ($216 over three years) for another 100 GB and 2 TB.

For a single WordPress site with a few hundred images, 30 GB is roughly ten times what you will use. Two TB of transfer is far beyond what a small site moves in a month, and bandwidth overage is not the thing that will take your site down first.

The realistic case for 100 GB is a small store with a product image library, a photographer or designer hosting portfolios and client previews, or an account running five or six sites for other people. The 200 GB tier exists for content-heavy properties: video thumbnails, large PDF archives, dozens of domains under one cPanel login.

If you are launching one site and traffic is a guess, buy the 30 GB plan. Upgrading later is a plan change, not a migration, and paying $4/month for three years to hold storage you will never fill is the most common way people overspend on shared hosting.

## The limits that decide whether this plan fits

Disk and transfer limits are the ones printed on the sales page. Three others are buried deeper and matter more.

**Concurrent load, not bandwidth.** Shared hosting puts your site on a server with other customers, and CloudLinux enforces per-account CPU and memory ceilings. A traffic spike on your own site, or heavy PHP from a badly built plugin, hits that ceiling before it hits your transfer allotment. LiteSpeed and CloudLinux handle this better than the old Apache setups, but a shared plan is still the wrong home for a WooCommerce store running daily campaigns.

**Domain caps on promo tiers.** RackNerd's ordering guide lists unlimited domains and databases on all three plans, while plan cards on the shared hosting pages have shown per-tier host limits on promotional offers. If hosting several sites on one account is the reason you are buying, read the plan card at checkout rather than the comparison table.

**Migration scope.** Free migration covers cPanel to cPanel. Coming from a custom panel, a site builder, or a host that will not hand over a cPanel backup, confirm with support before you assume the move is free.

Backups deserve a second mention because of how they are usually sold. JetBackup runs daily and stores copies offsite, so a deleted file or a broken plugin update is recoverable without you maintaining your own schedule. Restoring is a support request; ask how that is handled if you expect to need it often.

**On refunds:** neither the ordering walkthrough nor the plan pages state a money-back window. If trying a host for 30 days and walking away matters to you, get the refund terms in a ticket before you pay for a year. Bluehost, for contrast, publishes a 30-day window and deducts the domain fee if you cancel inside it, and its free domain has to be redeemed within 90 days of purchase.

👉 [Compare the three RackNerd tiers and their current terms](https://bit.ly/RacKnerd)

## Who should buy somewhere else

RackNerd's shared plans are ticket-support only. No phone line, no chat, no managed WordPress. If a human on the phone is worth money to you, HostGator sells 36-month terms under $4/month with 24/7 phone and chat, cPanel, a free domain for the first year and ten sites per account, renewing just under $10/month.

If you need 25 sites on one cheap account, DreamHost's Launch plan allows exactly that at $2.89 for the first year, renewing at $10.99, with unmetered monthly traffic. Some DreamHost tiers do not include email, so check before you move a domain's mailboxes.

If a credit-backed uptime guarantee is a procurement requirement, Bluehost commits to 99.99% on shared hosting and lets customers claim a single 5% monthly credit within 30 days when it falls short. RackNerd's shared plan listings do not publish an uptime percentage with a compensation mechanism attached.

If you want cloud infrastructure, NVMe on every tier including entry level, WAF and malware removal bundled, HostArmada builds its shared plans that way and includes daily backups and cPanel.

None of those hosts is cheaper over three years than RackNerd at $5.59/month flat. You are paying the difference for phone support, a larger site allowance, or a guarantee with teeth.

## Before you check out

1. Confirm the billing cycle and the renewal amount on the invoice, especially if you are buying an annual promo rather than monthly.
2. Pick your datacenter. US, EU and Asia are all available on every plan, and the closest region to your visitors is usually the right one.
3. Decide whether you need a dedicated IP. RackNerd's shared plans run on a shared address; if you need your own for email reputation or an SSL setup, ask support what it costs before ordering.
4. Check the domain field. You can transfer a domain in, point an existing one at RackNerd's nameservers later, or register a new one during checkout.
5. Ask about backups and restore procedure if your site changes daily.
6. If you are migrating, confirm in a ticket that your current host's export qualifies for the free cPanel-to-cPanel move.

## FAQ

**How much traffic can the 30 GB plan handle?**
The 2 TB monthly transfer allowance is not the binding constraint for most sites; the CloudLinux CPU and memory limits are. A cached static site on LiteSpeed will serve far more visitors than an uncached WordPress site with heavy plugins on the same plan. Judge by page weight and PHP load, not by a visit counter.

**Is $5.59 the price I will pay next year?**
On monthly billing, yes, that is the recurring rate. On a prepaid annual promo, ask support to confirm the renewal invoice in writing before you pay, because promo terms are not documented in the ordering guide.

**Can I host more than one website?**
The ordering guide says unlimited domains and databases on all three plans. Promotional plan cards have shown per-tier domain caps, so verify the card you are actually buying if multiple sites matter.

**Can I upgrade later?**
Yes. Moving from 30 GB to 100 GB is a plan change inside the same account, and cPanel storage, databases and email come with you. There is no rebuild.

**Is cheap shared hosting safe enough for a business site?**
Free Let's Encrypt SSL, CloudLinux account isolation, DDoS protection and daily offsite backups cover the infrastructure side. Plugin updates, admin passwords and removing abandoned plugins remain your job on any shared plan, at any price.

## How to decide in one pass

One low-traffic site, or you are launching and traffic is a guess: the 30 GB plan at $5.59/month, billed monthly so nothing surprises you at renewal. Several sites or a large media library: the 100 GB plan, and check the domain cap on the card. Content-heavy or running client sites: the 200 GB plan at $15.59/month is still cheaper per year than most competitors' renewal rates alone.

If a prepaid annual promo is live when you order, it is the cheapest route into the same hardware, with one condition attached: get the renewal price confirmed in a ticket first.

👉 [Order the RackNerd plan that matches your site size](https://bit.ly/RacKnerd)
