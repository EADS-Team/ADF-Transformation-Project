# ADF-Transformation-Project :

This project is designed to demonstrate data transformation using Azure Data Factory (ADF) by processing a CSV file stored in Azure Storage.

## Project Overview:

The goal of this project is to create an automated data pipeline that extracts a CSV file from an **input container**, applies a **Pivot transformation** to convert rows into columns, and stores the transformed data in an **output container** within an Azure Storage Account.

## Solution Overview:

To achieve this, the following steps were implemented:

## Setup & Configuration:

1. **Created an Azure Resource Group** – To organize Azure resources.

2. **Created an Azure Storage Account** – For storing input and output data.

3. **Created Two Containers**:

     * **Input container** – Stores the source CSV file.

     * **Output container** – Stores the transformed data.

 4. **Created an Azure Data Factory (ADF) instance** – For data transformation.

## Data Flow Implementation:

1) **Imported the source data** from the Storage Account into **Data Flow** in ADF.

2) **Applied a Pivot transformation** to convert row values into columns.

3) **Added a Sink transformation** to store the processed data into the **output container**.

4) **Integrated the Data Flow into an ADF pipeline** and triggered execution.

5) **Verified the output in the Storage Account** to ensure the data was successfully pivoted.

## Technology Stack:

* **Azure Storage Account** – For data storage.

* **Azure Data Factory (ADF)** – For orchestrating the data transformation.

* **Data Flow in ADF** – For applying the Pivot transformation.

## Conclusion:

This project successfully demonstrates how to transform structured data using Azure Data Factory. By leveraging Data Flow, we efficiently converted row-based data into a columnar format and automated the process using an ADF pipeline.
