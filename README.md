# Rockbuster_Stealth

# Project Overview

A demo project using PostgreSQL and pgAdmin to clean, document, query, and analyze data from a fictitious movie rental company, Rockbuster Stealth LLC.

## Context

Rockbuster Stealth LLC, a fictional movie rental company with a global presence, is adapting to the competitive landscape posed by streaming services like Netflix and Amazon Prime. To stay relevant, the management is strategically transitioning from physical stores to an online video rental platform, leveraging their existing movie licenses.

As part of this initiative, I, a data analyst hired by Rockbuster Stealth's business intelligence (BI) department, am tasked with providing data-driven insights to inform the launch strategy for the new online service.

## Objectives

The Rockbuster Stealth Management board has posed critical business questions, seeking data-driven answers for their 2020 company strategy. The key questions include:

- Identification of movies contributing the most/least to revenue gain.
- Determination of the average rental duration for all videos.
- Analysis of the countries where Rockbuster customers are based.
- Identification of customer segments with a high lifetime value.
- Evaluation of sales figures variation across geographic regions.

## Data

The dataset for this project was supplied by Rockbuster and encompasses information about the company's film inventory, customers, payments, and more. To facilitate the analysis, the data was loaded into a PostgreSQL database.

The database comprises the following tables:

## Fact Tables

- Payment
- Rental

## Dimension Tables

- Store
- Film_Actor
- Inventory
- Film_Category
- Customer
- Staff
- Actor
- Film
- Category
- Address
- Language
- City
- Country

This structured database forms the foundation for answering the posed business questions and guiding Rockbuster Stealth's strategic decisions for the online video rental platform launch.


## Tools

_Language_: PostgreSQL

_Software_: pgAdmin, DbVisualizer, Excel, Tableau

## Data Visualization

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

Deck created in [Tableau](https://public.tableau.com/app/profile/greta.lawani/viz/3_10RockbusterStealthLLC/RockbusterCompetitivenessAnalysis)
