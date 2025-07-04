
## Masterpieces in Data: SQL Insights from Famous Paintings & Museums
<img width="334" alt="image" src="https://github.com/user-attachments/assets/121ffa3a-815d-46d2-8603-67dbdd0aeb1c" />


##  Project Overview
This SQL project explores a dataset containing information about famous paintings, museums, artists, canvas sizes, and more. Using complex SQL queries, I uncovered insights related to museum operations, pricing strategies, artist popularity, and geographical trends.

##  Business Questions Answered
- **Unassigned Paintings**: Identify all paintings not currently displayed in any museum.
- **Empty Museums**: Are there museums without any paintings?
- **Price Discrepancies**: How many paintings are priced above their regular value?
- **Undervalued Art**: Which paintings are priced below 50% of their regular price?
- **Most Expensive Canvas Size**: Which canvas label has the highest average price?
- **Data Cleaning**: Remove duplicate records across key tables (work, product_size, subject, image_link).
- **Invalid Location Data**: Find museums with incorrect or missing city values.
- **Invalid Operating Hours**: Identify and remove incorrect entries in museum_hours.
- **Top Subjects**: What are the 10 most common painting subjects?
- **Open on Sunday & Monday**: Find museums open on both days.
- **Always Open Museums**: How many museums operate every day of the week?
- **Top Museums**: Which 5 museums house the most paintings?
- **Top Artists**: Who are the 5 most prolific artists by painting count?
- **Least Popular Canvas Sizes**: Identify 3 canvas labels with the fewest paintings.
- **Longest Open Hours**: Which museum stays open the longest on a single day?
- **Style Concentration**: Which museum holds the most works in the most popular style?
- **Global Artist Reach**: Which artists have paintings in museums across multiple countries?
- **Museum Density**: Which cities and countries have the most museums?
- **Price Extremes**: Where are the most and least expensive paintings displayed?
- **5th Most Paintings by Country**: Which country ranks fifth by painting count?
- **Style Popularity Range**: Identify the 3 most and 3 least popular painting styles.
- **Portraits Outside USA**: Which artist created the most portrait paintings outside the USA?

## Key Outcomes
- Revealed undervalued paintings to support pricing reevaluation
- Identified underutilised museums for potential exhibit placement
- Cleaned and validated key data tables for reliable reporting
- Ranked top artists and museums for promotional or strategic focus
- Delivered geographic insights on museum and artwork distribution
  
##  Tools & Technologies
- **SQL**: Joins, CTEs, Window Functions, Aggregations
- **Python**: Used for data loading via `pandas` and `SQLAlchemy`
- **Database**: PostgreSQL

<img width="625" alt="image" src="https://github.com/user-attachments/assets/ccd95d61-3c6d-4469-a97c-1033d2f4f753" />

## Analysis & Findings

### A. Inventory and Display Analysis
<img width="691" alt="image" src="https://github.com/user-attachments/assets/c117023a-b83b-455e-84e2-b8c0d391b234" />
Paintings not displayed in any museum are **10,223**

<img width="413" alt="image" src="https://github.com/user-attachments/assets/7c7bdf6a-a1fd-4802-a054-d3259cef3a40" />
3 Least Popular Canvas Sizes are **11**

## B. Pricing Insights
<img width="308" alt="image" src="https://github.com/user-attachments/assets/154e4fc3-190e-4790-864a-4f2f7b280412" />
Most expensive canvas size: **48" x 96" (122 cm x 244 cm)** with sale price **1,115**

## C. Data Quality Checks
<img width="536" alt="image" src="https://github.com/user-attachments/assets/fae7c0a0-9ee7-492a-abb2-98fd58144572" />
Duplicates removed from `work`, `product_size`, `subject`, `image_link`

## D. Museum Operations
<img width="744" alt="image" src="https://github.com/user-attachments/assets/2cdba404-87ce-4309-8dd9-1e73fdcff564" />
The longest daily opening Museum is **Musée du Louvre** on **Friday** for 12 hours 45 minutes

## E. Artist & Museum Popularity
<img width="701" alt="image" src="https://github.com/user-attachments/assets/351674db-1281-4cea-970a-eac3a5a61f7c" />
Top 5 Museums by Number of Paintings:
**The Metropolitan Museum of Art** – 939, **Rijksmuseum** – 452, **National Gallery** – 423, **National Gallery of Art** – 375, **The Barnes Foundation** – 350

## F. Painting Subjects & Styles
<img width="531" alt="image" src="https://github.com/user-attachments/assets/c012e610-3a1c-49d0-b529-aede8827ec87" />
 **3 Most Popular Styles**:
Impressionism, Post-Impressionism, Realism

**3 Least Popular Styles**:
Avant-Garde, Art Nouveau, Japanese Art



