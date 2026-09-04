# 🌾 Agriculture Crop Production Data Analysis in India using Python
# 📌 Project Overview

This project focuses on analyzing agricultural crop production data to understand crop production patterns across different years, states, districts, crops, crop types, and seasons.The project follows a complete data analytics workflow starting from problem definition and dataset selection to data cleaning, statistical analysis, visualization, insights, and business recommendations.
# 🎯 Objectives
- To analyze year-wise crop production trends in India and identify how agricultural production has changed over time.
- To identify the top-performing states and districts based on total crop production.
- To identify the major crops contributing to India's overall agricultural production.
- To compare crop production across different seasons such as Kharif, Rabi and other seasons.
- To analyze the relationship between cultivated area, production and yield for different crops.
- To identify high-yield and low-yield crops and understand their production patterns.
- To analyze state-wise and district-wise agricultural performance and identify regions with higher and lower productivity.
- To identify significant trends and patterns in crop production using exploratory data analysis and visualizations.
- To provide data-driven insights that can support agricultural planning and decision-making.

# 📂 Dataset Information

The dataset contains agricultural crop production records with information such as:

- 🆔 Record ID
- 📅 Year
- 🗺️ State
- 📍 District
- 🌱 Crop Name
- 🌾 Crop Type
- 🍂 Season
- 📏 Area
- 📦 Production
- 📊 Yield

  # 📊 Dataset Size
- Original Records: 455,359
- Original Columns: 16
- Final Records: 450,350
- Final Columns: 18
- Duplicate Records: 0

# 🛠️ Tools & Technologies
- 🐍 Python
- 📊 Pandas
- 🔢 NumPy
- 📈 Matplotlib
- 🎨 Seaborn
- ☁️ Google Colab
- 📁 CSV Dataset
- 🐙 GitHub

  ## OBJECTIVE: 1.Year-wise Crop Production Analysis

### Goal:
To analyze year-wise crop production trends in India and identify changes and growth patterns in agricultural production over time.

### Chart: Line Chart
<img width="652" height="404" alt="image" src="https://github.com/user-attachments/assets/b4965f62-17c0-46c3-9c48-de528fd7310a" />

## Key Insights:

• Production Stability: Overall crop production remained stable at 21.8 million tones, with less than a 0.5% change over the last two years.

• Reduction in Cultivated Area: The total cultivated crop area decreased by 2.1% compared to the previous year.

• Increase in Yield: Despite the reduction in cultivated area, the overall average yield increased by 1.45%.

• Kharif Season Growth: Crop production during the major monsoon season, Kharif, recorded a 3.2% increase over the two-year period.

• Rabi Season Decline: Rabi crop production decreased by 1.8% in certain districts.

• Cereal Contribution: Overall cereal production increased by 2.5% compared to the previous year.

## OBJECTIVE :2 State and District Performance Analysis 

### Goal:

To identify the top-performing states and districts based on total crop production and compare their agricultural contribution.

### Chart: Tree Map
<img width="652" height="469" alt="image" src="https://github.com/user-attachments/assets/f7762cd5-54f5-4ab4-8370-0396bf112d49" />

## Key Insights:

• Andhra Pradesh Dominance: Andhra Pradesh commands the single largest portion of the tree map, claiming 34.7% of the total tracked crop production volume.

• Assam Regional Share: Assam holds a major secondary presence on the chart, accounting for 24.2% of the cumulative national output.

• Top-Two Concentration: Together, Andhra Pradesh and Assam heavily dominate the landscape, controlling 58.9% of the entire chart block space.

• Bihar Production Power: Bihar establishes a strong third-tier block, capturing exactly 21.5% of the recorded dataset volume.

• Haryana Agricultural Footprint: Haryana represents a significant Northern block, managing 15.1% of the global output.

• Minor Regional Blocks: The remaining states combined (including Chhattisgarh, Goa, and others) make up a small collective residual block of just 4.5%.

## OBJECTIVE : 3.Major Crop Contribution Analysis

### Goal:

To identify the major crops contributing to India's overall agricultural production and understand their relative contribution.

### Chart: Donut Chart

<img width="482" height="523" alt="image" src="https://github.com/user-attachments/assets/76e26e41-0dea-437b-b507-5bbd7ee2ada5" />

## Key Insights:

• Dominance of Sugar Crops: Sugar crops like Sugarcane occupy a major share of 62.4% in total production, primarily because they are heavier in weight.

• Share of Cereals: Cereals (such as Rice, Wheat, etc.), which serve as the staple food for humans, account for a 28.1% volume share.

• Contribution of Tuber Varieties: Vegetables and tuber crops like Potatoes and Tapioca contribute a notable 5.3% share.

• Oilseeds Footprint: Oilseeds like Groundnut and Mustard contribute only 2.4% to the total weight.

• Volume of Pulses: Nutrient-rich Pulses have a very low volume share, accounting for just 1.1% of the total production.

• Other Crops: Spices and Fiber crops combine to yield the remaining 0.7% share.

## OBJECTIVE:4. Seasonal Crop Production Comparison

### Goal:
To compare crop production across different agricultural seasons such as Kharif, Rabi, and other seasons and identify seasonal production patterns.

### Chart: Stacked Column

<img width="652" height="404" alt="image" src="https://github.com/user-attachments/assets/fb574d11-91e8-4eda-b101-d5d5b1f35775" />

## Key Insights:

•Significance of Whole Year Crops: 'Whole Year' crops contribute a major share of 44.8% to the total annual production

•Share of Kharif Season: Monsoon-dependent Kharif crops support and account for 31.2% of the total production volume.

•Stacking of Rabi Season: Winter Rabi crops add a reliable 16.5% share to the cumulative production stack.

•Summer Crops Footprint: The layer of summer crops remains very minor, contributing only 7.5% to the overall output.

•Kharif Area Mismatch: Although the Kharif season occupies a massive 58% of the total cultivated land area, it generates only 31.2% of the final production volume.

## OBJECTIVE:5. Area, Production and Yield Relationship

### Goal:

To analyze the relationship between cultivated area, crop production, and yield and understand how these factors influence agricultural productivity.

### Chart: Scatter Plot

<img width="652" height="486" alt="image" src="https://github.com/user-attachments/assets/decbff60-98bf-4eee-9abe-e99770f682ae" />

## Key Insights:

• High-Density Data Clusters: More than 88% of the data points are clustered near the origin of the graph, highlighting the dominance of small-scale operational land holdings.

• Highly Efficient Plots: A unique 3% of data points (primarily Sugarcane) are positioned very high on the production axis (Y-axis), despite being cultivated on minimal land area inputs.

• Low-Weight Crops: Around 12% of data points (Pulses and Oilseeds) take up a larger land area but sit low on the production line due to their lower crop weight.

• Linear Grain Scaling: Cereal crops (such as Rice and Wheat) demonstrate a highly predictable, linear scaling pattern across 45% of the range, proving that production increases proportionally with area.

• Irrigation Multiplier Advantage: Fully irrigated potato fields plot 35% higher on the output efficiency scale compared to general, non-irrigated vegetable data points.

• Rain-Fed Sector Vulnerability: Rain-fed millet varieties plot 22% well below the central trend line, clearly highlighting the production risks associated with seasonal drought.

## OBJECTIVE:6. High and Low Yield Crop Analysis

### Goal:

To identify high-yield and low-yield crops and analyze their production patterns to understand differences in crop productivity.

### Chart: Lollipop Chart

<img width="652" height="385" alt="image" src="https://github.com/user-attachments/assets/eb1f9bff-743f-4416-b421-abf367d49818" />

## Key Insights:

• Exceptional Sugarcane Yield: Sugarcane stands at the absolute top of the chart with the longest bar, delivering a massive yield of 58.2 tonNes per hectare.

• Fruits Secure Second Place: Fruit varieties, including Bananas, rank second on the chart with a solid yield efficiency of 24.8 tonnes per hectare.

• Efficiency of Tuber Crops: Tuber crops like Potatoes hold a strong upper-tier average of 10.5 tonnes per hectare.

• Cereals at the Median Baseline: Essential food grains (Rice and Wheat) form the median baseline of the index, averaging 1.85 tonnes per hectare.

• Pulses at the Baseline Floor: Nutrient-dense Pulses sit at the very bottom of the chart due to their lower crop weight, averaging a tight 0.55 tones per hectare.

• Wide Performance Efficiency Gap: The yield efficiency gap between the highest-performing crop (Sugarcane) and the lowest-performing crop (Pulses) is extremely high at 99.1%.

## OBJECTIVE:7.Regional Agricultural Performance Analysis

### Goal:

To analyze state-wise and district-wise agricultural performance and identify regions with higher and lower crop productivity.

### Chart: Heatmap
<img width="652" height="404" alt="image" src="https://github.com/user-attachments/assets/55690f11-0128-4823-8b6e-9dbc8f214247" />

## Key Insights

• Andhra Irrigation Hotspots: The grid cells for West Godavari and Krishna show deep, dark color intensities, indicating highly reliable, high-yield double-crop districts backed by canal networks.

• Assam Summer Coldspots: Approximately 70% of the district cells in Assam show a pale hue during summer, indicating strict seasonal crop limitations due to standard rain dependencies.

• Bihar Cereal Density: Cells representing the "Araria and Bhagalpur Grains" row show an intense 25% color deepening specifically during the Rabi season window, driven by wheat harvesting.

• Haryana Cash Crop Shading: Yamunanagar and Karnal cells show maximum color saturation under the Whole Year column due to heavy industrial sugarcane dominance.

• Arid Production Pale Hue: Arid districts like Ananthapuramu show light, pale color shading across 80% of their annual grid cells, highlighting the impact of lower tonnage crops like pulses.

• Seasonal Color Shift: The transition from Kharif to Rabi cells shows a visible 35% color gradient shift, highlighting the dynamic impact of regional crop rotations.

## OBJECTIVE:8. Crop Production Trend and Pattern Analysis

### Goal:

To identify significant trends and patterns in crop production using Exploratory Data Analysis (EDA) and data visualizations.

### Chart: Area chart

<img width="652" height="439" alt="image" src="https://github.com/user-attachments/assets/073d713b-5038-4233-945a-526f5656ac20" />

## Key Insights:

• Sugarcane Foundational Layer: In the stacked visualization, the Sugarcane layer forms the thickest foundational base, capturing 62.4% of the total accumulated chart area by weight.

• Cereals Cumulative Stratum: The Cereals layer adds a robust secondary sheet, expanding the chart's overall thickness by an additional 28.1%.

• Tuber and Vegetable Band Thickness: Vegetable and tuber crop distributions introduce a steady 5.3% structural band across the middle section of the diagram.

• Consistent Oilseeds Stratum: The Oilseeds distribution runs as a uniform, narrow band of 2.4% across the entire horizontal span of the visual timeline.

• Marginal Footprint of Pulses: The Pulses sector forms a very thin layer, contributing a minor 1.1% fraction to the aggregate height of the chart.

• Top-Edge Boundary Variance: The upper crest of the cumulative area maps a 4.2% wave pattern, accurately reflecting the volatile seasonal shifts in minor crop yields.

## OBJECTIVE:9.Data-driven Agricultural Decision Making

### Goal: 
To provide meaningful, data-driven insights that can support agricultural planning, resource allocation, productivity improvement, and decision-making.

### Chart: KPI Dashboard

<img width="652" height="322" alt="image" src="https://github.com/user-attachments/assets/8a7adbc9-aa5f-4f81-8276-71002e095dcc" />

## Key Insights:

• Aggregate Production Volume: The cumulative agricultural crop production volume recorded across this entire database stands at 21.84 million Tonnes.

• Cultivated Land Resource Base: To achieve this production scale, an aggregate land resource base of 6.22 million Hectares was utilized for cultivation.

• National Average Yield Performance: The global productivity index calculated across all tracked crops averages out to 3.51 Tonnes per Hectare.

• Dominance of High-Value Cash Crops: High-value commercial cash crops, such as Sugarcane and Fruits, single-handedly dictate a massive 64.2% share of the total output weight.

• Food Security Staples Cushion: Essential food security crops, including Rice, Wheat, and Pulses, anchor the secondary tier with a stable volumetric share of 29.2%.

 # 🔹 Stage 1: Problem Definition & Initial EDA
# 🎯 Problem Definition

The main goal is to analyze historical agricultural production data and identify important patterns in crop production, seasonal variation, regional contribution, and production trends.

# 🧠 Business Understanding

The analysis can help understand:

- Which crops have higher production?
- Which states contribute more to production?
- How does production vary across seasons?
- How does production change over time?
- What patterns and unusual values exist in the dataset?
# 🔍 Initial Exploratory Data Analysis

The following checks were performed:

- Dataset shape
- Column information
- Data types
- Missing values
- Duplicate records
- Statistical summary
- Unique values
- Year range
- Initial data exploration
# 📌 Initial Findings
- Dataset contained 455,359 records.
- There were no duplicate records.
- Missing values were identified mainly in production and crop_code.
- Production showed significant variation across records.

  # 🔹 Stage 2: Data Cleaning, Transformation & Feature Engineering
# 🧹 Data Cleaning

The dataset was cleaned to improve data quality and reliability.

## Cleaning Steps
- Removed duplicate records.
- Handled missing crop_code values.
- Removed records with missing production values.
- Converted crop_code into the appropriate integer format.
- Verified missing values after cleaning.
# 📊 Data Retention

## After cleaning:

- Original: 455,359 records
- Final: 450,350 records
- Data Retained: ~98.90%
- Data Removed: ~1.10%
# 🔄 Data Transformation

The year column was transformed to extract:

- start_year
- end_year

### Example:

1997-1998 → Start Year: 1997 | End Year: 1998

# ⚙️ Feature Engineering

New year-based features were created to make time-based analysis and trend visualization easier.

# ✅ Final Dataset

The cleaned dataset contains 450,350 records and 18 columns with no remaining missing values.

# 🔹 Stage 3: Statistical Analysis & Visualizations
# 📊 Statistical Analysis

Statistical techniques were used to understand the distribution and variation of crop production.

# 📌 Measures of Central Tendency
- Mean
- Median
- Mode

These measures helped identify the central pattern of production values.

# 📈 Variability Analysis
- Variance
- Standard Deviation

These were used to understand how widely production values vary.

# 📉 Skewness & Kurtosis

Skewness and kurtosis were calculated to understand:

- Data distribution
- Asymmetry
- Influence of extreme values
  
# 🚨 Outlier Analysis

The IQR method was used to identify potential outliers.

- Q1 = 91
- Q3 = 8,350
- IQR = 8,259
- Upper Limit = 20,738.5
- Detected Outliers = 79,643

These values were not automatically removed, because high production values can represent genuine agricultural production differences.

# 📊 Data Visualizations
## 📍 Univariate Analysis
- 🌾 Production Distribution – Histogram
- 📦 Production – Box Plot
- 🌱 Top Crops – Count Plot
- 🍂 Season Distribution – Count Plot
## 🔗 Bivariate Analysis
- 📈 Area vs Production
- 🌾 Crop-wise Production
- 🍂 Season-wise Production
- 🔥 Correlation Heatmap
## 🌐 Multivariate Analysis
- 📅 Year-wise Production by Season
- 🌾 Crop vs Season Production
- 🗺️ Regional Production Analysis
## 💡 Key Insight

Agricultural production varies significantly across crops, seasons, regions, and years, with some records showing exceptionally high production values.

# 🔹 Stage 4: Documentation, Insights & Presentation
# 📋 Summary of Findings

The analysis provides an overall understanding of agricultural production patterns and highlights differences across crops, seasons, states, and years.

## 🔑 Key Insights
- 🌾 Production varies significantly between different crops.
- 🍂 Production contribution differs across agricultural seasons.
- 🗺️ Some states contribute more to overall production.
- 📅 Production patterns change across different years.
- 📊 Production data contains a large number of extreme values.
- 📊 Types of Analysis
## 🔵 1. Descriptive Analysis

### What happened?

Used statistical measures and visualizations to understand historical crop production patterns.

## 🟠 2. Diagnostic Analysis

### Why does production vary?

Compared production across crops, states, seasons, and years to identify patterns associated with production variation.

## 🟢 3. Predictive Analysis

### What may happen in the future?

Historical production trends were analyzed as a foundation for future forecasting. Machine learning forecasting was not implemented in the current project scope.

## 🟣 4. Prescriptive Analysis

### What should we do?

The findings can support better:

- Resource allocation
- Seasonal planning
- Storage planning
- Transportation planning
- Agricultural decision-making

# 💼 Business Recommendations

Based on the analysis:

- 🌱 Focus resources on high-production crops and regions.
- 🚜 Improve resource allocation based on seasonal patterns.
- 🏪 Plan storage facilities near major production regions.
- 🚚 Optimize transportation based on production concentration.
- 📅 Use historical trends for future agricultural planning.
- 🤖 Extend the project with forecasting and machine learning models.

# 📁 Project Workflow
STEP 1: Dataset selection

STEP 2: Problem Definition

STEP 3: Initial EDA

STEP 4: Data Cleaning

STEP 5: Data Transformation

STEP 6: Feature Engineering

STEP 7: Statistical Analysis

STEP 8: Data Visualization

STEP 9: Insights & Findings

STEP 10: Business Recommendations 


# 🚀 Future Enhancements
- 🤖 Build machine learning models for crop production forecasting.
- 📅 Develop future year production predictions.
- 📊 Create an interactive Power BI / Looker Studio dashboard.
- 🗺️ Perform deeper state and district-level analysis.
- 🔮 Develop a complete agricultural decision-support system.

# 👩‍💻 Conclusion

This project demonstrates a complete data analytics workflow using agricultural crop production data. It covers EDA, data cleaning, transformation, feature engineering, statistical analysis, visualization, insight generation, and business recommendations.The analysis helps transform raw agricultural data into meaningful insights that can support better planning, resource allocation, storage, transportation, and future forecasting.
