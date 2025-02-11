instructions:

1) clone this repo using your chosen IDE, I use pycharm and you can get a free professional version as a student
2) open a terminal and run `pip install -r requirements.txt`


## Project plan:

### Hypothesis: 
- Does the cost of fuel have an impact on electricity generation

#### Data Cleaning, Preprocessing (Safia) 
- Y: Electricity Net Generation (MWh)
- X: from page 1 (will need to get pivoted): [Month, Quantity Consumed in Physical Units for Electric Generation, Physical Unit Label, Reported Prime Mover, Reported Fuel Type Code, Operator Name (or ID), Plant State, Census]
- X: from Page 5: [ENERGY_SOURCE, FUEL_GROUP, QUANTITY, Average Heat Content, Average Sulfuer Content, Average Ash Content, FUEL_COST, Moisture Content, Primary Transportation Mode, ]

#### EDA (Sharon, Linda)
- Paired scatterplots (x values vs y)
- correlation matrix
- histograms (especially for Y)
- line graphs

#### Feature Engineering (Nash)
- cost per unit of energy (MWh), which requires some conversions
- encoding for categorical variables
- May need to log transform or a box cox




- Nash: 
- Sharon:
- Linda:
  - 
- Safia: R
  - Data cleaning
- Alex:
  - 
