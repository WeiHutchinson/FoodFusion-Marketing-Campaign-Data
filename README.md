# FoodFusion Marketing Campaign Data Analysis

## Overview

The **FoodFusion Marketing Campaign Data** is a simulated dataset designed to provide a realistic scenario for analysing marketing campaigns. This dataset includes user interactions with marketing messages from FoodFusion, a meal kit delivery service, across various channels. It also contains information about users' subscription status, retention status, dietary preferences, preferred meal types, location, and age group. This project aims to explore key marketing data science concepts, such as conversion analysis, retention analysis, and segmentation.

## Dataset Description

The dataset includes the following columns:

- **user_id:** Unique identifier for each user.
- **date_served:** Date the marketing message was served.
- **subscribing_channel:** Marketing channel through which the user subscribed (e.g., Email, Facebook, Instagram, Push, House Ads, Influencers).
- **converted:** Boolean indicating if the user subscribed after receiving the marketing message.
- **is_retained:** Boolean indicating if the user was retained after subscribing. *(Retention period is set as one month, aligned with the discounted trial duration.)*
- **dietary_preference:** Dietary preference of the user (e.g., Vegan, Vegetarian, Gluten-Free, Keto, Omnivore).
- **meal_type:** Type of meal kit preferred (e.g., Breakfast, Lunch, Dinner, Snack).
- **location:** Borough of London where the user is located (e.g., Camden, Greenwich, Hackney, Hammersmith and Fulham, Islington).
- **age_group:** Age group of the user (e.g., 0-18 years, 19-24 years, 25-30 years, 31-36 years, 37-45 years, 46+ years).

## Analysis Objectives

### 1. Conversion Analysis
- **Overall Conversion Rate:** Calculate the percentage of users who subscribed after receiving a marketing message.
- **Conversion Rate by Dietary Preference:** Determine conversion rates across different dietary preferences.
- **Daily Conversion Rate:** Analyse how conversion rates vary on a day-to-day basis.

### 2. Retention Analysis
- **Overall Retention Rate:** Calculate the percentage of subscribers retained after the trial period.
- **Retention Rate by Meal Type:** Assess retention rates for different meal types.
- **Retention Rate by Location:** Explore retention rates across different boroughs of London.

### 3. Segmentation Analysis
- **Segment by Subscribing Channel and Age Group:** Group users based on the channel through which they subscribed and their age group.
- **Segment by Retained Subscribers' Dietary Preference and Subscription Date:** Analyse retained subscribers by their dietary preferences and when they subscribed.

### 4. Advanced Insights
- **Dietary Preferences' Impact:** Identify which dietary preferences have the highest conversion and retention rates.
- **Influence of Meal Types and Locations:** Determine if certain meal types or locations influence retention more than others.
- **Trends Over Time:** Identify seasonal trends or other patterns in subscription and retention rates.

## Visualisations

- **Bar Charts:**
  - Conversion rates by dietary preference.
  - Conversion rates by meal type.
  - Marketing channels segmented by age group.
  
- **Line Charts:**
  - Daily conversion rates.
  - Retention rates by location.

## Business Recommendations

Based on the analysis, this section will provide actionable insights and recommendations, such as:

- **Effectiveness of Marketing Channels:** Which channels are driving the most conversions and retention?
- **Dietary Preferences and Meal Types:** Which preferences and meal types are most popular, and how can these insights be used to enhance marketing strategies?
- **Location-Based Strategies:** Recommendations for targeting specific boroughs with tailored marketing messages.
- **Strategies to Improve Conversion and Retention Rates:** Suggested actions based on the analysis findings to optimize marketing efforts.

