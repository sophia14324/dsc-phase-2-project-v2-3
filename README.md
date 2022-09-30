# Analysis and Prediction of House Sales in King County for potential external customers
## Business Understanding


King County is a county located in the U.S. state of Washington. The house prices and its spatial distribution are important for stakeholders in
the real estate business particularly in metropolitan areas. Stakeholders, such as, external customers looking to
purchase or sell a house in King County, they would require to decide on the house to choose based on the
variety of parameters associated with the house prices. The objective of the study is to use statistical analysis
to find the dependence of these variables on the price of houses, and which parameters affect the housing
prices and which variables have minimal affect on the price of houses and ultimately make recommendations to
stakeholers. The statistical tools used are, Correlation and Regression. Insights between the variables are
drawn from scatter and regression plots, and histogram.

## Data Understanding

The dataset we have taken is House sales in King County, which can be found in kc_house_data.csv in the
data folder. The data contains the prices of houses against a variety of parameters, for example, bedrooms, bathrooms/bedroom, square foot area of the house and lot,
presence of a waterfront, views, condition of the house, grade assigned by the county, built year, renovated
year and the location of the house. 

## Stakeholder audience

The stakeholder audience for this project is any external customers looking to purchase or sell a house in King County, USA.

## Modeling
### Simple Linear Regression (Baseline Model)
![graph](simpleRegression.png)

### Multiple Linear Regression (Baseline Model)
![Screenshot](Regression.png)


## Regression Results

The adjusted R-Squared for simple linear regression: 0.46107169815138016

The adjusted R-Squared for multiple linear regresion: 0.5127811244220679

The Error-Based Metric (mean absolute error) for simple linear regression: 166350.62192683897

The Error-Based Metric (mean absolute error) for multiple linear regression: 159875.09332006477

## Conclusion
The data understanding, data preparation and data cleaning allowed me analyze, model and evaluate the data
on the King County dataset. The key takeaways are that sqft_living, waterfront, sqft_lot15 and bedrooms are
the best predictors of a house's price in King County.
