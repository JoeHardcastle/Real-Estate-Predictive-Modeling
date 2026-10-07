# Real Estate Predictive Modeling: Cross-Market Valuation
### A Comparative Spatial and Economic Analysis of the Delhi Residential Real Estate Market

📧 **jhrdcstl77@gmail.com** | 💻 **https://github.com/JoeHardcastle**

---

## Project Overview & Objectives
This data science project looks at the residential housing market across two major locations in Delhi: Dwarka Mor and Uttam Nagar. 

While the raw, uncleaned dataset contained many different neighborhoods across the Delhi National Capital Region (NCR), the data-cleaning phase revealed that these specific two locations contained the most robust, high-volume sample sizes within the selected price range of 40 to 80 Lakhs. By filtering the data to this specific lower-middle class price band, the primary objective of this project is to evaluate how area of property, the number of bedrooms, and premium amenities influence the valuation of the properties.

---

## Key Project Discoveries
- **Cleaning Raw Data:** Managed a complete data preparation by checking for missing values, finding and dropping duplicate entries, fixing categorical anomalies, and removing outliers to focus strictly on the 40–80 Lakhs price group.
- **Visual Asset Mapping:** Formatted grouped bar charts to cross-examine the exact percentage of available amenities across the four most data rich locations. Followed this with focused box plot comparison charts mapping property prices against amenity distributions specifically within Dwarka Mor and Uttam Nagar to expose price variances between the two locations.
- **Fixing Price Skewness:** Identified that the property prices were right-skewed. By transforming the prices using a natural logarithm, the data's skewness was significantly reduced, making it fit the regression models accurately.

- **Micro-Market Differences:** Mathematically proved that the two neighboring areas operate quite differently. While the slightly more premium Dwarka Mor market strongly rewards absolute square footage, the high-density market of Uttam Nagar fundamentally rewards room counts and infrastructure (making a secure parking spot highly valued).
- **Practical Application:** Built a custom testing script that allows a user to input identical house specifications to run a direct comparison test. This script programmatically finds hidden property deals where a house in the upmarket region of Dwarka Mor can actually cost less than a smaller home in Uttam Nagar under identical requirements.

