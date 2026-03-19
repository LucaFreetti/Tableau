# Tableau
A Tableau data visualization project analyzing the carbon footprint of food production across its full lifecycle. Built on peer-reviewed research (Poore &amp; Nemecek, Science 2018), the project debunks the "eat local" myth and provides data-driven recommendations for designing a low-carbon restaurant menu.

# Designing a Low-Carbon Menu: Data-Driven Insights for a Sustainable Restaurant

## Objective
This project uses data visualization to explore the environmental impact of food production
and translate those insights into a concrete, actionable menu strategy for a sustainable restaurant.
The central argument: what we eat matters far more than where food comes from.

## Key Questions
- Which foods have the highest carbon footprint across their lifecycle?
- Does eating local actually reduce emissions significantly?
- How does animal-based vs plant-based food production compare in terms of GHG emissions?
- What is the hidden climate cost of land use?
- Which countries waste the most food, and why does it matter?

## Data Source
- Poore & Nemecek (2018), *Reducing food's environmental impacts through producers and consumers*, Science
- [Our World in Data — GHG Emissions by Lifecycle Stage](https://ourworldindata.org)

## Visualizations
The project includes 6 interactive Tableau dashboards:

| Dashboard | Description |
|---|---|
| CO₂ Emissions by Deforestation | World map of emissions caused by land clearing for food production |
| The "Eat Local" Myth | Treemap breaking down emissions by lifecycle stage (farm, transport, packaging...) |
| Animal vs Plant-Based Emissions | Bubble chart comparing the share of emissions by food type |
| CO₂ Emissions by Food Product | Dot plot ranking individual foods by carbon footprint per kg |
| Carbon Opportunity Cost | Bar chart showing the hidden cost of land use for animal-based foods |
| Food Waste per Capita | Stacked bar chart of the top 10 countries for food waste |

🔗 **[View Interactive Dashboards on Tableau Public](#)**
*https://public.tableau.com/app/profile/luca.frittitta/viz/Esametableau_17720533271220/Dashboard1*

## Key Findings
- Food production accounts for approximately 25% of global greenhouse gas emissions
- Transport represents less than 10% of total food emissions — for beef it is often below 1%
- Animal-based foods are responsible for 63.8% of food-related CO₂ emissions
- Producing 1 kg of beef emits ~60 kg CO₂e, compared to ~1 kg for peas
- Sheep and goat meat carry a carbon opportunity cost of 186 kg CO₂e per kg — the highest of any food
- The global average food waste per capita is 31 kg/year; Mexico reaches 214 kg

## Menu Strategy Recommendations
- Make plant-based dishes the default option
- Limit high-impact items: beef, lamb, high-emission dairy
- Replace red meat with poultry or plant-based proteins
- Label low-carbon choices visibly on the menu
- Reduce food waste through portion planning and creative use of leftovers

## Repository Structure
```
/
├── README.md
├── presentation/
│   └── low_carbon_menu_tableau.pdf
└── data/
    └── ghg-emissions-by-lifecycle-stage.csv
```

## Tools
- Tableau Public — data visualization and interactive dashboards
- Data source: Our World in Data / Poore & Nemecek 2018
