"# EDA-Playstore_Data_Analysis" 



📘 Play Store Apps EDA – Data Analysis Project
📌 Overview

This project performs Exploratory Data Analysis (EDA) on the Google Play Store dataset to uncover insights about app categories, user preferences, install patterns, rating behaviors, and market opportunities.
The goal is to help developers, product teams, and businesses make strategic decisions regarding app development, pricing, and user targeting.

📁 Dataset Description

The dataset contains the following key attributes:

App – App name

Category – Category under which the app is listed

Rating – User rating

Reviews – Total reviews submitted

Size – App size

Installs – Number of installs

Type – Free or Paid

Price – Cost of the app

Content Rating – Age-based restrictions

Genres – Sub-category

Last Updated – Last update date

Current Version / Android Version – Compatibility details

The dataset was cleaned and processed before performing any analysis.

🎯 Business Problems

This project aims to answer the following business questions:

Which categories dominate the Play Store?

Which app types (Free vs Paid) attract more users?

How does content rating influence user reach?

Which categories generate the highest total installs?

Does a high user rating ensure high installs?

How does pricing impact user installation behavior?

What app size do users prefer?

How strongly do reviews correlate with install count?

Which categories receive the best user ratings?

Which categories are ideal for new developers to enter?

📊 Key Insights

Here are some high-level insights discovered during the analysis:

Family, Game, and Tools have the highest number of apps → high competition.

Users prefer Free apps, making freemium the best monetization model.

Apps rated “Everyone” attract the highest number of downloads.

Gaming, Social, and Communication apps lead in total installs.

Ratings show weak correlation with installs; reviews show strong correlation.

Apps sized 10MB–40MB perform the best in install count.

Categories like Finance, Education, and Productivity show strong potential for new developers.

Very large apps are installed mainly in niches like Gaming or Video Editing.

Review count significantly boosts overall visibility and downloads.

For a complete insights report, refer to insights.txt.

🧠 Business Solutions

Based on analysis, the following solutions are recommended:

✔ Market Entry Strategy

Focus on moderately competitive, high-demand categories:
Finance, Education, Lifestyle, Sports, Productivity

✔ Pricing Strategy

Use a Freemium Model instead of a fully paid app.
Paid apps attract very low download volume.

✔ App Optimization

Keep the app lightweight — preferably under 40MB.

✔ User Engagement

Encourage users to leave reviews, as install count strongly correlates with review volume.

✔ Target Audience Strategy

Aim for an “Everyone” content rating to maximize reach.

📈 Visualizations Included

This project includes:

Category Distribution (Pie Chart)

Top 10 Categories (Bar Plot)

Free vs Paid Apps Distribution

Rating Distribution

Installs Distribution

Scatter Plots (Rating vs Reviews, Size vs Installs, Price vs Installs)

Correlation Heatmap

Content Rating Distribution

Category vs Install Count Chart

All plots are available inside the Jupyter Notebook.

🧹 Data Cleaning Performed

Removed duplicate entries

Cleaned Install values (removed commas + converted to int)

Converted Price to numeric

Converted Size (“M” and “k”) into unified numeric values

Handled missing ratings

Cleaned and formatted “Last Updated” column

Encoded categorical values for analysis

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn
