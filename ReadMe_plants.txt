Plants with Pliers Business Database README
Overview

Welcome to the Plants with Pliers Business Database repository. This database contains real data from a small plant startup, collected and organized using SQL. The data has been imported into Power BI via ODBC, and additional columns have been added to enhance the analysis. The database is designed to provide insights into sales and inventory aspects of the business.

Confidentiality Assurance: Customer data is held confidential and is not shared outside the organization. Any access or use of this database should adhere to the company's data privacy and security policies.
Table of Contents

    Getting Started
        Prerequisites
        Installation
    Database Structure
        Tables
        Relations
    Power BI Dashboards
        Sales Dashboard
        Inventory Dashboard
    Contributing
        Code Style
        Submitting Changes
    Troubleshooting
    License

Getting Started
Prerequisites

Before using the Plants with Pliers Business Database, make sure you have:

    SQL Server installed for data collection.
    Power BI installed for visualization.
    ODBC driver for connecting SQL to Power BI.

Installation

    Clone the repository:

    bash

    git clone https://github.com/your-username/plants-with-pliers-database.git

    Follow the specific instructions for setting up SQL Server and Power BI, as well as configuring the ODBC connection.

Database Structure
Tables

The database includes tables with information on customers, sales, and inventory. Details on table structures are available in the SQL schema.
Relations

The relationships between tables are crucial for data coherence. Refer to the schema documentation for insights into how tables are connected.
Power BI Dashboards
Sales Dashboard

The Sales Dashboard provides a comprehensive view of the business's sales performance.

    Customer Invoice History Slider: Analyze customer invoices over time.
    Top Selling Categories Bar Graph: Identify the most profitable product categories.
    Sales Over Time Line Graph: Visualize the trend of sales over a specific period.
    Key Highlights Card: Display key performance indicators.
    Average Sale Gear: Understand the average sale value.
    Payment Methods Wheel Graph: Explore the distribution of payment methods.
    Total Dollars Earned Card: View the overall revenue earned.

Inventory Dashboard

The Inventory Dashboard offers insights into the business's inventory management.

    Targeted Price Point Funnel Graph: Visualize the distribution of items based on price points.
    Distribution of Assets Column Chart: Analyze the distribution of assets in the inventory.
    Distribution of Mediums (Substrates) Column Chart: Explore the variety of substrates used.
    Growth Distribution (Small, Large, Medium): Understand the distribution of plant growth sizes.
    Maturity Curve (Small, Medium, Large) Line Graph: Track the maturity curve of plants.
    Total Amount of Unique Species Card: Display the count of unique plant species.
    Total Amount of Proposed Revenue Card: Show the proposed revenue from all items.

How to Reproduce:

    Clone the Repository:
        Clone this GitHub repository to your local machine.

    Load Data into Power BI:
        Import the provided dataset into Power BI.

    Explore and Analyze:
        Open the Power BI file and explore the various pages and visualizations.

    Adjust and Customize:
        Customize the dashboard by adding or modifying visualizations based on your specific needs.

Contributions

Contributions to this project are welcome. Feel free to fork the repository, make changes, and submit a pull request.