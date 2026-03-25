# Analysis-Thailand-household-income

📊 Thai Household Income & Inequality Analysis (2023)

📌 Executive Summary
This project analyzes the 2023 National Statistical Office (NSO) dataset to map economic disparity across 77 Thai provinces. By processing 10 socio-economic classes, the analysis identifies critical "dual economies" where high average wealth masks deep internal inequality.

🎯 Key Insights & Policy Impact
The 3.2x Gap: Identified a stark income disparity between professional managers (avg. ฿48,293/mo) and agricultural laborers (avg. ฿14,983/mo).

The "Outlier" Economy: Discovered that Chanthaburi leads the nation in income not through industry, but through high-value agricultural land ownership—averaging over ฿181,000 for specific segments.

Vulnerability Mapping: Proved that while wage policies help urban laborers, 47–55% of farmer income comes from profit, meaning they require market access rather than just minimum wage hikes.

🛠️ Advanced Visualizations
This project moves beyond static charts to interactive Plotly dashboards:

Geospatial Wealth Map: A regional benchmarking tool to visualize "Income Hubs" vs. "Underfunded Zones."

Dumbbell Charts: Visualizing intra-group inequality to show which job sectors have the widest internal pay gaps.

4-Quadrant Policy Matrix: Categorizing provinces into four priorities:

High Income / High Inequality (Needs redistribution)

Low Income / Low Inequality (Needs infrastructure)

🧬 Technical Pipeline
Data Cleaning: Handled Thai-encoded CSVs, mapped 77 provinces to 7 regions, and handled "Unmatched" geographical data points.

Aggregation: Engineered weighted means to accurately reflect "National Averages" versus "Province-specific Medians."

Custom Theming: Built a consistent "Thai UI" template using custom fonts (Garuda/Tahoma) and color scales for accessibility.

💻 Tech Stack
Language: Python 3.x

Data Science: Pandas, NumPy

Visualization: Plotly Express, Plotly Graph Objects (Interactive)
