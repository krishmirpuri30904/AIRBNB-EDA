🏠 Airbnb Data Analysis (USA)

This project performs Exploratory Data Analysis (EDA) on Airbnb listings in the USA to uncover insights related to pricing, room types, neighborhood distribution, customer behavior, and booking trends.

📁 Project Overview

The goal of this project is to analyze Airbnb listing data and extract meaningful insights that can help:

Understand pricing distribution

Identify popular room types

Analyze listing concentration across neighborhoods

Study customer engagement through reviews

Evaluate booking patterns and policies

The dataset contains 100K+ listings with multiple attributes such as price, room type, neighborhood, reviews, availability, and more.

🛠️ Tools & Technologies

Python

Pandas & NumPy

Matplotlib & Seaborn

Jupyter Notebook

🔍 Data Cleaning & Preprocessing

Removed irrelevant columns:

ID, Host ID, License, House Rules

Handled missing values:

Dropped rows where necessary

Filled reviews_per_month and last_review appropriately

Converted data types:

Date columns standardized

Price & service fee cleaned (removed $ symbol)

Removed duplicates for consistency

📊 Exploratory Data Analysis
💰 Price Distribution

Histogram shows a fairly even spread of listing prices across ranges (page 8)

Prices range widely (~$50 to $1200), indicating diverse accommodation options

🏡 Room Type Distribution

Entire home/apartment: ~52% (majority)

Private room: ~45%

Hotel & shared rooms: minimal (page 10)

👉 Indicates users prefer full property rentals over shared stays

🏙️ Listings by Neighborhood

Manhattan has the highest number of listings

Followed by Brooklyn (page 12)

👉 Suggests strong demand and supply concentration in prime locations

💵 Price vs Room Type

Median price ~$620–$640 across all room types

Price ranges are similar across categories (page 14–15)

👉 Indicates:

Limited differentiation in pricing across room types

Possible platform pricing normalization

📈 Reviews Over Time

Sharp spike around 2019 (peak Airbnb usage)

Extremely high future dates (2024–2050) indicate data quality issues (page 16)

👉 Important takeaway:

Always validate temporal data before modeling

🛏️ Minimum Nights Analysis

Manhattan: highest (~9.5 nights)

Bronx: lowest (~5 nights) (page 17–18)

👉 Suggests:

Premium areas encourage longer stays

Budget areas favor short-term bookings

📜 Cancellation Policy

Even distribution across:

Moderate (~33%)

Strict (~33%)

Flexible (~33%) (page 18)

👉 No dominant policy → balanced platform strategy

📌 Key Insights

Airbnb listings are heavily concentrated in Manhattan and Brooklyn

Majority of users prefer entire homes over shared spaces

Pricing is relatively consistent across room types

Review trends highlight peak usage periods and data anomalies

Booking behavior varies significantly across neighborhoods

🚀 Business Implications

Hosts in high-demand areas can optimize pricing strategies

Airbnb can improve:

Data quality (future dates issue)

Pricing differentiation across room types

Targeted marketing can be applied based on:

Location

Stay duration patterns
