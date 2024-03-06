# AirBnb-Analytics-Engineering

**Project Title:** Analytics Engineering with Airbnb: Building a Data Analytics Pipeline Using Snowflake, dbt, and Preset for Visualization

**Project Overview:**
In this project, we aim to simulate the role of an Analytics Engineer working with Airbnb data. The primary focus is on constructing a robust data analytics pipeline that involves loading, cleansing, exposing data, implementing tests, automations, and documentation. We'll utilize Snowflake as the data warehouse, dbt (data build tool) for modeling, and Preset for visualization purposes. The dataset used for analysis is sourced from Inside Airbnb: Berlin.

**Requirements:**

1. **Modelling Changes Traceability:** Ensure that any changes made to the data modeling process are easy to follow and revert. This involves maintaining clear documentation and version control.

2. **Explicit Dependencies Between Models:** Establish explicit dependencies between different data models to ensure accurate and efficient execution of the pipeline.

3. **Exploring Dependencies Between Models:** Conduct thorough exploration of dependencies between various data models to understand the flow of data and its implications on downstream processes.

4. **Data Quality Tests:** Implement data quality tests to validate the integrity, accuracy, and consistency of the data throughout the pipeline. These tests should cover aspects such as completeness, validity, and consistency.

5. **Error Reporting:** Develop mechanisms for error reporting and handling within the pipeline to promptly identify and rectify any issues that arise during data processing.

6. **Incremental Load of Fact Tables:** Implement incremental loading techniques for fact tables to optimize performance and minimize processing time when dealing with large datasets.

7. **Tracking History of Dimension Tables:** Establish a mechanism to track the historical changes in dimension tables, allowing for analysis of data evolution over time.

8. **Easy-to-Access Documentation:** Maintain comprehensive documentation covering all aspects of the data analytics pipeline, including data sources, transformations, tests, and visualization processes. This documentation should be easily accessible to all stakeholders involved in the project.

**Data Source:**
The data for this project is sourced from Inside Airbnb: Berlin, providing valuable insights into the Airbnb listings, hosts, reviews, and other relevant information specific to the Berlin region.

By adhering to these requirements and leveraging the capabilities of Snowflake, dbt, and Preset, we aim to construct a robust and efficient data analytics pipeline that enables insightful analysis and visualization of Airbnb data.

**Dataset Details**

The dataset utilized for this project is sourced from "Inside Airbnb: Berlin," a comprehensive collection of data related to Airbnb listings, hosts, reviews, and other pertinent information specific to the Berlin region. This dataset offers rich insights into the dynamics of the Airbnb market in Berlin, including property characteristics, pricing trends, host demographics, and guest experiences.

**Key Components of the Dataset:**

1. **Listing Data:** Information about individual Airbnb listings in Berlin, including property type, neighborhood, amenities, pricing, availability, and host details.

2. **Host Data:** Details about Airbnb hosts in Berlin, including demographics, host verification status, response rate, and listing activity.

3. **Review Data:** Reviews and ratings provided by guests for Airbnb listings in Berlin, offering insights into guest experiences, satisfaction levels, and areas for improvement.


The dataset is provided in structured formats suitable for integration with Snowflake and processing using dbt. It is regularly updated to reflect the latest information about Airbnb activities in Berlin, ensuring the relevance and accuracy of the analysis.

By leveraging this comprehensive dataset, we aim to gain actionable insights into the dynamics of the Airbnb market in Berlin and support data-driven decision-making processes for stakeholders in the hospitality industry, urban planning, and tourism sectors.
