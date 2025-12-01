# Bali-Hotels-Data-Analysis-and-Insights
🏨 Bali Hotels Data Analysis & Insights

Author: Talasila Om Prakash

This repository contains the complete workflow of web scraping, data cleaning, and exploratory data analysis (EDA) performed on Bali hotel listings. The goal is to uncover meaningful insights about hotel pricing, ratings, locations, and guest experiences.

📌 Project Overview

Bali attracts millions of tourists every year, resulting in a huge number of hotel listings. However, understanding how price, location, reviews, and ratings influence customer decisions is a challenge.

This project analyzes these factors to discover patterns that can help:
✔ Hotel owners
✔ Travel platforms
✔ Tourists
✔ Tourism market analysts

🎯 Project Objectives

Analyze the relationship between hotel ratings and prices.

Study how location influences pricing and popularity.

Identify the most preferred hotel categories (Excellent / Very Good / Good).

Understand price variations and detect outliers.

Extract insights using advanced visualizations.

Provide recommendations to improve hotel marketing, pricing, and service strategies.

🕸️ Web Scraping Process
Tools Used:

Python

BeautifulSoup

Requests

Pandas

Steps:

Selected a travel website with Bali hotel listings.

Inspected HTML elements to extract hotel name, price, rating, location, etc.

Scraped data from multiple pages.

Stored the extracted data in a Pandas DataFrame.

Cleaned and prepared the dataset for EDA.

🧹 Data Cleaning Steps

Removed duplicates

Handled missing values

Fixed inconsistent naming formats

Converted price values into numeric format

Dropped irrelevant fields

Standardized text (locations, categories)

Cleaned currency symbols and formatting

📊 Exploratory Data Analysis (EDA)
Univariate Analysis

Most hotel prices fall in the ₹4,000–₹8,000 range.

“Very Good” is the most common experience rating (~68%).

Excellent-rated hotels = ~24%.

Poorly rated hotels are extremely few.

Bivariate Analysis
⭐ Rating vs Price

Higher-rated hotels tend to have higher minimum prices.

⭐ Price vs Distance

Price has very weak correlation with distance from the city center.

⭐ Minimum Price vs Maximum Price

Strong positive correlation (0.95).

Categorical vs Continuous

Excellent and Very Good categories have higher price ranges.

Budget hotels mostly fall under Good and Review Score categories.

Location-Based Analysis

Top locations with maximum hotel listings:

Seminyak

Kuta

Ubud

These regions also have the largest share of Excellent and Very Good rated hotels.

Multivariate Insights (Location + Rating + Price)

Premium locations: Nusa Dua, Ubud, Seminyak, Jimbaran
→ Consistently high hotel prices

Affordable regions: Amed Beach, Tejakula, Kerobokan

Pricing is influenced more by location + rating than by distance.

🗝️ Key Insights

Bali maintains high hospitality standards across most hotels.

Location significantly impacts price, not rating.

Mid-range hotels dominate the market.

Budget hotels form a small percentage.

Premium areas consistently show high pricing.

⚠️ Challenges Faced

Dynamic website structure caused scraping interruptions.

Inconsistent HTML elements

Multiple currency formats

Duplicate hotel entries

Cleaning varied text formats

📚 Learnings

Improved understanding of web scraping with BeautifulSoup.

Learned real-world data cleaning techniques.

Gained expertise in creating visualizations using:
✔ Scatter plots
✔ Heatmaps
✔ Violin plots
✔ Box plots
✔ Bar charts

Understood how pricing, rating, and location influence hotel performance.

📝 Repository Contents

📁 Bali Hotels Data Analysis & Insights

bali_hotels_data.csv

web scrapping on traveltriangle (1).ipynb

eda and visualization .ipynb

eda ppt on bali Hotels'.pptx

README.md


✅ Conclusion

Bali’s hospitality market is highly competitive and customer-friendly.
Most hotels offer good to excellent service, regardless of price.
Hotel prices depend more on location than rating.
The island provides a mix of budget, mid-range, and premium hotels to suit different travelers.

