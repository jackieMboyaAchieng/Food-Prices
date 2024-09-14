# Food-Prices
This repo contains food price analysis for Kenya from 2006 to 2024

# Analysis of Food Prices in Kenya Using WFP Data

## Introduction

### Background

Food prices are a crucial indicator of economic stability and food security in Kenya. The World Food Programme (WFP) monitors these prices to understand market dynamics and guide policy decisions. Various factors, including weather patterns, political stability, and economic conditions, can significantly impact food prices. Fluctuations in these factors can alter market trends, making it essential to analyze food price data accurately. Effective forecasting of these trends enables timely interventions to address potential issues, ensuring that food security measures adapt to changing conditions.

## Research Problem

Despite extensive availability of food price data, there is a gap in comprehensive analysis. Most current analyses either focus on exploratory data analytics, providing insights into historical trends and patterns, or on predictive modeling, forecasting future trends based on past data. There is a lack of integrated approaches that combine both exploratory and predictive methods. This project aims to address this gap by using advanced machine learning techniques to merge these analytical approaches. The goal is to extract actionable insights from the [World Food Program food prices database](https://data.humdata.org/dataset/?dataseries_name=WFP+-+Food+Prices) and enhance the accuracy of predictions, offering more robust recommendations for policymakers and stakeholders to improve food security and economic stability.

### Objectives

- Identify and forecast seasonal patterns in commodity prices.
- Analyze historical food price data in Kenya to identify trends and patterns.
- Develop predictive models to accurately forecast future food prices in Kenya.

### Hypotheses

- Most cereals and tubers are the staple foods for Kenyan citizens.
- Prices vary significantly across different commodity categories.
- Seasonal variations significantly impact food prices in Kenya.

## Methodology, Results, and Discussion

### Data Description

The dataset, provided by the World Food Programme (WFP), includes historical food prices in Kenya from the January 15, 2006 to June 15, 2024. It encompasses multiple regions and various food items, with columns such as `date`, `admin1`, `admin2`, `market`, `latitude`, `longitude`, `category`, `commodity`, `unit`, `priceflag`, `pricetype`, `currency`, `price`, and `usdprice`. The data, collected through market surveys, spans several years, offering a comprehensive view of food price trends.

### Data Collection

The WFP dataset includes:

1. **Market Surveys:**
   - Periodic surveys across various Kenyan markets to capture representative prices of different food commodities.

2. **Geographic Coverage:**
   - Data from both urban and rural areas, including detailed geographic information such as `admin1`, `admin2`, market names, and coordinates.

3. **Commodity Coverage:**
   - Various food items categorized by `category` and `commodity`, allowing detailed price trend analysis.

4. **Temporal Coverage:**
   - Longitudinal data with timestamps (`date`) to facilitate time series analysis and identify seasonal patterns.

5. **Price Types:**
   - Prices recorded in various units (e.g., kg, liter) and `pricetype` categories (e.g., retail, wholesale), with `priceflag` indicators for specific conditions or anomalies.

6. **Currency:**
   - Prices in local currency and USD for standardized comparison.

The dataset's detailed information on market conditions, geographic locations, commodity types, and temporal patterns supports thorough analysis and predictive modeling.

#### Variables Table

| Variable   | Description                                    |
|------------|------------------------------------------------|
| date       | Date of price recording                        |
| admin1     | First-level administrative division in Kenya   |
| admin2     | Second-level administrative division in Kenya  |
| market     | Market name                                    |
| latitude   | Latitude of the market location                |
| longitude  | Longitude of the market location               |
| category   | Category of the food item                      |
| commodity  | Type of food item                              |
| unit       | Measurement unit (e.g., kg, liter)             |
| priceflag  | Indicator of price flag                        |
| pricetype  | Type of price (e.g., retail, wholesale)        |
| currency   | Currency of the price                          |
| price      | Price of the commodity in local currency       |
| usdprice   | Price of the commodity in USD                  |

For more information on the WFP Food Prices dataset, visit the [Humanitarian Data Exchange](https://data.humdata.org/dataset/wfp-food-prices-for-kenya).
