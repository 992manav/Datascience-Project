# 🚗 Indian Used Car Price Prediction
By Manav Desai and Tushar Madan

![Car GIF](https://cdn.pixabay.com/animation/2023/01/24/23/10/23-10-50-478_512.gif)

---

## 📌 Project Overview

- Focuses on predicting the price of used cars in major Indian metro cities.
- Uses various car features for prediction such as:
  - Manufacturer
  - Model
  - Variant
  - Fuel type
  - Color
  - Kilometers driven
  - Body style
  - Transmission type
  - Manufacture date
  - Model year
  - CNG kit availability
  - Ownership history
  - Dealer details
  - Quality score
- Applies data analysis and machine learning techniques.
- Helps both buyers and sellers make informed decisions in the used car market.

## Data Dictionary

Here is a detailed data dictionary for the columns in the "Indian IT Cities Used Car Dataset 2023":

| Column Name       | Description                            |
| ----------------- | -------------------------------------- |
| ID                | Unique ID for each listing             |
| Company           | Name of the car manufacturer           |
| Model             | Name of the car model                  |
| Variant           | Name of the car variant                |
| Fuel Type         | Fuel type of the car                   |
| Color             | Color of the car                       |
| Kilometer         | Number of kilometers driven by the car |
| Body Style        | Body style of the car                  |
| Transmission Type | Transmission type of the car           |
| Manufacture Date  | Manufacture date of the car            |
| Model Year        | Model year of the car                  |
| CngKit            | Whether the car has a CNG kit or not   |
| Price             | Price of the car                       |
| Owner Type        | Number of previous owners of the car   |
| Dealer State      | State in which the car is being sold   |
| Dealer Name       | Name of the dealer selling the car     |
| City              | City in which the car is being sold    |
| Warranty          | Warranty offered by the dealer         |
| Quality Score     | Quality score of the car               |

## Conclusion

In the course of this data science project aimed at predicting used car prices in major Indian metro cities, several significant insights have emerged through exploratory data analysis and machine learning techniques. These insights shed light on both the demand and pricing dynamics within the Indian used car market, offering valuable information to both prospective buyers and sellers.

### 1. Price and Demand Relationship

- **Budget-friendly options dominate**: We discovered a clear inverse relationship - lower-priced used cars enjoy significantly higher demand in the market
- **Luxury segment behavior**: Brands like Mercedes Benz, BMW, Volvo, MG, and KIA command premium prices even in the used market
- **Interesting consumer psychology**: Many buyers prefer purchasing new luxury vehicles rather than pre-owned ones, creating a unique market dynamic

### 2. Fuel Type Impact

- **Market composition**: The market is primarily split between petrol and diesel vehicles
- **Price premium for diesel**: Despite not being overwhelmingly common, diesel cars consistently fetch slightly higher prices than their petrol counterparts
- **Fuel efficiency consideration**: This price difference likely reflects the long-term fuel economy benefits diesel engines provide

### 3. Color Preferences and Pricing

- **Conservative color dominance**: White, grey, silver, and black cars represent the majority of listings, indicating strong market demand
- **Premium for distinctive colors**: Interestingly, more unique colors like burgundy, riviera red, dark blue, and black magic command higher prices
- **Style vs. practicality**: This suggests that while most buyers prefer traditional colors, those seeking distinctive options are willing to pay more

### 4. Mileage Matters

- **Low mileage prevalence**: Most cars in our dataset have traveled less than 10,000 kilometers
- **Clear pricing correlation**: As expected, cars with lower odometer readings fetch substantially higher prices
- **Sweet spot for value**: The data reveals a noticeable price drop once cars exceed certain mileage thresholds

### 5. Body Style Preferences

- **Popular choices**: Hatchbacks, SUVs, and sedans are the most sought-after body styles
- **Premium segments**: MPVs and luxury SUVs command higher prices due to their specialized nature
- **Changing urban preferences**: We noticed increasing SUV popularity in metro areas, reflecting evolving consumer tastes

### 6. Age and Resale Value

- **Depreciation reality**: Car age emerged as one of the strongest price predictors
- **5-year threshold**: Vehicles under 5 years old maintain substantially better resale values
- **Rapid early depreciation**: The steepest price drops occur in the first few years of ownership

### 7. Geographic Price Variations

- **Regional pricing differences**: Substantial price variations exist across different Indian states
- **Premium markets**: Delhi, Maharashtra, and Rajasthan consistently show higher used car prices
- **Dealer influence**: Specific dealers like Car Estate, Star Auto India, and Car Choice list vehicles at premium prices

### 8. Ownership History Impact

- **First owner premium**: Cars with a single previous owner command higher prices
- **Consumer psychology**: Buyers perceive first-owner vehicles as better maintained and more reliable
- **Documentation factor**: Better documentation and service records typically accompany first-owner vehicles

### 9. Warranty Value

- **Price boost**: Cars sold with warranties fetch slightly higher prices
- **Peace of mind premium**: Buyers are willing to pay extra for the security a warranty provides
- **Dealer opportunity**: This represents a potential value-add strategy for dealers

### 10. Quality Score Correlation

- **Direct relationship**: Higher quality scores directly translate to higher market prices
- **Consumer confidence**: Quality scores serve as a trusted benchmark for buyers
- **Investment in quality**: For sellers, maintaining vehicle condition yields measurable financial returns

### 11. Model Performance

- **Algorithm comparison**: We tested multiple machine learning models for price prediction
- **Random Forest superiority**: The Random Forest Regressor outperformed other models in accuracy
- **Key drivers identified**: Our feature importance analysis revealed car age, body style, and manufacturer as the most critical pricing factors

This analysis provides valuable intelligence for anyone navigating the Indian used car market. Whether you're a buyer seeking the best value, a seller aiming to optimize pricing, or a dealer refining inventory strategy, these insights can help you make more informed decisions in this dynamic marketplace.
