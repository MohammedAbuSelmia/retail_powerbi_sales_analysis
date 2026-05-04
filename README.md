#  Retail Sales Performance Dashboard

## Project Overview
This project is a full-scale Power BI analytics solution built for a company that sells and supplies **office supplies, furniture, and technology** across all 50 U.S. states. The dataset was rich with potential — and as a data analyst, it immediately raised a set of critical business questions that shaped the entire project:

- What are the best-selling categories in each state?
- Which products perform best by customer segment?
- What is the annual profit margin, and how is it trending?
- What is the year-over-year growth rate?
- Who are our top and bottom performing customers?

>  **Fully Dynamic** — Every visual, metric, and filter updates instantly based on selections across State, Segment, Category, and Year — giving decision-makers complete control in real time.

---

##  Tools and Technologies
`SQL` · `Power BI` · `DAX` · `Data Modeling`

---

##  Step 1 — Data Import amd Column Selection
Imported the raw dataset from **SQL into Power BI** and carefully identified the columns most relevant to the project's analytical goals — keeping the model lean and focused.

---

##  Step 2 — Building the Calendar Table
One of the most critical steps in any time-based analysis: I built a dedicated **CALENDAR table** containing all the time intelligence fields needed — year, quarter, month, day, and more. This table became the backbone of every date-related measure in the project.

---

##  Step 3 — Data Modeling
Linked the CALENDAR table to the main fact table, establishing the relationships needed to perform accurate time-based calculations and ensure every measure behaves correctly across all visuals.

---

##  Step 4 — Measures Table
To keep the project clean and scalable, I created a **dedicated measures table** housing all DAX calculations in one organized place — separating logic from data and making the model easy to maintain and expand.

---

##  Page 1 — Executive Sales Overview
The first page delivers a comprehensive, high-level view of the company's sales performance — everything a decision-maker needs at a glance:

- Total orders and shipped orders
- Total sales and previous year sales (YoY comparison)
- Top 5 and bottom 5 performing sales categories
- Top 10 states by annual sales
- Top and bottom performing customers
- And several additional insights packed into a clean, interactive layout

---

##  Page 2 — Regional and Customer Deep Dive
The second page zooms in on geography and customer behavior — giving regional managers the detail they need:

- Number of customers per state
- Full customer-level breakdown by region
- Category sales performance across each region
- Identification of the top-selling categories in each area

This page was designed with one goal: make every region's performance fully transparent and easy to act on.

---

##  Impact
This project takes raw, unstructured transactional data and transforms it into a **highly interactive, well-organized decision-making resource** — answering real business questions with real data, and empowering stakeholders to make informed, confident decisions.

---
