# Sales Insights — Power BI Dashboard

## Project Overview

The **Sales Insights Power BI Dashboard** is a data analytics project developed using Microsoft Power BI and SQL to analyze the sales performance of AtliQ Hardware, a company that supplies computer hardware and peripherals to clients across India.

The primary objective is to transform raw sales data into meaningful visual insights, enabling business stakeholders to monitor performance, identify sales trends, and make data-driven decisions.

## Problem Statement

AtliQ Hardware operates across multiple locations in India and supplies computer hardware and peripherals to various customers.

The sales director faces challenges in understanding the company's overall sales performance. Sales have been declining, and obtaining timely, actionable insights from traditional Excel reports has become increasingly difficult.

Regional managers provide sales updates using spreadsheets and numerical reports, making it challenging to identify trends, recognize underperforming markets, and respond quickly to business problems.

The company needs a centralized and interactive reporting solution to simplify sales analysis and improve decision-making.

## Solution

To address these challenges, an interactive Power BI dashboard was developed to convert raw sales data into meaningful visualizations and actionable insights.

The project uses SQL to explore and prepare the sales data and Microsoft Power BI to present key performance indicators, sales trends, and business performance across different dimensions.

The dashboard enables stakeholders to analyze sales performance, compare markets, and identify areas that require attention.

## Project Objectives

- Analyze overall sales performance and revenue trends.
- Monitor sales performance across different markets and regions.
- Identify top-performing customers and products.
- Understand changes in sales over time.
- Present business metrics through interactive visualizations.
- Help stakeholders make informed, data-driven business decisions.

## Tools & Technologies

- **Microsoft Power BI:** Dashboard development, data visualization, and interactive reporting.
- **SQL / MySQL:** Data querying, data exploration, and sales data analysis.
- **Power Query:** Data transformation and preparation within Power BI.
- **DAX:** Calculated measures and business metrics, where applicable.

## Project Structure

```text
Sales-Insights-PowerBI/
│
├── Screenshots/
│   └── Dashboard screenshots
│
├── Atliq-sales insight project.pbix
│   └── Power BI dashboard and data model
│
├── README.md
│   └── Project documentation
│
├── db_dump.sql
│   └── SQL database dump used to set up the dataset
│
└── sales_insight.sql
    └── SQL queries for data exploration and analysis
```

*Note: The file descriptions above reflect the apparent purpose of the files based on their names. The exact contents depend on the implementation in the repository.*

## Key Analysis Areas

The dashboard focuses on understanding the company's sales performance through visual reporting and business metrics.

- **Revenue Analysis:** Examine overall revenue and changes in sales performance.
- **Market Analysis:** Compare sales across different markets and regions.
- **Customer Analysis:** Identify key customers and evaluate their contribution to sales.
- **Product Analysis:** Understand product-level sales performance.
- **Sales Trends:** Explore changes in sales over time to identify patterns and potential issues.

*The exact metrics and analysis available depend on the measures and visuals implemented in the Power BI report.*

## Key Features

- Interactive Power BI dashboard for exploring sales data.
- SQL-based data exploration and querying.
- Visual representation of business performance.
- Sales analysis across multiple business dimensions.
- Consolidated reporting to support faster decision-making.

## AIMS Grid

The AIMS Grid is a project management framework used to establish the purpose, stakeholders, intended outcomes, and success criteria of a project.

| Component            | Description                                                                                                |
| -------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Purpose**          | Analyze sales performance and provide actionable insights to address declining sales.                      |
| **Stakeholders**     | Sales director, regional managers, and other business decision-makers at AtliQ Hardware.                   |
| **End Result**       | An interactive Power BI dashboard presenting sales insights through visualizations and business metrics.   |
| **Success Criteria** | Improve visibility into sales performance, simplify reporting, and support data-driven business decisions. |

## Getting Started

Follow these steps to explore the project on your local machine.

### Prerequisites

- Microsoft Power BI Desktop.
- MySQL Server, if you want to restore and query the SQL database.
- A SQL client such as MySQL Workbench, if required.

### Step 1: Clone the Repository

```bash
git clone <your-github-repository-url>
```

Navigate to the project directory:

```bash
cd <your-repository-folder>
```

Replace the placeholders with your actual GitHub repository URL and folder name.

### Step 2: Set Up the Database

1. Install and start MySQL Server if it is not already installed.
2. Open MySQL Workbench or another compatible SQL client.
3. Import or execute `db_dump.sql` to restore the database, following the file's actual structure and instructions.
4. Open `sales_insight.sql` to explore and execute the analysis queries.
5. Verify that the database and required tables are available.

### Step 3: Open the Power BI Dashboard

1. Install Microsoft Power BI Desktop.
2. Open `Atliq-sales insight project.pbix`.
3. Configure the data source connection if prompted.
4. Refresh the dataset if the required database is available.
5. Explore the report pages, charts, filters, and other interactive elements.

**Note:** The dashboard may require changes to its data source settings before it works on another machine.

## Learning Outcomes

Through this project, I gained practical exposure to:

- Building interactive dashboards using Microsoft Power BI.
- Exploring and querying relational data using SQL.
- Understanding data preparation and transformation workflows.
- Presenting business metrics through data visualizations.
- Analyzing sales performance to identify trends and potential business issues.
- Translating business requirements into analytical reports.
- Understanding how data analytics can support business decision-making.

## Author

**Sruti Kumari**

---

If you find this project useful, feel free to explore the repository and share your feedback.
