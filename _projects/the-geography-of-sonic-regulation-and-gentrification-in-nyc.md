---
layout: project-page
title: "The Geography of Sonic Regulation and Gentrification in NYC"
linkname: the-geography-of-sonic-regulation-and-gentrification-in-nyc
author: "Arooj Fatima"
tagline: "Mapping gentrification pressure and complaint based sound regulation in NYC to show where neighborhood change and reporting intensity intersect."
location:
    - place: New York, USA.
project-link:
    - href: https://arooj98.github.io/Scrollytelling-Methods/#1
tags:
    - tag: gentrification
    - tag:  noise complaints
    - tag:  sonic politics
    - tag:  sonic justice
    - tag:  redevelopment
thumbnail-path: img/the-geography-of-sonic-regulation-and-gentrification-in-nyc/S6WIOd4.png
img-folder: ../../img/the-geography-of-sonic-regulation-and-gentrification-in-nyc/
timestamp: 12/15/2025 13:38:52
---
<h3> Introduction</h3>

New York City is being reshaped by gentrification through rising rents, shifting incomes, new development and changing housing tenure. These changes are not only economic and physical, they also transform everyday life including what kinds of street activity, nightlife and community sound are treated as normal versus treated as a problem. Complaint based systems like 311 are central in this context because they translate personal discomfort into data that can guide attention, enforcement and public narratives about neighborhood order. When gentrification accelerates, complaint patterns can become another way that public space and residential life are informally regulated with uneven impacts across different communities. This project is necessary because it connects measurable neighborhood change with the geography of sound related complaints to better understand where these pressures concentrate and why certain areas experience intensified regulation during periods of transition.

To examine this relationship I use a citywide spatial analysis that combines neighborhood change measures with population adjusted 311 complaint patterns. I first define and map gentrification across two time periods using a composite index built from income, rent, renter occupancy and new building permits. I then map sound related complaint density per 1,000 residents to identify where complaint activity concentrates beyond simple population effects. Next I compare gentrification and complaint intensity to locate areas where both pressures intersect and I focus on the most recent period to highlight current hotspots. I then add racial context using percent people of color to better understand who is most affected by these overlap zones. Finally I zoom in on Harlem as a high signal case and use land use patterns to interpret how neighborhood form and function can help explain complaint clustering.

<h3> Mapping Gentrification Signals Across NYC in Two Time Periods </h3>


To ground the project in measurable neighborhood change I use ACS based indicators and new building permit data to map gentrification patterns for two time periods 2014 to 2018 and 2019 to 2023. Figures 1 to 5 present five maps for each period including four normalized components and a composite Gentrification Index. Together these maps establish the citywide geography of gentrification that the later complaint analysis builds on.

**1. Median Household Income (Normalized)**

![]({{ page.img-folder }}y7gx0gK.jpeg)

These paired maps establish the income baseline that gentrification often builds on: where higher-income neighborhoods are concentrated and how that pattern shifts between 2014–2018 and 2019–2023. I normalized tract-level median household income to a 0–1 scale so that values closer to 1 represent higher-income tracts (and therefore stronger “affluence signals” within the broader gentrification pressure framework used in this project). This step useful because raw income values are not directly comparable across maps and periods, but a shared normalized scale makes later layering and index-building consistent and legible. Importantly, income alone does not equal gentrification, but it sets a critical socioeconomic context for interpreting where rising costs, new development and complaint-based regulatory attention may intensify.

Looking at the maps, the highest-income concentrations remain strongly anchored in Manhattan’s core and waterfront-adjacent areas, while the outer boroughs show more mixed, patchwork patterns. Between the two periods, several tracts outside Manhattan appear to deepen in higher-income values, suggesting outward diffusion of affluence signals beyond the traditional high-income core. This provides an essential reference layer for later steps, where I test whether rising-cost/development indicators and 311 complaint density align with these shifting income geographies.

Next, I map median gross rent (normalized) to capture the cost-pressure side of neighborhood change and to see where rising affordability stress overlaps with the income geography shown here.

**2. Median Gross Rent (Normalized)**

![]({{ page.img-folder }}haomezR.jpeg)

These paired maps capture the cost-pressure side of gentrification by showing where median gross rent is highest across NYC in 2014–2018 and 2019–2023. I normalized tract-level median gross rent to a 0–1 scale, where values closer to 1 represent higher rents. When rents rise, displacement pressure can intensify even if other neighborhood features have not fully shifted yet. Using the same normalized scale in both periods also makes the maps directly comparable. It also allows rent to be combined consistently into the composite Gentrification Index later.

