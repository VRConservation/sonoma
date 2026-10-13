---
title: Sonoma County Wood Recovery & Utilization Project
subject: Wood Utilization
subtitle: 
short_title: Sonoma Feedstock Pilot
date: 2026-10-12
authors:
  - name: Vance Russell
    affiliations: 
      - 3point.xyz
    email: vance@3point.xyz
keywords: Wood, Mill, Community
abstract: |
  Sonoma County contains about 513,000 acres of forest land, but under current practices only around 3,000 acres are treated each year, resulting in a treatment gap of nearly 100% (99.7%) when compared to the approximately 246,000 acres believed to be treatable. These treatable acres are spread out over some 14,000 private parcels—about 93% of which are less than 100 acres in size—such fragmentation means that individual permitting is too costly and is therefore the main reason for the initiative to centralize feedstock aggregation. When the land that is feasible to treat is matched with census tracts that have a poverty rate above 40%, this results in about 3,100 priority acres that are concentrated in the fire-prone northwest part of the county, which is in line with the project's Phase I aim of treating 3,000 to 4,000 acres per year and focuses risk reduction on the communities that have suffered the most from fire and at the same time have the least economic opportunity. The project suggests the establishment of a wood recovery and utilization campus at a former sawmill site within a 60-minute drive of the majority of existing timber harvesting areas and the county's most dense forest biomass, with the material being diverted into wood products, firewood, and biomass energy rather than being left as waste or burned in piles. The expected benefits are 36 direct full-time-equivalent jobs in Phase 1, increasing to 107 by 2030, together with 69 to 175 indirect jobs in the fields of forestry, prescribed fire, and support services—amounting to 85 to 191 total jobs when a wider sector-wide employment multiplier is taken into account.
kernelspec:
  name: python3
  display_name: Python 3
exports:
  - format: docx
    template: curvenote
    output: article-name.docx
    article_type: Report
  - format: typst
    template: lapreprint-typst
    output: article-name.pdf     
---

:::{figure} header.png
:alt: header shot
:::

# Background
This was originally a storymap report for Regenerative Forest Solutions and its feedstock aggregation effort, funded by the Governor's Office of Land Use and Climate Innovation. The storymap no longer exists, so this is a reproduction.

## Poverty
California's economy is the 5th largest in the world (if it were a country), and it is often not mentioned in the same sentence as poverty. However, pockets of the state have high levels of poverty ({numref}`ces`). These are located in urban areas, the state's northern and southern ends, and the southern San Joaquin Valley.

:::{figure} calenviro.png
:label: ces
California percent poverty rankings by census tract. Green (low), Yellow (medium), and Red (high) percentages (CalEnviroScreen 4.0).
:::

In Sonoma County, most economically disadvantaged residents live in the highly dense urban corridor of Santa Rosa and Windsor. They are dispersed throughout more rural parts of the county. Overall, Sonoma County has a 9% poverty rate and generally lower percentages of economically disadvantaged citizens than other parts of California ({numref}`ces-son`). Many rural areas have experienced a double whammy of high poverty and brain drain as people who cannot find work leave for urban areas. These areas often coincide with heavily forested regions.

:::{figure} sonoma-ces.png
:label: ces-son
:height: 400px
Poverty percentage in Sonoma County by census tract. Green (low), Yellow (medium), and Red (high). CalEnviroScreen 4.0.
:::

:::{important} Wildfire
:class: dropdown

Except for desert and agricultural lands, most of California has burned at some point during the past 150 years (map of fire perimeters from CAL FIRE). Fires have become increasingly intense over time, largely due to climate change. The map groups fires by decade (older fires are lighter, newer are darker). 

Recently, Sonoma County has experienced several high-severity wildfires. The 2017 Tubbs fire burned 36,807 acres, destroyed many homes, and caused nearly $9.6 billion in damage, mostly in Santa Rosa. The foothills east of Santa Rosa have burned repeatedly in the past few years.

