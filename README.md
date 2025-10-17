# FreshCart Marketing Analytics Optimization
<iframe title="FRESH CART PROJECT" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMzcyNDE2MDYtODk0MS00MmI4LTljMWMtNjI2Njk5Mzc0NTNmIiwidCI6IjM0YTkxMjU3LWU1NzctNDliNi05ZmQ3LTJmNjNmNzMzMDRhYyJ9" frameborder="0" allowFullScreen="true"></iframe>

## Project Overview
This project focuses on analyzing and optimizing digital advertising spend for FreshCart, a leading e-commerce platform in the online grocery sector. In a highly competitive market, the company faced two primary challenges: inefficient ad spending and difficulty identifying the most effective advertising channels.

The goal was to leverage data to create a data-driven strategy for better budget allocation, ultimately increasing the return on investment (ROI) of marketing campaigns.

## Problem Statement
FreshCart was experiencing inefficient ad spend, with some campaigns costing more than they returned in revenue. With a wide array of advertising platforms (Google Ads, Facebook, Instagram, etc.), the company needed a clear way to determine which channels offered the best ROI and how to better allocate its marketing budget.

## Project Aim
The aim of this project was to analyze FreshCart's past advertising data and develop a strategy to optimize digital ad spending. The specific objectives were:

Evaluate the effectiveness of current advertising campaigns across platforms.

Identify top-performing channels for advertising.

Assess demography engagement and conversion rates.

Recommend strategies for better budget allocation.

## Data Source
The analysis was performed on an Excel file containing  ad campaign data provided by FreshCart's Marketing team.

## Data Attributes:

CampaignID: Unique identifier for each campaign.

Platform: Advertising platform (e.g., Google Ads, Facebook, Instagram, Twitter).

AdDuration: Ad duration in weeks.

Cost: Amount spent on the ad.

Impressions: Number of times the ad was shown.

Clicks: Number of times the ad was clicked.

Conversions: Number of actions taken as a result of the ad.

ConversionValue: The total sales value generated from the conversions.

CPC (Cost per Click): How much was spent for each click.

## Technical Stack
ETL & Analysis: Power BI

Data Source: Microsoft Excel

## Project Scope
Data Integration: Connected the Excel data source to Power BI.

Data Cleaning & Transformation: Used Power Query to clean and transform the data, handling any inconsistencies and ensuring it was in the correct format for analysis.

Data Modeling: Created a simple data model in Power BI.

Analysis & Visualization: Defined key performance indicators (KPIs) and created interactive visualizations to tell the story of ad performance.

Reporting & Recommendations: Developed a comprehensive report with clear findings and actionable recommendations for FreshCart.

## Key Performance Indicators (KPIs)
The following KPIs were calculated using Power BI's DAX (Data Analysis Expressions) to measure campaign effectiveness:

Total Cost: $28,000

Total Conversion Value: $97,520

Return on Investment (ROI): 3.42

Cost per Conversion (CPCCONV): $12.89

Average Cost per Click (CPC): $1.16

## Power BI Dashboard Structure
The final Power BI report is organized into interactive pages, designed to provide a cohesive narrative for different stakeholders.

1. Executive Summary
This page provides a high-level overview for a quick understanding of overall performance.

KPI Cards: Prominent cards displaying the key metrics, showing a high ROI of 3.42, indicating that for every $1 spent, FreshCart earned $3.42 in revenue.

Ad Funnel Performance: A funnel chart that visually exposes a critical issue: a high volume of 23 million impressions with a near-zero conversion rate. This indicates a significant drop-off from exposure to customer action, highlighting a need for immediate optimization of ad creatives and targeting.

ROI by Year, Quarter, Month and Day: A line chart tracking ROI fluctuations over time, showing performance peaks and valleys. This suggests ad performance is not consistent and may be influenced by seasonality or specific campaigns.

2. Channel Performance
This page allows for a detailed analysis of individual platforms and campaigns.

"Spend vs Revenue by Platform": A stacked bar chart visually compares the cost and conversion value for each platform. The chart clearly shows that while platforms like Facebook and Google Ads have significant ad spend, YouTube and Twitter are highly efficient, generating a large return for a relatively lower cost.

"ROI by Platform": A bar chart that directly ranks platforms by their ROI. This visual confirms that YouTube is the top-performing platform, with an ROI significantly higher than Twitter, Facebook, Instagram, and Google Ads.

Campaign Performance Table: A table with conditional formatting applied to the ROI column (not pictured) to instantly identify top- and bottom-performing campaigns. The visible data for YouTube campaigns (CID8, CID9, CID3) shows a strong performance with high conversions, while Twitter campaigns (CID12, CID6, CID16) are less consistent, highlighting where budget adjustments could be made.

## Conclusion and Recommendations
The analysis provides a clear roadmap for FreshCart to optimize its ad spend.

Reallocate Budget to Top-Performing Channels: The data strongly suggests shifting a larger portion of the ad budget towards YouTube, which offers the highest ROI.

Optimize Low-Performing Campaigns: Campaigns on platforms like Facebook and Google Ads should be reviewed. While these platforms have high ad spend, their lower ROI suggests they are less efficient at generating revenue. Further analysis should be conducted to determine if targeting, ad content, or bidding strategies are the root cause.

Improve Conversion Funnel Efficiency: The significant drop-off between impressions and clicks/conversions is a major area for improvement. Efforts should be focused on creating more engaging ad content and refining audience targeting to increase click-through and conversion rates.

This project empowers FreshCart's marketing team to move from reactive decision-making to a proactive, data-driven strategy for sustain
