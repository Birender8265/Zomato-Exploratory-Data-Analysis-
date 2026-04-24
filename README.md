🍽️ Zomato Dataset — Exploratory Data Analysis (EDA)






📌 Project Overview


This project performs a comprehensive Exploratory Data Analysis (EDA) on the Zomato Restaurant Dataset — a globally recognised food delivery and restaurant discovery platform dataset. The goal is to uncover meaningful patterns and insights about restaurant distribution, customer ratings, online delivery availability, and country-wise usage trends.
By combining the core Zomato dataset with a country-code mapping file, this analysis produces a clean, enriched dataset that enables multi-dimensional exploration across geography, ratings, and service offerings.




🔍 Key Features & Analysis Performed
1. 🌍 Country-wise Distribution

Identified the top 3 countries by number of Zomato records using a pie chart.
Finding: India dominates Zomato's data, followed by the USA and the United Kingdom.

2. ⭐ Rating Analysis

Grouped restaurants by aggregate_rating, rating_color, and rating_text to understand the rating distribution.
Plotted bar charts with color-coded rating categories:

4.5–4.9 → Excellent (Dark Green)
4.0–4.4 → Very Good (Green)
3.5–3.9 → Good (Yellow)
3.0–3.4 → Average (Orange)
2.0–2.9 → Poor (Red)
0 → Not Rated (White/Blue)


Finding: A large proportion of restaurants are unrated, and most rated restaurants fall in the 2.5–3.4 range.

3. 🚫 Zero-Rating Investigation

Filtered records where aggregate_rating == 0 and rating_color == 'White'.
Finding: India accounts for the maximum number of zero/unrated restaurants.

4. 💳 Currency by Country

Mapped each country to the currency used on the Zomato platform.

5. 🛵 Online Delivery Availability

Analysed which countries have restaurants offering online delivery.
Finding: Online delivery is available only in India and UAE.

6. 🏙️ Top Cities Distribution

Visualised the top 5 cities by restaurant count using a pie chart.




👤 My Role & Responsibilities
🔧 Data Collection & Loading

Sourced the Zomato dataset and the Country Code mapping file.
Loaded and inspected both files using Pandas, handling encoding issues (latin-1 for the CSV).

🧹 Data Cleaning & Preprocessing

Used .isnull().sum() to identify and assess missing values across all columns.
Applied column renaming with snake_case conventions for readability and consistency.
Performed a left merge of the main dataset with the country code lookup file to enrich the data.

📐 Exploratory Data Analysis

Conducted shape, info, and describe analysis to understand the structure and statistical properties of the dataset.
Analysed rating categories by cross-referencing aggregate_rating, rating_color, and rating_text.
Investigated zero-rated restaurants and filtered data by country-level conditions.
Explored service availability (online delivery) at a country level.

📈 Data Visualisation

Designed and customised pie charts, bar plots, and count plots using Matplotlib and Seaborn.
Annotated each visualisation with clear labels and percentage breakdowns.

💡 Insight Generation

Documented observations after each analysis block to translate visual findings into business-relevant insights.
Drew conclusions on Zomato's geographic dominance, rating behaviour, and delivery availability.





📬 Contact
Feel free to connect or reach out:

GitHub: https://github.com/Birender8265

LinkedIn: https://www.linkedin.com/in/birendra-singh-28183339b

Email: birendersingh9917@gmail.com
