
# 📊 Electronic Products Inventory Analysis (Excel)

## 📌 Project Overview

This project presents an exploratory inventory analysis of the **Electronic_Products** dataset using Microsoft Excel.

The dataset contains structured product-level information including:

* Product Name
* Brand
* Category
* Price (USD)
* Stock (Units)
* Availability Status
* Internal ID and EAN

The primary objective of this analysis was to evaluate:

* Inventory capital allocation
* Brand and category concentration
* Stock distribution patterns
* Catalogue activity health


## 📂 Dataset Summary

* Total Inventory Value: **$2.52B**
* Total Products (Distinct): **7,896**
* Total Records: **10,000**
* Categories: **30+**
* Brands: **9,000+**
* Currency: **USD**

Inventory Value was calculated as:

```
Inventory Value = Price × Stock
```

All aggregations were performed using Pivot Tables in Excel.

## Data Cleaning

The dataset was transormed in power query(Excel) where neccessary checks were carried out
* No duplicate records found
* No missing values found
* All columnms were ensured to be in their right data type


## 🔎 Business Questions Explored

1. Which product categories hold the highest inventory capital?
2. Is inventory value concentrated among specific brands?
3. What does product availability reveal about catalogue health?
4. How aligned are stock volume and capital allocation across categories?


## 📊 Visualizations Created

<img width="8192" height="5535" alt="hngproject1" src="https://github.com/user-attachments/assets/70ee0de1-edff-4344-98cf-784b5f7a5d24" />


### 1️⃣ Category by Inventory Value (Top 10)

* Total Inventory Value: **$2.52B**
* Top 10 Categories: **$803.23M (~31.9%)**
* Leading Category: **Clothing & Apparel ($87.48M)**

Clothing & Apparel($87.48M) is the most capital-intensive category, followed by Grooming Tools($83.24M).
Camera & Accessories ($77.19M) ranks lowest within the Top 10.


### 2️⃣ Brand by Inventory Value (Top 10)

* Total Inventory Value: **$2.52B**
* Top 10 Brands Combined: **$16.28M (~0.65%)**
* Leading Brand: **Cuevas and Sons ($1.93M)**
* Lowest in Top 10: **Williamson LLC($1.47M)**

Inventory value is highly fragmented across more than 9,000 brands.


### 3️⃣ Availability by Product Count

Distribution of product availability:

* Out_of_stock: **1,560**
* Discontinued: **1,560**
* In_stock: **1,477**
* Pre_order: **1,527**
* Limited_stock: **1,479**
* Backorder (lowest count): **1,469**

Out_of_stock and Discontinued products represent the largest share of catalogue entries.


### 4️⃣ Stock by Top 5 Category (Units)

Leading categories by stock volume:

1. Clothing & Apparel: **174,236**
2. Health & Wellness: **160,698**
3. Camping & Hiking: **160,376**
4. Team Sports: **159,781**
5. Beauty & Personal Care: **159,161**

Clothing & Apparel leads in both stock volume and inventory value.


## 📈 Key Insights

### 1️⃣ Category Concentration Analysis

Inventory is diversified across 30+ categories.
The Top 10 categories account for ~31.9% of total inventory value.

Clothing & Apparel is both capital-intensive and strategically dominant.

**Implication:**
This category represents the highest financial exposure and requires consistent monitoring.


### 2️⃣ Brand Concentration Analysis

Inventory value is extremely fragmented across 9,000+ brands.
Top 10 brands represent only ~0.65% of total value.

**Implication:**
There is minimal supplier concentration risk. However, the extensive brand base increases operational and procurement complexity.


### 3️⃣ Catalogue Health Insight

Out_of_stock and Discontinued products (1,560 each) exceed In_stock products (1,477).

**Implication:**
A large portion of the catalogue is inactive or unavailable, indicating potential inefficiencies in inventory lifecycle management.


### 4️⃣ Volume–Value Alignment Insight

Clothing & Apparel leads in both:

* Inventory value ($87.48M)
* Stock volume (highest units)

**Implication:**
This category drives both financial exposure and warehouse utilisation, making it strategically critical to overall inventory performance.



## ⚠️ Limitations

* No time dimension (no sales velocity or time intelligence analysis possible)
* No cost or margin data (profitability not measurable)
* Availability status does not indicate duration of stock state
* No supplier performance metrics available


## 🚀 Strategic Recommendations

### 1️⃣ Reduce Catalogue Inactivity

* Clean up obsolete SKUs
* Remove discontinued listings from active reporting
* Strengthen lifecycle governance

This will improve catalogue efficiency and reporting clarity.


### 2️⃣ Review Category Capital Allocation

Given the dominance of Clothing & Apparel:

* Conduct deeper demand and turnover analysis
* Validate capital exposure alignment with revenue performance
* Monitor overexposure risk


### 3️⃣ Evaluate Brand Rationalization

With over 9,000 brands:

* Consolidate low-impact brands
* Reduce supplier management complexity
* Focus procurement efforts on high-value partners


### 4️⃣ Monitor Inventory Concentration Risk

Even with moderate category diversification:

* Continuously monitor Top 10 categories
* Identify early concentration shifts
* Improve capital allocation efficiency


## 🛠 Tools Used

* Microsoft Excel

  * Pivot Tables
  * Calculated Columns
  * Conditional Formatting
  * Custom Number Formatting
  * Bar,line and Column Charts


## 📌 Conclusion

The analysis reveals a diversified but operationally complex inventory structure.

Clothing & Apparel dominates both financial exposure and stock volume, while brand fragmentation reduces supplier risk but increases management complexity.

A significant share of inactive products highlights the need for stronger inventory lifecycle controls and strategic SKU optimization.


