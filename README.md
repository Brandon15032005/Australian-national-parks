# Australia's National Parks: are we protecting the right places, and who uses them?

A data visualisation web page for FIT3179 Data Visualisation 2, Monash University.
Author: Brandon Koh Shin.

**Live page:** https://brandon15032005.github.io/Australian-national-parks/

## What is in this repository
| Folder or file | What it holds |
|---|---|
| `index.html` | The web page (HTML, CSS and JavaScript). It loads each chart from `specs/`. |
| `specs/` | One Vega-Lite JSON file for each chart (listed below). |
| `data/` | The cleaned data the charts use. `data/README.md` explains where each file comes from. |

## The charts (`specs/`)
| File | Chart |
|---|---|
| `waffle.json` | Waffle chart of protected land by type |
| `choropleth.json` | Map of the share of each state's land that is protected |
| `butterfly.json` | Butterfly chart: share of protected land against share of population |
| `tilegrid.json` | Tile grid map: people for every square kilometre of protected land |
| `parks_map.json` | Map of every national park, sized by area (state selector) |
| `parks_bins.json` | Binned map: how many national parks fall in each 200 km square |
| `parks_jitter.json` | Jitter plot of park sizes by state (hover to highlight a state) |
| `bio_lollipop.json` | Lollipop chart of the least and most protected natural regions |
| `bio_heatmap.json` | Heatmap of how strictly each of those regions is protected |
| `visits_map.json` | Map of places with published visit counts (click the key to focus on one agency) |
| `visits_inset.json` | Zoom on Greater Sydney for the visits map |
| `visits_inset_tas.json` | Zoom on Tasmania for the visits map |
| `nsw_top20.json` | Lollipop chart of the 20 most visited NSW parks |
| `nsw_trend.json` | Line chart of total NSW park visits, 2008 to 2024/25 |
| `tas_slope.json` | Slope chart of visits at 12 Tasmanian sites |
| `visits_recovery.json` | Heatmap of each place's visits as a share of its own busiest year |
| `dotplot.json` | Connected dot plot of each state against the 30% protection goal |

## Data sources
- Department of Climate Change, Energy, the Environment and Water (DCCEEW), Collaborative Australian Protected Areas Database (CAPAD) 2024, data at 30 June 2024 (CC BY).
- DCCEEW, Achieving 30 by 30, updated 22 July 2026.
- Australian Bureau of Statistics, National, state and territory population, March 2026.
- NSW National Parks and Wildlife Service, park visitor survey, 2008 to 2024/25.
- Tasmania Parks and Wildlife Service, Visitors to Selected Parks and Reserves, 2020-21 to 2025-26.
- Director of National Parks (Parks Australia), Annual Reports 2022-23 and 2024-25.
- State outlines: github.com/rowanhogan/australian-states.

## AI acknowledgment
Claude AI guided me and helped me in most parts, including the data and the code. Another AI tool also helped me find datasets.
