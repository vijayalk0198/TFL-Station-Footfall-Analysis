# Analysis of Station Footfall Trends Across the TFL Network (2019–2024)
### Introduction 
This project analyzes daily footfall data from TFL train stations across London between 2019 and 2024. Using metrics such as average daily usage, seasonality dependency, and footfall volatility, stations have been segmented into functional groups—including Low Footfall Stops, Residential Connectors, and Busy Interchanges. The core focus is on understanding patterns of station usage and building a data-driven framework for station classification based on zone and usage behavior.

### Dataset Overview
1. TFL Station Footfall Data (2019–2024)
Daily footfall data was sourced from the official [Transport for London website] (https://crowding.data.tfl.gov.uk/), where each year’s data is published as a separate file. The dataset includes key columns such as date, station name, entry tap count, and exit tap count. This rich time series data provides valuable insights into how station usage fluctuates over time across the TFL network.

2. TFL Station Metadata
Complementary metadata about each station was collected from a [Kaggle dataset] (https://www.kaggle.com/datasets/olisao/transport-for-london-tfl-entry-and-exit-dataset/data), which includes details like the station’s zone, lines served, network classification, and geographical coordinates (latitude and longitude). This data enabled spatial segmentation and contextual understanding of station behavior within the broader network.

### Tools & Concepts
#### Tools Used:
- Microsoft Excel – Used for initial data preparation, including combining yearly footfall files into a single consolidated dataset.
- Power BI – Used to develop interactive dashboards and implement a scoring system using advanced DAX queries.

#### Key Concepts Applied:
- Comparative Analysis – Benchmarking stations across usage metrics to identify relative performance.
- Z-Score Calculation – Standardizing metrics to support meaningful comparison and segmentation.
- Time Series Trend Analysis – Examining seasonal patterns and long-term usage shifts across years.
- Footfall Volatility & Seasonality Metrics – Measuring variability and dependency on seasonal factors to classify station behavior.