Visually, the highest rent concentrations remain clustered in Manhattan and waterfront-adjacent neighborhoods. In the later period, high-rent tracts also appear more widely across parts of the outer boroughs. This supports the idea that affordability pressure is spreading outward instead of staying contained. This layer is especially important when read alongside income. Places with high rents but only moderate incomes can indicate sharper vulnerability and tension.

Next, I map percent renter-occupied housing (normalized) to identify where these rent pressures are likely to affect the largest share of residents through rental tenure.

**3. Percent Renter-Occupied Housing (Normalized)**

![]({{ page.img-folder }}wJaPfuM.jpeg)

These paired maps show where residents are most likely to feel gentrification through rental tenure, since renters are typically more exposed to rent hikes, lease turnover and displacement risk than homeowners. I normalized the percent of renter-occupied housing at the tract level to a 0–1 scale, where values closer to 1 represent a higher share of renter households. This layer matters because high-rent areas do not always translate into high displacement pressure unless a large share of people are actually renting. Including renter occupancy makes the gentrification signal more socially grounded.

The maps show a strong concentration of renter-heavy tracts across Manhattan and much of the inner core of Brooklyn and Queens, with additional clusters in parts of the Bronx. Many of these areas remain consistently high across both periods, which suggests that tenure vulnerability is a relatively stable baseline. That stability is useful analytically because it lets the next indicators do more explanatory work. In other words, when we later see rent increases or new development appearing inside high-renter areas, it becomes easier to interpret those as stronger gentrification pressure zones.

Next, I map new building permits (normalized), taken from NYC Open Data’s Department of Buildings (DOB) permit records, to capture the development and reinvestment signal that often accompanies and accelerates, neighborhood change.

**4. New Building Permits (Normalized)**

![]({{ page.img-folder }}pfJ04Cp.jpeg)

These paired maps capture development intensity, which is a key physical signal of gentrification because new construction often brings higher-end units, changing land values and neighborhood “repositioning.” I normalized the count/concentration of new building permits to a 0–1 scale, where values closer to 1 indicate a greater concentration of new permits in that tract. This step separates areas that are changing mainly through market pressure (like rent increases) from areas also experiencing visible reinvestment and redevelopment.

Across both periods, higher permit activity clusters in many of the same high-change corridors, especially in parts of Manhattan, northwest Brooklyn and several Queens tracts, with notable pockets in the Bronx as well. Compared side by side, the later period also suggests that redevelopment pressure is not limited to already-expensive cores, it extends into more mixed-income zones where other vulnerability factors (like high renter share) are present. This is important for the narrative because it helps explain why complaint patterns might intensify in places where the streetscape, nightlife and everyday public activity are being remade alongside housing.

Next, I combine the four normalized components (income, rent, renter occupancy and permits) into a single Gentrification Index (GI) map for each period to summarize gentrification pressure at the citywide scale before layering in 311 complaint patterns.

<h3> Gentrification Index (GI)</h3>

![]({{ page.img-folder }}odr8v3Q.jpeg)

The Gentrification Index (GI) combines the four prior indicators into one tract-level measure of gentrification pressure, so patterns across income, rent, renter share and development can be interpreted together. Each variable is scaled to a 0–1 range within each period so that no single variable dominates simply because it has larger raw units.

Formula (tract i, within each time period):

GIᵢ = (NormIncomeᵢ + NormRentᵢ + NormRenterShareᵢ + NormPermitsᵢ) / 4

Min–max normalization:

NormXᵢ = (Xᵢ − min(X)) / (max(X) − min(X))

Why this structure: a simple average is clear, replicable and keeps gentrification multi-signal rather than dependent on one proxy. It also supports later overlays and hotspot checks.

High GI concentrates in Manhattan where multiple pressures align, but the value of the index is that it also surfaces smaller, uneven clusters in the outer boroughs where pressures stack in localized ways (often corridor-based rather than continuous). From 2014–2018 to 2019–2023, the broad core pattern holds, while several outer-borough pockets intensify, supporting the idea that pressure is extending outward rather than staying confined to the traditional high-cost center.

One important note is that while the darkest tracts indicate the highest gentrification pressure, the mid-to-high range tracts are equally important because they often represent neighborhoods in transition where pressures are building and gentrification may be actively unfolding rather than already fully consolidated.

With the gentrification baseline established, the next step is to place 311 noise complaint locations on top of the Gentrification Index to see where sound-related reporting is most active relative to neighborhood change.

![]({{ page.img-folder }}BDTF1Xw.jpeg)

