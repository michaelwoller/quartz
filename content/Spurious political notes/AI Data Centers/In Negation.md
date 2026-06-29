
# Three main claims against

## 1) Data centers make energy more expensive

Sen. Elizabeth Warren" if you live near one of these large data centers, your electricity bills over the last five years have gone up by as much as 267 percent" [[3]](https://www.wral.com/news/state/fact-check-data-center-electricity-bills-june-15/)
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


# Other anti-arguments

## Mafia Diplomacy

## Low frequency sound health effects

No evidence [link](https://www.nature.com/articles/s41598-021-82203-6). Woo woo bullshit
- yet [millions of views](https://www.youtube.com/watch?v=_bP80DEAbuo)
	- [debunking](https://blog.andymasley.com/p/contra-benn-jordan-data-center-and?open=false#%C2%A7second-video-datacenters-behaving-like-acoustic-weapons) 
		basically it was some youtuber doing a rather shit methodology design and making shit up

Bottom line, no actual peer-reviewed study on this exists
- surprise surprise, but there's a reason peer review exists

##  AI datacenters have a low job creation to capex ratio

True, but requiring all innovation to be a jobs project is one of the worst impulses of government.

## They are making chips more expensive

The goal and hope eventually is to have things taper down eventually I presume.


# Sources (collected from [post](https://www.reddit.com/r/neoliberal/comments/1ugp9ye/we_need_to_talk_about_ai_data_centers_a_look_at/))

1. [Ballotpedia — Monterey Park Measure NDC (June 2026)](https://ballotpedia.org/Monterey_Park,_California,_Measure_NDC,_Prohibit_Data_Centers_Measure_\(June_2026\))
    
2. [Kaplan et al. (2020) — Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361)
    
3. [McCullough, WRAL News — Fact-check: Did data centers cause US electricity bills to rise 267%?](https://www.wral.com/news/state/fact-check-data-center-electricity-bills-june-15/)
    
4. [NJ Office of the Governor — Governor Sherrill Executive Orders on Utility Costs](https://www.nj.gov/governor/news/2026/20260120a.shtml)
    
5. [Reed, Harvard Law Today — How data centers may lead to higher electricity bills](https://hls.harvard.edu/today/how-data-centers-may-lead-to-higher-electricity-bills/)
    
6. [Kay, Reaser & Taylor, Dallas Fed — Processing Power: The Effect of Data Centers on Wholesale Electricity Markets](https://www.dallasfed.org/research/papers/2026/wp2606)
    
7. [Watten, Bistline & Blanford — Have Data Centers Raised Your Electric Bill?](https://arxiv.org/abs/2606.19777)
    
8. [Knittel, Senga & Wang, iScience — Flexible Data Centers Reduce Power System Costs But Can Increase Emissions](https://doi.org/10.1016/j.isci.2026.110255)
    
9. [Hilt, SELC — xAI built an illegal power plant to power its data center](https://www.selc.org/news/xai-built-an-illegal-power-plant-to-power-its-data-center/)
    
10. [Bonfiglioli et al., CESifo — Data, Power and Emissions: The Environmental Cost of AI](https://www.cesifo.org/en/publications/2025/working-paper/data-power-and-emissions-environmental-cost-ai)
    
11. [Hankendi, Coskun & Sovacool, iScience — Why transparency matters for sustainable data centers](https://doi.org/10.1016/j.isci.2025.113705)
    
12. [Mytton, npj Clean Water — Data centre water consumption](https://doi.org/10.1038/s41545-021-00101-w)
    
13. [Food & Water Watch — Big Ag Is Draining the Colorado River Dry](https://www.foodandwaterwatch.org/2023/08/08/big-ag-is-draining-the-colorado-river-dry/)
    
14. [Herrera et al., Journal of Cleaner Production — Sustainable AI infrastructure: water footprint forecast](https://doi.org/10.1016/j.jclepro.2025.146528)
    
15. [Couture, Bryant Research — A Drop in the Bucket: AI vs. the Cattle Industry](https://bryantresearch.co.uk/insight-items/comparing-water-footprint-ai/)
    
16. [Han, Li, Wierman & Ren — Small Bottle, Big Pipe: Data Centers and Public Water Systems](https://arxiv.org/abs/2603.02705)
    
17. [Shah, PLOS Water — Four water insecurity concerns about datacenters](https://doi.org/10.1371/journal.pwat.0000500)
    
18. [Fleury, BBC News — 'I can't drink the water' - life next to a US data centre](https://www.bbc.com/news/articles/cy8gy7lv448o)
    
19. [Kim, UC Law Environmental Journal — Data Center Cooling Water Discharge](https://repository.uclawsf.edu/cgi/viewcontent.cgi?article=1664&context=hastings_environmental_law_journal)
    
20. [Grimm, Green Nylen & Kiparsky, UC Berkeley — Regulating Data Center Water Use in California](https://www.law.berkeley.edu/wp-content/uploads/archive/2026/02/Regulating-Data-Center-Water-Use-in-CA_Report_CLEE-2026.pdf)
    
21. [Jager & Yoon, Water Biology and Security — Data centers: threat to freshwater biodiversity](https://doi.org/10.1016/j.watbs.2026.100585)
    
22. [Milman, The Guardian — Advocates raise alarm over PFAS pollution from datacenters](https://www.theguardian.com/environment/2025/oct/04/pfas-pollution-data-centers-ai)
    
23. [Microsoft Research — Project Natick](https://natick.research.microsoft.com/)
    
24. [Ascone et al., Scientific Reports — Effects of airborne infrasound on human mental health](https://doi.org/10.1038/s41598-021-82203-6)
    
25. [Ruane & DiFelice, Food & Water Watch — The AI Data Center Boom Is Coming for Farmers](https://www.foodandwaterwatch.org/2026/06/24/ai-data-center-boom-farmland/)
