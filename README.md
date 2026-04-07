**Forbes Billionaires Data Analysis (Power BI)**

**Dashboard Preview**

<p align="center">
  <img src="Forbes Dashboard.png" alt="Forbes Billionaire Dashboard" width="1000"/>
</p>

*Overview*

This project focuses on transforming and analyzing a raw Forbes billionaires dataset using **Power BI (Power Query + DAX)**.

*The objective was to:*

* Clean and standardize messy real-world data
* Build a structured analytical model
* Create an interactive dashboard for insights on wealth distribution, demographics, and global trends


**Data Cleaning & Transformation**

All transformations were performed in Power Query Editor following best practices.

**Name Standardization**

* Removed first_name, last_name (80%+ nulls)
* Retained full_name → Person Name
* Applied Trim, Clean, and encoding fixes

**Location Standardization**

* Renamed:

  * Citizenship Country
  * Residence Country
  * Residence City
* Replaced nulls with "Unknown"

**Industry Cleaning**

* Removed columns with 95%+ nulls
* Cleaned special characters
* Standardized industry values
  
**Gender Handling**

* Standardized values (Male/Female)
* Replaced nulls with "Unknown"

**Wealth Type Creation**

* Derived column:

  Self-Made<br>
  Inherited<br>
  Unknown<br>

**Net Worth Transformation**

* Removed "B" suffix
* Converted to numeric net_worth
* Enabled sorting and aggregations

**Ranking Logic (Advanced)**

* Grouped by **Year + Month**
* Sorted by Net Worth (Descending)
* Generated rank within each partition

**Null Handling Strategy**

* Replaced categorical nulls with "Unknown"
* Removed rows with missing critical values

**Data Type Enforcement**

* Ensured correct numeric and text types
* Enabled accurate calculations and visuals

**Key Visualizations**

**Top 10 Billionaires** - Ranked by Net Worth<br>

**Billionaires by Gender** - Donut chart showing Male / Female / Unknown split<br>

**Age Distribution** - Shows concentration of billionaires by age<br>

**Wealth Type Analysis** - Self-made vs Inherited comparison<br>

**Top Countries Analysis**
* Top 5 Countries by billionaire count
* Top 20 Countries breakdown

**City Analysis** - Distribution of billionaires across major cities

*Filters (Slicers)*

* Year
* Country
* Gender

**Key Learnings**

**Data Engineering**

* Handling high null percentage columns
* Data standardization and cleaning techniques
* Encoding and text normalization

**Power Query (ETL)**

* Column transformations
* Grouping and ranking logic
* Creating derived columns

**Data Modeling**

* Understanding when to simplify vs normalize
* Preparing data for analytical consumption

**DAX & Analytics**

* Preparing dataset for advanced calculations
* Designing KPIs and aggregations

**Dashboard Design**

* Layout structuring (top-down storytelling)
* Choosing correct visuals for business questions
* Maintaining clean UI and spacing

**UX Best Practices**

* Slicer interactions
* Avoiding clutter
* Clear visual hierarchy

**Business Insights Enabled**

* Global wealth concentration trends
* Self-made vs inherited wealth distribution
* Industry dominance among billionaires
* Geographic hotspots (countries & cities)
* Age patterns among billionaires

**Tools Used**

* Power BI Desktop
* Power Query Editor
* DAX

**Project Highlights**

* Real-world messy data handling
* Strong transformation logic
* Interactive dashboard design
* Business-focused insights

