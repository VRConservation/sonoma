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
  This was originally a storymap report to Regenerative Forest Solutions and their feedstock aggregation effort funded by the Governor's Office of Land Use and Climate Innovation. The storymap no longer exists and this is a reproduction of it.
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

> "A starting quote" 

# Background
This was originally a storymap report to Regenerative Forest Solutions and their feedstock aggregation effort funded by the Governor's Office of Land Use and Climate Innovation. The storymap no longer exists and this is a reproduction of it.


## Poverty
California's economy is the 5th largest in the world (if it was a country) and so often is not mentioned in the same sentence with poverty. However, pockets of the state have high levels of poverty ({numref}`ces`). These are located in urban areas, the northern and southern ends of the state and the southern San Joaquin Valley.

:::{figure} calenviro.png
:label: ces
California percent poverty rankings by census tract. Green (low), Yellow (medium), and Red (high) percentages (CalEnviroScreen 4.0).
:::

In Sonoma County, most economically disadvantaged citizens live in Santa Rosa or Windsor's highly dense urban corridor. They are dispersed throughout more rural parts of the county. Overall, Sonoma County has a 9% poverty rate and generally lower percentages of economically disadvantaged citizens than other parts of California ({numref}`ces-son`). Many rural areas have experienced a double whammy of high poverty and brain drain from the exodus to urban areas of people who cannot find work. These areas often coincide with heavily forested regions.

:::{figure} sonoma-ces.png
:label: ces-son
:height: 400px
Poverty percentage in Sonoma County by census tract. Green (low), Yellow (medium), and Red (high). CalEnviroScreen 4.0.
:::

:::{important} Wildfire
:class: dropdown

Except desert and agricultural lands, most of California has burned at some point during the past 150 years (map of fire perimeters from CALFIRE). Fires have become increasingly intense over time, mostly exacerbated by climate change. The map shows all fires grouped by decade (older fires are lighter in color, newer are darker). 

Recently, Sonoma County has experienced several high-severity wildfires. The 2017 Tubbs fire burned 36,807 acres, destroying many houses and causing nearly $9.6 billion in damages, mostly in Santa Rosa. The foothills east of Santa Rosa have burned repeatedly in the past few years.

Estimates from the Sonoma Wildfire Hazard Index and US Census show that 15,437 Sonoma County residents, or 3% of the population, live in areas of extreme wildfire risk ( Sonoma CWPP, 2023 ). Nearly 14,000 buildings in this landscape are at extreme wildfire risk, and if burned, they could account for roughly $9 billion in losses (Ibid).
:::

## Fire Impact
Higher poverty and fire frequency are connected. @hino found a correlation between high poverty and wildfire frequency ([numref]`hino-map`).  @king found similar results with 6.7 million private forest treatable acres; four million acres are concentrated in High Poverty Census Tracts of California; that is, 60% of total private treatment needs are concentrated in areas where the poverty rate exceeds 20%—two times the national average. The same authors estimated 231,000 acres in need of treatment, with 71% located in high-poverty areas (poverty rate > 20%).

:::{figure} hino.png
:label: hino-map
:height: 600px
Fire experience by census tracts and corresponding median income by experience group
:::

According to the feasibility study, treating 246,365 acres within Sonoma County is feasible. Below, we estimate the number of people needed to conduct forest treatments at this scale over time.