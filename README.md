# SmartCabinPrice Predictor

Final project for the Building AI course

## Summary

SmartCabinPrice Predictor is an AI tool that estimates the market price of cabins based on their features using machine learning. This Building AI course project demonstrates how data-driven predictions can help buyers and sellers make informed decisions.

## Background

Cabin pricing can be complex due to many influencing factors like size, sauna, proximity to lakes, and neighborhood density. This project aims to:  
* Help buyers quickly estimate fair prices.  
* Assist sellers in setting competitive prices.  
* Provide insights into which cabin features affect price most.  

Motivation: Personal experience with vacation property searches showed that many listings lack price transparency. AI can make pricing more objective and accessible.  

## How is it used?

The user enters cabin details (e.g., square meters, sauna size, number of bathrooms, distance to lake, distance to neighbors) into a web or mobile interface. The AI predicts the likely market price in real-time.  

Users:  
* Potential cabin buyers looking for fair pricing.  
* Sellers wanting competitive, data-informed pricing.  
* Real estate agents for automated valuation insights.  

Example image (replace with your own visualization or chart):

![Cabin Pricing Example](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

Code snippet for demonstration:
```python
# Example: Predict cabin price using a trained neural network
import numpy as np

x_test = np.array([[82, 2, 65, 3, 516]])
predicted_price = model.predict(x_test)
print(f"Predicted cabin price: €{predicted_price[0]:,.0f}")
