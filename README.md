# Delhivery_Feature_Engineering

**About Delhivery:**
Delhivery is India's largest and fastest-growing fully integrated logistics player as of Fiscal 2021. The company is committed to building an operating system for commerce, combining world-class infrastructure, high-quality logistics operations, and advanced technology capabilities. Their data team plays a crucial role in maintaining their competitive edge by leveraging data to enhance the quality, efficiency, and profitability of their operations.

**Project Objectives:**
- The goal of this project is to process and extract meaningful insights from Delhivery’s data to aid the data science team in building effective forecasting models. The main tasks involve:

--Cleaning, sanitizing, and manipulating raw data to extract valuable features.
--Understanding raw data to support predictive modeling efforts.

## Project Files
- [Delhivery_case_Study.pdf](https://github.com/titojorj/Delhivery_Feature_Engineering/blob/main/Delhivery_case_Study.pdf)
- [Delhivery_case_Study.ipynb](https://github.com/titojorj/Delhivery_Feature_Engineering/blob/main/Delhivery_case_Study.ipynb)

**Dataset Overview:**
- The dataset used for this project can be accessed [here](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/551/original/delhivery_data.csv?1642751181).

**Key Data Columns:**
- **trip_creation_time**: Timestamp of when a trip was created.
- **route_type**: Type of transportation (e.g., FTL or Carting).
- **source_center/destination_center**: IDs representing trip origins and destinations.
- **actual_time and osrm_time**: Actual vs. calculated delivery times.
- **segment_actual_time**: Time taken for a delivery segment.
- **segment_osrm_distance**: Distance covered by a delivery segment.

**Concepts Applied:**
- **Feature Creation**: Constructing new features to enhance data representation.
- **Feature Relationships**: Analyzing inter-feature connections.
- **Normalization/Standardization**: Scaling data for uniformity.
- **Handling Categorical Values**: Processing non-numeric data effectively.
- **Outlier Treatment**: Identifying and managing outliers to ensure data quality.
- **Missing Values**: Addressing data gaps for reliable analysis.