Estimates from the Sonoma Wildfire Hazard Index and US Census show that 15,437 Sonoma County residents, or 3% of the population, live in areas of extreme wildfire risk [Sonoma CWPP, 2023](https://permitsonoma.org/sonomacountycwpp). Nearly 14,000 buildings in this landscape are at extreme wildfire risk, and if they burn, they could cause roughly $9 billion in losses (Ibid).
:::

## Fire Impact
Higher poverty and fire frequency are connected. @hino found a correlation between high poverty and wildfire frequency ({numref}`hino-map`).  @king found similar results with 6.7 million private forest treatable acres; four million acres are concentrated in High Poverty Census Tracts of California; that is, 60% of total private treatment needs are concentrated in areas where the poverty rate exceeds 20%—two times the national average. The same authors estimated 231,000 acres needing treatment, with 71% in high-poverty areas (poverty rate > 20%).

:::{figure} hino.png
:label: hino-map
:height: 600px
Fire experience by census tracts and corresponding median income by experience group.
:::

According to the feasibility study, treating 246,365 acres within Sonoma County is feasible. Below, we estimate how many people are needed to conduct forest treatments at this scale over time.

## Treatment
Sonoma County has 513,000 acres of forestland. Commercial harvest is largely focused in the county's northwest, in redwood-dominated stands, and is conducted by larger-scale forestland owners. A current estimate of acres treated/year is approximately 3,000 across private forestland ownerships. This number excludes public, utilities, prescribed fire, road right-of-way, California Office of Emergency Services, and county-based vegetation management. Therefore, we can assume this number represents, on average, acres treated/year in a business-as-usual scenario.

The North Coast Resource Partnership created a map of feasibly treated acres (green) based on slope, road access, riparian, and wilderness area protection ({numref}`fease-map`).

:::{figure} fease.png
:label: fease-map
:height: 600px
Treatment feasibility of the North Coast region shown in green (@tukman). 
:::

Zooming into Sonoma County shows the 'feasible to manage' areas identified in green ({numref}`sonoma-zoom`). This covers nearly 212,000 acres, with the project’s data showing slightly more feasible, treatable acres at just over 246,000. This acreage is scattered across small private forestry landholdings (approximately 93% on parcels <100 acres, or close to 14,000 parcels)—too large an area and too many landowners for feasible forest health treatments because permitting work on smaller landholdings is cost-prohibitive.

:::{figure} sonoma-fease.png
:label: sonoma-zoom
:height: 600px
Sonoma County treatment feasibility (@tukman). 
:::

If we cross-walk the feasible-to-treat acres with areas > 40% poverty, the total number of acres is approximately 3,100 acres ({numref}`sonoma-pov`). This area is spread across the county's northwestern portion. Still, some of it is close to urban areas such as Santa Rosa. It aligns with work in progress or being planned by the County of Sonoma Vegetation Management Program and Permit Sonoma's FEMA grant treatment acres. This number of acres aligns with the estimated goal of 2,500-4000/yr treatment acres in Phase I of the project. If prioritized, treatment areas in disadvantaged communities could greatly reduce fire risk for many population sectors.

:::{figure} pov.png
:label: sonoma-pov
:height: 600px
Sonoma County treatment feasibility joined with > 40% poverty. 
:::

The 3,100 prioritized treated acres may or may not overlap with currently treated acres, since the estimate is based on timber harvest plans, non-industrial timber management plans, and 1,038 exemptions. Broadening the acres treated to include prescribed fire, public, and other lands, the Climate Resiliency Comprehensive Action Plan, published by the County of Sonoma’s Climate Resiliency and Action Division, estimates that the County will need to treat a total of 80,000 acres per year across categories of vegetation management, and 10,400 acres specific to in-forest treatments.

Of course, these treatments would need to be cross-walked and coordinated to already planned or ongoing projects. For example, The Sonoma County Hazardous Fuels Reduction Program was funded through FEMA's Building Resilient Infrastructure and Communities (BRIC) grant program in December 2020 and was funded $37 million to fund the  Wildfire Resilient Sonoma County  project, also known as the BRIC project.

The BRIC project will complement and scale up the projects, capabilities, and systems Permit Sonoma staff are developing through the Sonoma County Wildfire Adapted program and the Hazardous Fuels Reduction Project to reduce the risk of devastating wildfires. The four project areas are Austin Creek/Dry Creek, NE Geyserville, Lower Russian River-Cazadero, and East Sonoma ({numref}`sonoma-haz`). We identified these project areas based on burn history, fuel loads, population density, road networks, and other factors. This is the first wildfire mitigation funding allocated in the country via FEMA.

:::{figure} haz.png
:label: sonoma-haz
:height: 600px
Sites for the Sonoma County Hazardous Fuels ReductionGrant Program.
:::

## Jobs
Direct jobs are those anticipated to be involved in the logistics, transportation and hauling, wood processing, manufacturing, and sales involved in managing the stream of woody material at a wood campus or aggregation yard. Indirect jobs include forestry professionals conducting forest treatments, Licensed Timber Operators and haulers, wood product businesses, and others.

Direct positions are estimated at 36 full-time equivalents (FTEs) during Phase 1 ({numref}`ftes`). The estimated indirect jobs related to removing forest materials created are 37 during the same period. However, the forestry sector's general multiplier is about 2.3 indirect jobs per direct job, meaning approximately 83 indirect jobs were created (@bivens). The positions are estimated for a start of 3,000 acres treated/year, building to 5,000 in Phase 2 and 10,400 in Phase 3.

:::{table} Additional direct FTE positions created by Phase for the Sonoma Feedstock Pilot.
:label: ftes

| TYPE | PHASE 1 | PHASE 2 | PHASE 3 |
| :---- | ---: | ---:| ---: |
| Staffing | 7 | 12 | 15 |
| Mill & Firewood | 15 | 26 | 31 |
| Biomass | 2 | 6 | 11 |
| Manufacturing & Retail | 10 | 23 | 39 |
| Education & Outreach | 2 | 9 | 11 |
| **Total** | **36** | **76** | **107** |
:::

### Direct
For Phase 1 staffing, we estimated 7 FTEs (director, site operator, part-time admin assistant) to manage and run the feedstock aggregation unit. This is based on one wood recovery and utilization campus closest to potential wood resources currently proposed as Berry's Sawmill. According to project data, the mill is within a 60-minute drive of most current timber harvest plans and the greatest concentration of forest biomass. The location was selected because of its historic use as a sawmill and its proximity to potential material, which would reduce transportation and hauling distances. By 2030, adding one to two additional sort yards would create 15 FTEs to staff the units.

### Indirect
The following makes assumptions for the number of indirect jobs supported through the pilot ({numref}`indirect-table`). For Phase 1, one could assume 2,000 acres/yr are treated in the feasible treatment areas identified by the North Coast Resource Partnership analysis. Although treatments may vary, we will assume mastication or a feller-buncher. A masticator will treat approximately 0.57 acres/hr (@halbrook). Dividing 2,000/0.57 gives 3,508.8 hours or approximately 1.7 FTEs (3,508.8/2080).

:::{table} Additional indirect FTE positions created by Phase for the Sonoma Feedstock Pilot.
:label: indirect-table

| TYPE | PHASE 1 | PHASE 2 | PHASE 3 |
| :---- | ---: | ---:| ---: |
| Forest Techs | 18 | 28 | 36 |
| Thinning | 18 | 35 | 52 |
| Prescribed Fire | 9 | 18 | 26 |
| Suppliers | 15 | 27 | 38 |
| Admin/support | 9 | 16 | 23 |
| **Total** | **69** | **124** | **175** |
:::

To get to 3,000 acres, hand crews thin an additional 1,000 acres of terrain unsuitable for machines. A capable crew member can thin approximately 0.25 acres/day. Therefore, a 10-person crew thins 2.5 acres/day. Dividing 1,000 by 2.5 gives 400 days, equivalent to 4,000 total days (400 x 10 crew members) or 32,000 hours. Dividing 32,000/2,080 gives approximately 15 FTEs. Rounding up the 1.7 FTEs for machine treatments and adding to the crews gives 17 FTEs. This number would double by Phase 2 and triple by Phase 3 to 12 total FTEs.

For prescribed fire crews, we assumed ~50% overlap in crew members, starting with 2 FTEs in the initial phase and ending with 6. 

Suppliers and admin support staff for indirect positions are estimates, but we used the following multipliers:

1. Suppliers: 1 supplier FTE for every 3 indirect FTEs (forest techs, thinning, and prescribed fire crews).
2. Admin/support staff: 1 support staff for every 5 indirect FTEs (forest techs, thinning, and prescribed fire crews).

The forest sector uses more generous multipliers at the national scale. For instance, @bivens used a multiplier of 2.3 indirect jobs for every direct job created. However, this figure includes all spending and jobs created, so it is much higher than our estimates and may reflect the project's impact on the entire Sonoma economy. Bivens' multiplier gives 83 FTEs during Phase 1 of the pilot and 191 FTEs by 2030 (Phase 3).

The analysis also included structural hardening in the indirect jobs created. In Sonoma County, 13,776 buildings are in areas classified as extreme in the wildfire risk index ([Sonoma CWPP, 2023](https://permitsonoma.org/sonomacountycwpp)). Assuming each building requires 100 sq. ft. of treatment for structural hardening, that's about 32 acres at 0.25 acres treated/day, or 128 days of work (0.5 FTE). Since nearly 14,000 home treatments is a lot, we doubled the number to include time to arrange and complete treatments. Total FTEs would likely remain constant across phases, possibly even decreasing. However, we assumed home hardening must be maintained over time and therefore added 1 to each phase of the indirect thinning FTEs.

To increase the acres of in-forest treatments, workforce development programs such as the partnership between  Resilience Works and North Bay Jobs with Justice, the Forestry and Fire Recruitment Program, Tribal EcoRestoration Alliance, local arborists, and other programs offered within the county and State (Humboldt State, UC Berkeley, UC Davis, and Chico State), will prove essential in attracting and training a workforce capable of meeting the increased forest treatment needs. 

## Take-Aways
The Sonoma County Wood Recovery & Utilization Project will benefit the county through direct wildfire mitigation, wood products, job creation, and new businesses created or supported. Key findings included the following: 

- The treatment gap between treatable and treated acres in Sonoma County is nearly 100% (99.7%).
- Cross-walking the feasible-to-treat acres with areas > 40% poverty mechanically gives an acreage of 3,100, in line with the initial treatment goal of 3,000 acres. Identified areas could help reduce wildfires and decrease risk in the most fire-prone and economically disadvantaged areas.
- The total number of jobs created for Phase 1 of the project is 36, which will increase to 107 by 2030 (Phase 3).
- The total number of indirect jobs created increases from 69 in Phase 1 to 175 in Phase 3. Calculating the total number of jobs created (dividing total spending by total jobs created) yields a range of  85 (Phase 1) to 191 (Phase 3).