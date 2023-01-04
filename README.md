# Vermont-RE-Price-Prediction
Predicting home prices in West Dover Vermont to shop for Airbnb properties
We're excited to dive into the real estate market in West Dover, VT and uncover some valuable insights! Here's a summary of our findings so far:

Positive Relationship Between Time of Sale and Price per Square Foot 📈
It looks like there's a strong positive correlation between the time a property was sold and its price per square foot. In fact, the median price per square foot saw a significant increase of 23% from 2020 to 2022. Additionally, when comparing the 75th percentile, we see that in 2022, 75% of properties sold for a price per square foot of less than $284, compared to just 67% in 2021. This represents a staggering 75% increase in value.

Non-Linear Relationship Between Living Space and Sold Price 🏠
The data suggests that the relationship between living space in square feet and the sold price of a property is non-linear. The sold price becomes less sensitive to the size of a property beyond 3,000 square feet, while homes with sizes less than 3,000 square feet tend to fit well around the regression line, indicating that the sold price is more sensitive to the size of the property in this range.

Using XG Boost to Train Model 🤖
We're using the XG Boost algorithm with a maximum depth of 6 trees and regularization to train our model on a cleaned dataset. Our loss function is the Mean Squared Error and our evaluation metric is the Mean Absolute Error. We'll be running 16 boost iterations until the model converges.