This overlay shifts the analysis from “where gentrification pressure is” to “where sonic regulation is being activated through reporting.” The purple GI surface provides the structural context, while the red points show the everyday geography of complaint events. The value here is not to claim causation, but to visually test alignment and mismatch: some high-GI corridors also carry dense reporting, but complaint activity is not confined to the darkest tracts and often appears along commercial strips, nightlife areas and dense residential blocks across different GI levels. Because point maps can overstate intensity in places with more people and activity, the next step converts complaints into population-adjusted complaint density (per 1,000 residents) to identify where reporting is concentrated beyond simple population effects.

![]({{ page.img-folder }}ettyYqh.jpeg)

This figure maps noise complaint density per 1,000 residents for 2014–2018 and 2019–2023, translating complaint activity into a comparable rate so the pattern reflects where reporting intensity is disproportionately concentrated, not simply where more people live. Read as a geography of sonic regulation, the map shows that high-density reporting forms a clear Manhattan spine, with especially strong concentrations in central and lower Manhattan, but it also surfaces distinct secondary clusters that would be easy to miss in a raw point map. In the later period, several pockets become sharper and more localized, suggesting that complaint intensity concentrates around specific urban conditions rather than spreading evenly across the city. One of these high-signal zones is Upper Manhattan, including Harlem, which stands out alongside other hotspots in parts of Brooklyn and Queens, indicating that complaint intensity is not confined to the most affluent core alone. The spatial structure of the hotspots often appears corridor-like, aligning with mixed land uses, active commercial streets, nightlife-adjacent blocks and neighborhood edges where residential expectations, street activity and public space collide. Importantly, the density map provides the project’s key regulatory baseline: it identifies where sound becomes most reportable and governable at the neighborhood scale, setting up the next step of testing how these complaint hotspots overlap with tracts showing high or emerging gentrification pressure.

![]({{ page.img-folder }}qQYWL81.png)

Building on the complaint-density maps (which compare rates by tract and time period), this 10-year hexbin view is included to show persistence rather than period-by-period fluctuation. By aggregating all 311 noise complaints into a uniform hexagonal grid, it smooths out tract boundary effects and makes long-run clusters easier to read. The pattern reinforces that complaint activity is not evenly distributed across the city; it concentrates along major activity corridors, with especially sustained intensity across Harlem and parts of the Bronx, alongside other high-activity zones in core Manhattan and adjacent waterfront neighborhoods.

To move from “where pressures concentrate” to “who is most likely to bear the costs of regulation,” the next step adds a demographic lens to the gentrification surface.

![]({{ page.img-folder }}CidcuBS.png)

This map layers the 2019–2023 Gentrification Index (GI) with proportional symbols representing the share of residents identifying as people of color. The goal is not to treat race as an “explanatory variable” on its own, but to make visible a core equity question embedded in complaint-based governance: when gentrification pressure and heightened reporting overlap, which communities are positioned closest to enforcement attention and quality-of-life policing. Visually, the highest GI values remain concentrated in Manhattan, but the largest demographic circles cluster strongly in the Bronx, Upper Manhattan and several outer-borough tracts. This creates a critical spatial tension for the project’s narrative: the city’s strongest gentrification pressures often sit adjacent to or extend into, areas with higher shares of residents of color, where the social meaning of “noise,” “order,” and “neighborhood norms” is more likely to be contested.

This overlay provides the rationale for zooming into Harlem as a high-signal case. Harlem is not only positioned near Manhattan’s high-pressure corridor, it also appears as a space where (1) gentrification pressure is present or intensifying, (2) residents of color remain a large share of the population and (3) complaint density and hotspot persistence are visible in the noise reporting maps. In other words, Harlem sits at the intersection of neighborhood transition and heightened sonic regulation, making it a strong site to interpret mechanisms rather than only describe citywide patterns.

![]({{ page.img-folder }}UPqhPHK.png)

This Harlem-focused hexbin map narrows the lens from “citywide clustering” to the neighborhood-scale structure of persistent reporting. The hexagonal grid is useful here because it highlights stable concentrations without being overly shaped by tract boundaries. Within Harlem, the hotspots are not evenly distributed. They form corridor-like streaks and localized pockets that suggest recurring friction points where residential life, commercial activity, transit access and public space meet. The pattern also helps clarify why Harlem shows up in the citywide density analysis: it is not a diffuse, low-level presence, but a place where reporting concentrates repeatedly across the decade. That persistence is analytically important for the project’s main claim, since it strengthens the interpretation of complaints as a form of ongoing neighborhood governance rather than a one-off spike tied to a single year.

![]({{ page.img-folder }}vB3BVNK.png)

