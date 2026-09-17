# colocation data centers: how they work, what they really cost, and how to pick the right facility for your own hardware

There's a moment in almost every IT career when the server closet stops being funny. Maybe it was the summer the AC died and a switch cooked itself at 2 a.m. Maybe it was the electric bill after you added a second rack. Either way, you now own hardware you like (or at least hardware you've paid for), and you've realized it needs to live somewhere designed to keep it alive. That's the search that leads people to colocation data centers.

This article covers what colocation actually is, what it costs in the current market, how to evaluate a facility before you commit, and — since pricing transparency in this industry is rare — a full breakdown of one provider's published plans: Sharktech, which runs colocation facilities in Los Angeles, Las Vegas, Denver, Chicago, and Amsterdam and publishes its per-location pricing without forcing you through a "contact us for a quote" gauntlet first.

## What a colocation data center actually is

Colocation (usually shortened to "colo") means you rent physical space, power, cooling, and network connectivity inside a data center, but you keep your own servers. The facility handles the expensive parts — redundant power feeds, backup generators, precision cooling, physical security, carrier connectivity — and you handle the hardware and everything running on it.

It sits in a useful middle ground between the other two options:

- **Cloud hosting** means renting someone else's virtual infrastructure. Zero hardware ownership, but you pay per resource forever, and costs scale uncomfortably as you grow.
- **Dedicated server rentals** mean the provider owns the box and you rent it whole. No capital outlay, but the hardware isn't yours, and long-term you're paying a premium for that convenience.
- **Colocation** means you own the hardware and rent the environment around it. Higher upfront cost (you buy the server), but the monthly fee is just space and watts — typically much cheaper per unit of compute once your hardware is paid off.

The trade-off is control and responsibility. With colo, if the RAM fails, you ship the replacement or drive there. The facility keeps the power on and the packets flowing; the rest is yours.

## What's driving colocation pricing right now

If you priced colocation a few years ago and are checking again, prepare for some sticker drift. According to datacenterHawk's market research, global colocation rates have risen roughly 17% over the past five years, after nearly fifteen years of declines before that. North American vacancy rates sit below 2% in most tier-1 markets, which means the negotiating leverage has shifted firmly toward the operators.

A few things worth knowing before you compare quotes:

- **Power is the new bottleneck.** Grid capacity and utility timelines now matter more than the building itself. Sites in power-available secondary markets frequently price better and deploy faster than capacity-constrained primary markets.
- **Pricing is usually quoted per rack unit, per cabinet, or per kilowatt.** Industry retail pricing commonly runs around $75–$150 per U, or $900–$2,500+ per month for a full cabinet, depending heavily on market and facility quality.
- **Contract terms matter as much as the headline rate.** Retail deployments typically run 1–3 years; annual escalators of 2.5–5% are common in wholesale deals.
- **Setup fees exist** even when marketing pages don't mention them. Always check the order form, not the brochure.

Against that backdrop, providers that publish flat, location-specific pricing are genuinely easier to shop. Which brings us to the example at hand.

## How to evaluate a colocation facility before you sign anything

Whether you end up with Sharktech or anyone else, these are the questions worth answering first:

1. **Location and risk profile.** Is the facility in a seismically stable area? Is it close enough that you can physically get to your hardware when something needs hands-on work?
2. **Power redundancy.** Look for redundant feeds, UPS systems, and on-site generators. Ask what happens during an extended utility outage — and whether anyone has actually tested it.
3. **Connectivity.** Multi-homed, redundant network paths with multiple upstream carriers beat a single pipe every time. Check available port speeds and how transfer is metered.
4. **Physical security and access.** Badge/biometric access, surveillance, and 24/7 staff. A facility where you can't get someone on the phone at 3 a.m. is a facility you'll eventually resent.
5. **DDoS protection.** If you run anything publicly reachable — game servers, APIs, e-commerce — attack absorption capability on the network side is worth real money. Scrubbing after the fact is always slower than scrubbing inline.
6. **Total cost, including setup.** Monthly price plus setup fee plus overage terms. The cheapest sticker rate with a punitive power clause isn't the cheapest rate.

## Sharktech's colocation plans, location by location

Sharktech has been in the DDoS-protected hosting business since 2003, headquartered in Las Vegas, with colocation space inside enterprise-grade facilities from Equinix, CoreSite, H5 Data Centers, and Crown Castle across five cities: Los Angeles, Las Vegas, Denver, Chicago, and Amsterdam. The Los Angeles facility sits near One Wilshire — one of the busiest telecom hubs on the planet and the natural landing point for trans-Pacific traffic. The Denver presence operates out of H5 Data Centers' 300,000-square-foot campus.

They split colocation into two sizes: **1–6U** (one small box up to a few) and **full racks (10–42U)**. Here's every plan currently on their order form, prices as published:

| Plan | Space | Power | Network | Monthly Price | Setup Fee | Order |
| --- | --- | --- | --- | --- | --- | --- |
| Server Colocation – Los Angeles | 1–6U | 200–1200W | 1–40Gbps | $99.00 | $150.00 | [Order LA 1–6U](https://portal.sharktech.net/aff.php?aff=1611&pid=799) |
| Server Colocation – Las Vegas | 1–6U | 200–1200W | 1–40Gbps | $65.00 | $150.00 | [Order Las Vegas 1–6U](https://portal.sharktech.net/aff.php?aff=1611&pid=801) |
| Server Colocation – Denver | 1–6U | 200–1200W | 1–40Gbps | $65.00 | $150.00 | [Order Denver 1–6U](https://portal.sharktech.net/aff.php?aff=1611&pid=800) |
| Server Colocation – Chicago | 1–6U | 200–1200W | 1–40Gbps | $65.00 | $150.00 | [Order Chicago 1–6U](https://portal.sharktech.net/aff.php?aff=1611&pid=802) |
| Server Colocation – Amsterdam | 1–6U | 200–1200W | 1–40Gbps | $99.00 | $150.00 | [Order Amsterdam 1–6U](https://portal.sharktech.net/aff.php?aff=1611&pid=803) |
| Full Rack Colocation – Los Angeles | 10–42U | 1600–5500W | 1–100Gbps | $792.00 | $500.00 | [Order LA Full Rack](https://portal.sharktech.net/aff.php?aff=1611&pid=804) |
| Full Rack Colocation – Las Vegas | 10–42U | 1600–5500W | 1–100Gbps | $520.00 | $500.00 | [Order Las Vegas Full Rack](https://portal.sharktech.net/aff.php?aff=1611&pid=805) |
| Full Rack Colocation – Denver | 10–42U | 1600–5500W | 1–100Gbps | $520.00 | $500.00 | [Order Denver Full Rack](https://portal.sharktech.net/aff.php?aff=1611&pid=806) |
| Full Rack Colocation – Chicago | 10–42U | 1600–5500W | 1–100Gbps | $520.00 | $500.00 | [Order Chicago Full Rack](https://portal.sharktech.net/aff.php?aff=1611&pid=807) |
| Full Rack Colocation – Amsterdam | 10–42U | 1600–5500W | 1–100Gbps | $792.00 | $500.00 | [Order Amsterdam Full Rack](https://portal.sharktech.net/aff.php?aff=1611&pid=808) |

All prices are in USD, billed monthly, with quarterly, semi-annual, and annual billing cycles available in the order form. These are "starting from" figures — the configuration form lets you adjust rack space, power, bandwidth type, uplink speed, IP allocations, and DDoS protection level, so your final number depends on what you actually need.

Two things worth calling out. First, the **setup fees ($150 for 1–6U, $500 for a full rack)** appear on the order form, not the marketing page — factor them into your first invoice. Second, the pricing spread between locations is significant: the same 1–6U service that costs $99/month in Los Angeles or Amsterdam runs $65/month in Las Vegas, Denver, or Chicago. That's a 34% difference for identical space, power, and network specs. You can explore the configuration options and current availability yourself: 👉 [view Sharktech's colocation plans and order forms](https://bit.ly/SharKTech).

## What every plan includes, regardless of city

The baseline doesn't shrink because you picked the cheaper city:

- **Bandwidth:** The standard plan is metered at 300TB per month, with port speeds scaling from 1Gbps up to 40Gbps on the 1–6U tier and up to 100Gbps on full racks. Three hundred terabytes is an enormous amount of transfer for the small tier — most single-server workloads will never approach it.
- **DDoS protection:** Basic DDoS protection is included on the network, with an optional upgrade to 100Gbps protection in the order form. This is Sharktech's entire origin story — they've been selling attack-resistant hosting since 2003, and the testimonials on their colocation page lean heavily toward game-server operators describing multi-gigabit attacks absorbed without downtime.
- **IP allocations:** The order form includes initial IPv4 and IPv6 allocations, so you're not nickel-and-dimed for addresses on day one.
- **Hands on site:** 24/7 on-site technical support, not a ticket queue. For colocation specifically this matters more than people expect — when you need someone to check a cable or power-cycle a box while you're asleep or in another time zone, an on-site engineer is the difference between a five-minute fix and a bad morning.
- **Facility quality:** You're in Equinix, CoreSite, H5, or Crown Castle buildings — engineered facilities with redundant power, cooling, and security, not repurposed office space with a padlock.

## Which location makes sense for you

The five cities aren't interchangeable, and the price differences actually track geography usefully:

- **Chicago ($65/$520)** is the value pick for generic US workloads. Central location, solid connectivity, and the same network baseline as the pricier sites. If you're colocating a single firewall, NAS, or a couple of edge boxes and don't have a strong reason to be somewhere else, this is the rational default.
- **Denver ($65/$520)** is the geographic-diversity play. If your primary site is on the West Coast, a Denver footprint gives you a genuinely different seismic and grid profile without a three-timezone hop for maintenance visits.
- **Las Vegas ($65/$520)** serves the Southwest and is the natural choice if you want West-Coast-adjacent latency without West-Coast earthquake exposure.
- **Los Angeles ($99/$792)** is where you go for trans-Pacific traffic. Near One Wilshire, it's the classic landing point for US–Asia routes. If your users are in APAC or you need a West Coast interconnect, the premium buys real geography.
- **Amsterdam ($99/$792)** is the European foothold. Comparable AMS-region carrier-neutral facilities routinely charge well into three figures for a 1–6U slot, so $99/month here is genuinely competitive — and useful for EU latency, GDPR-residency reasoning, or simply not having all your infrastructure on one continent.

If you're unsure which facility fits, 👉 [Sharktech's team offers a free consultation](https://bit.ly/SharKTech) and will customize a solution if the listed plans don't match your requirements — they explicitly support custom configurations for anything from a single U to cages.

## Colocation vs. renting a dedicated server from the same provider

Worth a quick sanity check before you commit, because Sharktech sells both. The math is straightforward:

- If you already own suitable hardware, colocation wins on long-run cost. A $65/month slot in Chicago plus your own $2,000 server breaks even against a comparably specced dedicated-server rental (typically $100+/month at retail) inside a couple of years, and after that the server is an asset, not a line item.
- If you don't own hardware yet, don't buy it just to colocate. The upfront cost of server + setup fee + shipping needs about 18–24 months to pay off versus renting, and rented dedicated boxes come with hardware replacement as the provider's problem.
- The middle cases: hardware you've already depreciated, custom builds (specific GPUs, unusual network cards, licensed appliance software tied to a MAC address), or workloads where you legally need to own the machine.

Colocation is also the only option of the three where a provider like Sharktech's DDoS-protected network is attached to *your* hardware. If your box has custom tuning or licensed software you can't reinstall on rented gear, colo plus DDoS protection is a combination you can't replicate with a cloud instance.

## A few honest caveats

The prices above were pulled from Sharktech's live order system and reflect what's published today. Promotions rotate, and inventory at a given facility fluctuates — during research for this article, at least one older colocation SKU on their portal showed as out of stock, which is a good reminder to verify availability before you plan a migration weekend around it.

Also, "starting at" means exactly that. If you need 1200W on the 1–6U tier (a modern 2U box with a couple of beefy GPUs can get close), a 40Gbps uplink, or the 100Gbps DDoS protection upgrade, your monthly number will be higher than the headline. The order form prices all of this transparently, so configure before you budget.

Finally, colocation makes you responsible for your hardware's maintenance and spares. If your business can't tolerate a few days of hardware-shipping downtime when a component fails, either rent dedicated servers or keep a cold spare colocated next to the primary — which, at $65/month for extra U space in Chicago, is a cheaper insurance policy than most alternatives.

## Quick FAQ

**Is colocation cheaper than the cloud?** For steady, predictable workloads that run 24/7, usually yes — often dramatically so once your hardware is paid off. For bursty or short-lived workloads, cloud's pay-per-use model frequently wins.

**Do I need a full rack?** Most first-time colocators don't. A 1–6U slot handles a server or two; full racks (10–42U, 1600–5500W) are for people who already know they need that much space and power.

**What's the difference between colocation and hyperscale?** Colocation rents you space in a facility for your own servers. Hyperscale is cloud-style infrastructure with hundreds or thousands of the provider's servers operating as one system. Different products, different buyers.

**Who actually needs colocation?** Anyone with long-term infrastructure needs: businesses outgrowing the office server room, game-server operators absorbing regular attacks, companies needing geographic redundancy, and anyone with custom or licensed hardware that has to live somewhere with proper power and cooling.

## The bottom line

Colocation data centers let you convert the ruinous fixed costs of power, cooling, security, and connectivity into a predictable monthly line item — and in a market where rates have climbed 17% over five years and prime-market vacancy is under 2%, published flat pricing is worth seeking out. Sharktech's lineup is unusually easy to shop: five cities, two sizes, real numbers on the order form, DDoS protection included, and a 1–6U entry point as low as $65/month in Las Vegas, Denver, or Chicago ($99 in LA or Amsterdam), plus a one-time $150 setup fee. Full racks start at $520/month in the US mid-market cities and $792/month in LA or Amsterdam with a $500 setup fee.

If your 2 a.m. air-conditioning anxiety has finally pushed your servers out of the closet, 👉 [start here to compare Sharktech's colocation plans across all five data centers](https://bit.ly/SharKTech).
