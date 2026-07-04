
# Three main claims against

## 1) Data centers make energy more expensive

Sen. Elizabeth Warren" if you live near one of these large data centers, your electricity bills over the last five years have gone up by as much as 267 percent" [3](https://www.wral.com/news/state/fact-check-data-center-electricity-bills-june-15/)
- Not true. Conflates the prices utilities pay to producers with the price a consumer pays to the utilities
	- The electricity supply chain has two prices
		- Producers (power plants) generate electricity and sell it at **wholesale price** to utility companies
		- Utility companies deliver it to you and charge you on your monthly bill
	- The issue is Warren conflates the "267 percent" increase as consumers to utilities, when it's utilities to producers
		- It's a pretty malicious lie, not to say that consumers' bills *aren't* rising

Energy prices for consumers is rising but it is very nonlinear and region dependent
- also heavily depends on how the electricity grid is structured

Electricity prices:
- Utilities are monopolies, so markets don't set the prices. Prices are set by state regulators
- Price rate for consumers = Total cost of supplying energy, divided by weights of consumers based on demand and difficulty of supply (how much and where in the grid the electricity is needed)
	- Rates are set in front of the state, but are based on the qualities above
		- Closed door meetings, not open to the public, who might have to front the costs

Data centers need dramatic amounts of electricity and will need more electrical infrastructure of the power grid (power lines, poles, etc.)
- will generally lead to increased prices of electricitiy in order to reduce demand of electricity elsewhere
	- aka, the grid will struggle to have all the power needed, but if the utilities increase prices, less people will use the grid, freeing up space for data centers

It's not clear what increased demand on electricity does to the price of electricitiy empirically [link](https://www.dallasfed.org/research/papers/2026/wp2606)
- When a new huge customer shows up, two competing things happen
	- 1) prices go down: more customers sharing the same fixed infrastructure = each person pays smaller slice of the fixed costs
		- assumes infrastructure is FIXED
	- 2) Prices go up: if data center requires new infrastructure, that cost gets passed to everyone
- Heavily moderated by how close the local grid is to it's full capacity. Once it's near the ceiling, costs spike nonlinearly. 
	- This means a data center that is fine in one region could be catastrophic in another that has a heavily used grid

AI data centers don't have a demand that looks like other residential or commercial loads since it isn't uniform in how it is being used and is being trained.
- this makes it tricky to track

Grids are built to handle peak demand. Demand fluctuates per season and time of day (e.g., summer days have a lot of demand, the night will not have as much demand). 
- Electricity that is produced during low demand that is not effectively stored gets wasted
- This means you can design AI data center electricity usage during low demand hours. Since AI is flexible in when it can be trained and used.
	- So you could put more demand when this other electricity goes to waste

