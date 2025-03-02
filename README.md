# STAT-340 Applied Regression Methods Mini Projects

## Mini Project 1

The wine industry is investing in new technologies for both wine making and selling processes. Wine certification and quality assessment are key elements within this context. Certification prevents the illegal adulteration of wines (to safeguard human health) and assures quality for the wine market. Wine certification is generally assessed by physicochemical and sensory tests. Physicochemical laboratory tests routinely used to characterize wine include determination of density, alcohol or pH values, while sensory tests rely mainly on human experts.

In this mini-project, we are interested in learning about the variables that may be related to the wine density.

We will use the dataset "wine" and focus on the following variables:

• `density`: the wine density measured in grams per milliliter (g/mL)

• `citric_acidity`: amount of citric acid per liter (g/L)

• `residual_sugar`: amount of residual sugar per liter (g/L)

• `chlorides`: amount of sodium chloride per liter (g/L)

• `total_sulfur_dioxide`: total amount of sulfur dioxide per liter (mg/L)

• `alcohol`: percentage of alcohol in the wine (% vol)



## Mini Project 2

#### Part 1: Validation of model assumptions

Overall mortality indicators (e.g., life expectancy at birth or survival to a given age) are important indicators of health status in a country. Because data on the incidence and prevalence of diseases are frequently unavailable, mortality rates are often used to identify vulnerable populations. And they are among the indicators most frequently used to compare socioeconomic development across countries.

The data in this problem is from World Health Organization (WHO) and the United Nations Population Division and contain the following variables for 170 countries:

• `LifeExpectancy2015`: the life expectancy at birth in the year 2015 (number of years a newborn infant would live if prevailing patterns of mortality at the time of its birth were to stay the same throughout its life)

• `IncomeGroup`: the country’s income group (low, lower-middle, upper-middle, and high)

• `Polio`: Polio immunization coverage among 1-year-olds (%)

• `IncomeCompositionResources`: Human Development Index in terms of income composition of resources (index ranging from 0 to 1)

• `Schooling`: Number of years of Schooling (years)

#### Part 2: Polynomial Regression

The following R code loads in a data set with measurements of the tensile strength of paper (`tensile`, in units of pounds per square inch), and the percent of hardwood in the batch of pulp that was used to produce the paper (`hardwood`), for 19 diﬀerent samples of paper with diﬀerent percent hardwoods.
