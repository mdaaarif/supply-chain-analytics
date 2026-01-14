Inventory & Logistics Analytics (SQL-Focused)
Overview

This module applies advanced SQL analytics to evaluate inventory flow, supplier reliability, and delivery efficiency within a multi-product supply chain environment. The work focuses on transforming transactional data into operational insights that support planning, fulfillment optimization, and risk mitigation.

Technology Stack

MySQL – Primary platform for relational analysis and complex querying

Python – Data preparation, normalization, and feature engineering

Power BI – Visualization and exploratory reporting layer

Analytical Objectives

Classify products by movement velocity using historical demand

Measure delivery delays and reliability across suppliers and regions

Monitor inventory health through turnover and depletion indicators

Evaluate supplier and product-level fulfillment effectiveness

Provide data-backed signals to guide replenishment decisions

Data Model

Data Origin: Public Kaggle dataset adapted for analytical use

Schema Design: Converted into a normalized relational structure

Core Tables:

orders

products

customers

suppliers

inventory

shipments

SQL Techniques Applied

Analytical functions for ranking, sequencing, and rolling metrics

Multi-layer CTE pipelines for modular query design

Recursive queries for hierarchy and time-series expansion

Subqueries for conditional and context-aware calculations

Temporal functions to quantify shipping duration and delays

Analytical Use Cases

Supplier punctuality scoring based on shipment completion timelines

Detection of underperforming SKUs by category over recent demand windows

Warehouse-level inventory turnover tracking on a monthly basis

Early warning identification of potential stock depletion

Rolling-period sales and return trend analysis

Behavioral segmentation of high-risk customers (returns/cancellations)

Rule-based replenishment logic driven by demand and inventory signals

Outcome

The SQL analysis layer enables operational teams to identify inefficiencies, anticipate supply risks, and improve inventory planning decisions using structured, query-driven insights.