Other forms of uncertainty is whether or not the data center will produce their own electricity via things like natural gas, like in [utah](https://grist.org/accountability/data-center-natural-gas-utah-cox-box-elder-stratos/) or [mississippi](https://www.selc.org/news/xai-built-an-illegal-power-plant-to-power-its-data-center/)
- some want to invest in more rewnewables or other clean energy like solar arrays or nuclear reactors
	- This depends on the government holding companies and investors accountable and whatever happens behind closed doors

The takeaway from the energy section should be that, with the right incentives and regulation, the effects on price increases and fossil fuel drawdown can be positive. But, I worry that the regulatory structure is pushing the distribution of the data centers in a very suboptimal direction, and I think the way the companies are interacting with utilities is downright predatory
## 2) Data centers increase emissions

Emissions increase due to the increase in energy production. 

Fossil fuel generators are used as substitutes for low power grid capacity
- Can violate the Clean Air Act (making them illegal, see the Mississippi link above)
- These cases are transient and not a good criticism long term (since produce better grid capacity or renewable power sources, this isn't an issue)

Evidence of data center and emission increases from empirical study are sparse and can't really be decorrelated properly given the region [link](https://www.ifo.de/en/cesifo/publications/2025/working-paper/data-power-and-emissions-environmental-cost-ai)

One thought: data center is a fixed, constant power draw
- could lead emissions rise as much as 20-58% [link](https://www.ifo.de/en/cesifo/publications/2025/working-paper/data-power-and-emissions-environmental-cost-ai)
	- Issue with this is that data centers don't have to be fixed in power consumption. they can operate flexibly (see above)

Other thought: it depends on location and grid capacity
- in places transitioning to renewables (liek Texas), flat and predictable damnd encourages more renewable investment because developers can count on steady customers.
- **In places still heavily reliant on coal or gas**, the sudden demand surge does the opposite, it makes fossil fuel plants more profitable and economically necessary again, slowing the transition away from them.

Not enough data. But the basic idea is that it could swing either way. More demand could increase or decrease fossil fuel usage, depending on what the location is investing into

## 3) Data centers increase water scarcity and pollution

- claim is data centers generate significant heat, which takes wate to cool and a LOT of water
	- Data centeres are not closed systems so they need water supplied
- Estimates are billion of liters of water a day (estimate for all centers) [link](https://www.nature.com/articles/s41545-021-00101-w)
	- Single gemini training cycle can take one million of liters
	- usage is small drop of bucket in many water consumptions
		- Alfalfa crops to feed cattle used 2.2 trillion **gallons** in 2022 in the clorado river basin [link](https://www.foodandwaterwatch.org/2023/08/08/big-ag-is-draining-the-colorado-river-dry/)
			- turns out, best thing to do if you care about water conservation is go vegan
	- pessimistic analysis sees data center usage in 2050 only estimates it raising seven fold to ~7mil liters a day [link](https://linkinghub.elsevier.com/retrieve/pii/S0959652625018785)
- Utility strain is not talked as much
	- peaking factor of AI is high, which causes transient strains on water infrastructiure and impacts the ability of communities to withstand prolonged periods of drought [link](https://arxiv.org/abs/2603.02705)
		- essentially, water usage issue seems more accute than systematic
		- improvements in infrastructure will result in $10b to $58b in costs, which will likely result in increased consumer costs depending on negotiations of local municipalities
	- Newton Country GA reproted price increases of water utility up to 50% following a Meta datacenter with local water authority warning of potential rationing as a result of projected usage increases [link](https://journals.plos.org/water/article?id=10.1371/journal.pwat.0000500)
- Contamination of local ground water is also a criticism
	- but these seem to be issues or concerns of the construction itself
		- there is no direct evidence that water discharge from data centers affects local water quality'
		- However, a lack of requirements to disclose water discharge quality and a lack of monitoring infrastructure could, hypothetically, create a situation where a public health crisis *could* emerge [link 1](https://repository.uclawsf.edu/cgi/viewcontent.cgi?article=1664&context=hastings_environmental_law_journal) [link 2](https://www.law.berkeley.edu/wp-content/uploads/archive/2026/02/Regulating-Data-Center-Water-Use-in-CA_Report_CLEE-2026.pdf)
			- however, this would be mostly be bureaucratic and oversight issues rather than systemic
- concerns of freshwater vioddiversity driven by construction of new hydroeletric plants to feed electrical demands [link](https://www.sciencedirect.com/science/article/pii/S2772735126000399?via%3Dihub), or induced demand for PFAS (per- and polyfluoroalkyl substance; "forever chemicals" to make things resistant to heat) [link](https://www.theguardian.com/environment/2025/oct/04/pfas-pollution-data-centers-ai)
	- not necessarily specific to data centers though
- There are new and creative approaches to cooling that have some people say the issues is "solved" (not space-based data centers) [link](https://natick.research.microsoft.com/)
	- don't know nearly enough to give an opinion here and its hard to give predictions
	-  but in a world where the companies can basically strongarm the utilities, the incentive to innovate in that regard is pretty low.
# Other anti-arguments

## Shady NDAs and Collusions

- Data center AI companies/investors often pick rural cities partially for the cheaper land, but also because it is easier to strong arm the city counil/county commission into NDA's about the development
	- if the town doesn't agree to the NDA for negotiations, the AI affiliated companies will just find a town that will
	- If the NDA is signed, citizens lose their ability to even understand what is happening in their town and can suffer consequences they did not consent to
		- City can't answer anything becasue of the NDA
- political collusion is also an issue
	- In Utah, a Utah house speaker owns thousand of acres of land in the area wanting to make a data center. Claims he "didn't know" about the plans [link](https://www.ksl.com/article/51498194/utah-house-speaker-owns-25k-acres-not-far-from-site-of-proposed-box-elder-county-data-center)
		- obvious BS
- granted, direct democracy engagement on these topics will make things NEVER occur 
	- the people will just veto everything all the time
	- reason why utility energy negotiations are behind close doors
	- The council are empowered to decide, not the people in municipalities
		- issue is they should be empowered to keep it a secret (sunset laws exist)
			aka, sunset clauses exist so that the politcians can be pressured later  (easier to not extend laws than to pass laws that undo previous laws)

## Low frequency sound health effects

- No evidence [link](https://www.nature.com/articles/s41598-021-82203-6). Woo woo bullshit
	- yet [millions of views](https://www.youtube.com/watch?v=_bP80DEAbuo)
		- [debunking](https://blog.andymasley.com/p/contra-benn-jordan-data-center-and?open=false#%C2%A7second-video-datacenters-behaving-like-acoustic-weapons) 
			basically it was some youtuber doing a rather shit methodology design and making shit up
	- surprise surprise, but there's a reason peer review exists
- There could be concern about the harm on other animals that do hear infrasound, like migratory birds though
	- Migratory birds are pretty fucked eitherway, unfortunately (I donate mucho money to conservation projects mind you)
-  Bottom line, no actual peer-reviewed study on this exists
	- this does not mean there is NO effect, there just has been no verified and scrutinized effect
		- folk scientist content doesn't count
- There is probably a better argument for *audible* sound, but I haven't looked into that
##  AI datacenters have a low job creation to capex ratio

- They don't create as many jobs as some make it out to be  
	- compared to how much revenue for private holders it generates
- True, but requiring all innovation to be a jobs project is one of the worst impulses of government.
- There's some concern of things being automated inside of the data centers, which means less jobs, but idk about this
## They are making chips more expensive

- The goal and hope eventually is to have things taper down eventually I presume.
- They aren't necessarily taking the RAM or GPUs that you would use directly
	- They suck up all the production, so less goods of RAM or GPUs that consumers would get are being produces, leading to more scarcity and higher costs
- Regardless, increased prices of computer components isn't a good reason to halt datacenters per se

## Structural Job Loss

- more about AI in general than about data centers
- obviously, if the US and US-based companies are the ones building these, we have more of direct control about this type of issue
- more of a compeltely seperate topic
	- bad vibes in general regardless
## They are taking land from farmers
- [taking land](https://www.foodandwaterwatch.org/2026/06/24/ai-data-center-boom-farmland/)
- not inherently bad. Better use of land