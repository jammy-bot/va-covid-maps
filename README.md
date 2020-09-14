# va-covid-maps
Geospatial data exploration, based on my previous repository: https://github.com/jammy-bot/va-covid-eda

In notebooks at the [va-covid-eda](https://github.com/jammy-bot/va-covid-eda) github repository, we explore how cases of Coronavirus, consequent hospitalizations, and related deaths in Virginia's Hampton Roads region compare to those reported in other areas of the state, including the state's capital city of Richmond. We relied on interactive plotting with Plotly Express, to visualize data for multiple localities (including population data) on a single figure, with the option to hover or drill - down for greater detail (link to [Featured Notebooks](https://github.com/jammy-bot/va-covid-eda#featured-notebooks)).

Animated plots used in our previous notebooks enable us to quickly make visual comparisons across multiple localities, over time. Even the few static plots we include clearly indicate that the Fairfax area was impacted more severely than other localities, in raw numbers as well as by per 1,000 of locality population. However, the plots do not easily reference some factors likely influencing the spread of the virus. They do not show us that Fairfax borders Washington, D.C., or that Virginia Beach (in Hampton Roads) is a regional tourist destination. This type of information might be better communicated, at a glance, by incorporating relevant maps images into our visualizations. That is what we will do in this current exploration.

We will recall datasets from our previous exploration and stay within the same timeframe, for the sake of consistency. We also want to maintain a level interactive publishing ability, comparative to that which--by using the Plotly Express and Datapane libraries on Deepnote-- we previously attained.
