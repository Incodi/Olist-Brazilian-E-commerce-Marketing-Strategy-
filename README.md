# Brazilian E-Commerce Operations Dashboard

A Power BI portfolio project analyzing the Brazilian Olist e-commerce dataset to explore order volume, delivery performance, and customer experience.

## Project Status

Work in progress. The data model and initial analysis are complete, and I am currently studying dashboard design and refining the dashboard layout, visual design, and analysis. Additional metrics and visualizations may be added as the project develops.

All main DAX formulas are uploaded for me. DAX functions made specifically for testing relationships were used a lot but aren't in the file.

## Overview

This project uses the public Olist Brazilian E-Commerce dataset, which contains approximately 100,000 orders from 2016 to 2018 across multiple related tables. The project focuses on understanding operational performance rather than simply displaying sales totals.

The dashboard is being designed around questions such as how delivery performance changes over time, which locations experience more delivery delays, how long orders take to reach customers, and whether delivery performance is associated with customer review scores.

This information for a dashboard is important to an potential audience like a marketing manager. 

## Data

The project uses the Olist Brazilian E-Commerce Public Dataset from Kaggle. The dataset contains information about orders, order items, payments, reviews, customers, products, sellers, and geographic information.

The data covers orders placed between 2016 and 2018 and contains approximately 100,000 orders.

## Data Model

The Power BI model combines the Olist tables into a relational model with orders serving as the central fact table for operational analysis. A separate Date table is used for time-based analysis, allowing order activity and delivery performance to be analyzed by month, quarter, and year.

## Analysis

The current analysis includes total orders, revenue, freight costs, items sold, average order value, delivery time, estimated delivery time, delivery delays, delivered orders, late orders, on-time orders, on-time delivery percentage, late delivery percentage, and average customer review score.

The dashboard is made to provide both a high-level overview of operations and a way to investigate differences in delivery performance across time and customer locations.

## Tools

Power BI Desktop is used for data modeling, transformation, DAX calculations, and dashboard development.

The project uses DAX for calculated columns and measures and follows Microsoft's guidance for designing effective Power BI reports.

## Current Progress

The data has been loaded and modeled in Power BI, relationships have been established, a Date table has been created, and the initial operational measures and dashboard visuals have been developed.

The dashboard is currently being refined. Planned work includes improving the visual layout, formatting the report for easier interpretation, validating the delivery-performance calculations, and potentially adding additional analysis.

## Source

Olist Brazilian E-Commerce Public Dataset:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Microsoft Power BI report design guidance:
https://learn.microsoft.com/en-us/training/paths/power-bi-effective/

https://learn.microsoft.com/en-us/training/paths/model-data-power-bi/

## Project Goal

The goal of this project is to show practical experience with data modeling, DAX, Power BI reporting, and operational data analysis using a real world multi-table marketing dataset.

As a major goal for integrity, I have used no tutorials and references related to the data, and mainly used Microsoft Learn's official resources for help with PowerBI.