This map clarifies the internal structure of “transition” inside Harlem by combining percent people of color with tract-level income variation. Large portions of Harlem remain in the highest bands of residents of color, but income is not uniform across the neighborhood. Higher-income tracts appear in distinct clusters rather than as a continuous block, which supports an interpretation of gentrification as uneven and patchy. That unevenness matters for sonic regulation. When higher-income tracts emerge within or alongside long-standing communities of color, the social threshold for what counts as “acceptable” street life, public gathering, music and nighttime activity can tighten. Complaint-based systems like 311 can then function as a translation device, turning subjective discomfort into official records that concentrate attention in specific micro-areas. This map sets up the next layer by showing that Harlem’s complaint hotspots should be read against a landscape of demographic continuity combined with localized affluence signals, not as a generic “high-activity neighborhood.”

![]({{ page.img-folder }}eFwe5hG.jpeg)

The land use map adds a built-environment explanation for why complaints cluster where they do. Harlem’s complaint points align strongly with the street grid, but they concentrate most visibly along mixed residential-commercial corridors and around nodes of mobility and activity, including subway access points and major neighborhood connectors. The inclusion of cultural organizations (DCLA) helps interpret complaint density as more than “noise.” Cultural sites, community institutions and nearby public spaces often anchor gatherings, performance and street presence. In a gentrifying context, those same spaces can become flashpoints where competing expectations of public life collide. Reading the map this way supports the project’s argument about sonic regulation: complaint clustering is not random and it is not only a function of population. It follows neighborhood form and function, especially where activity is legible, repeated and more likely to be interpreted as disorder. This Harlem layer provides a grounded mechanism for the citywide pattern: places experiencing change often generate more points of contact between older soundscapes and newer residential expectations and complaint systems can become the channel through which those conflicts get formalized.

**Closing synthesis**

Taken together, the maps suggest that noise complaints are not just “where sound is,” but where sound becomes most reportable under changing neighborhood expectations. Overlaying gentrification pressure with complaint density and long-run hotspots points to transition corridors and activity nodes as key sites of conflict, not only the highest-cost core. Harlem emerges as a strong case because it concentrates these dynamics in a legible way, letting the project move from citywide pattern to plausible neighborhood mechanisms.

**Limitations**

This analysis uses 311 noise complaints as a proxy for sonic regulation, but 311 captures perception, willingness to report and access to civic systems as much as it captures sound. Complaint locations can also be noisy as data, since incidents may be mislocated, duplicated or inconsistently categorized and the same underlying conflict can generate multiple tickets. The gentrification index is an intentionally simplified composite. It depends on choices like min–max scaling within each period, equal weighting across components and tract boundaries that can hide within-tract change. ACS estimates also carry sampling error and DOB permits represent filings rather than completed or occupied development. Finally, spatial overlap supports interpretation but does not establish causality.

**Next steps**

In order to expand the scope of this project, I imagine several future steps and directions that could be taken. One direction is to conduct a comparative case study between neighborhoods that share similar gentrification index values but show very different noise complaint densities, to better understand how land use mix, nightlife intensity and local reporting norms shape where sound becomes “reportable.” A second comparative case study could focus on areas with similar complaint intensity but different racial and tenure profiles, which would help clarify whether the same levels of complaint activity carry different equity implications depending on who lives in the surrounding tracts.

To strengthen interpretation over time, I would also like to extend the analysis by calculating noise complaints as a share of all 311 complaints and tracking how that share shifts across the two periods, rather than relying only on per-capita density. Finally, to improve spatial precision, I would map complaint clustering at a finer scale along key corridors by using block faces or street segments and pair the highest Harlem hotspots with brief field observation to document what specific street-level conditions (commercial frontage, parks, transit nodes, late-night uses) correspond with repeated reporting.

**Data used**

•        American Community Survey (ACS), census tract level: median household income

•        American Community Survey (ACS), census tract level: median gross rent

•        American Community Survey (ACS), census tract level: percent renter-occupied housing

•        American Community Survey (ACS), census tract level: percent people of color

•        American Community Survey (ACS), census tract level: total population (for per-1,000 rates)

•        NYC Open Data: 311 Service Requests (all categories, filtered to noise-related complaints)

•        NYC Open Data: Department of Buildings (DOB) permit records

•        NYC Open Data: DCLA Cultural Organizations / Cultural Institutions

•        MTA / NYC Open Data: Subway Stations

•        NYC Primary Land Use / PLUTO land use layer

•        NYC Open Data: Parks / Open Space layer

•        NYC census tract boundary layer 
