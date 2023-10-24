# Microfinance Data Modeling with Python

### Project Overview
This project focuses on creating a data model for microfinance data using Python and various libraries. The data used in this project represents a real dataset from a company operating in the microfinance sector. To protect privacy and confidentiality, customer details have been anonymized and altered. The primary goal of this project is to structure and store data from various sources, such as CSV files, into a PostgreSQL database, and enable users to perform data operations using SQLAlchemy.

This real-world dataset showcases the practical application of data modeling and database management techniques in the microfinance industry, with a focus on customer information, loans, disbursements, repayments, and outstanding balances. The project provides a solid foundation for working with microfinance data and can be extended and customized for specific business needs.

### Prerequisites
List the prerequisites required to run the project, including:

Python (mention the version)
PostgreSQL database
Required Python libraries (e.g., SQLAlchemy csv)
Knowledge of SQL and Python data modeling concepts
### Installation

1. **Clone the Repository**: To get started, clone the project repository. 

2. **Install Python Libraries**: Install the required Python libraries using `pip`. Navigate to the project directory and run:

   ```bash
   pip install -r requirements.txt
   ```

3. **Database Setup**: You'll need to set up a PostgreSQL database. Make sure you have PostgreSQL installed and running. Configure the database connection details in the project by modifying the database URL in the configuration.

   - [PostgreSQL Installation Guide](https://www.postgresql.org/download/)
   - [SQLAlchemy Documentation](https://docs.sqlalchemy.org/en/20/)

### Data Modeling

In this project, we've defined the following tables:

- **Customer**: This table stores customer information, including their name, age, address, and city.

- **Loan**: The Loan table contains data related to loans, such as agreement dates, disbursement information, and more. It establishes a relationship with the Customer table.

- **Disbursement**: This table tracks disbursement details for loans, including disbursement amounts and dates.

- **Outstanding**: Outstanding records related to loans, such as outstanding amounts, interest, and payments, are stored in this table.

- **Repayment**: The Repayment table records repayments made for loans.

   - [SQLAlchemy ORM Tutorial](https://docs.sqlalchemy.org/en/20/orm/tutorial.html)
   - [Data Modeling Guide](https://www.lucidchart.com/pages/data-modeling-guide)
     
![microfinance_data_model](https://github.com/MampiononaRajaoferason/microfinance_data_modelling/assets/38230401/1dfea94c-08ff-4458-a764-084b2856bc31)

### Data Import

To import data into the PostgreSQL database, follow these steps:

1. Prepare your data in CSV format. Make sure the data in the CSV files matches the format expected by the project.

2. Use the provided scripts to read the CSV files and insert data into the respective database tables. Ensure that the file paths are correctly set in the scripts.

### Database Initialization

To initialize the database schema, you can use the provided SQLAlchemy models. The schema will be automatically generated based on the table definitions. Ensure that your PostgreSQL database is up and running, and that you have configured the connection details in the project settings.

   - [SQLAlchemy Core Tutorial](https://docs.sqlalchemy.org/en/20/core/tutorial.html)

### Data Insertion

Inserting data into the database tables is done using Python scripts. Use the provided scripts as examples to insert data from CSV files or other sources. Modify the scripts to match your data and requirements.

   - [SQLAlchemy Inserting Data](https://docs.sqlalchemy.org/en/20/orm/tutorial.html#inserting-data)

### Querying Data

You can query data from the database using SQLAlchemy. The project provides examples of common queries. Adjust the queries as needed to retrieve information from the tables.

   - [SQLAlchemy Querying Data](https://docs.sqlalchemy.org/en/20/orm/tutorial.html#querying)

### Usage

The project can be used for various microfinance data management tasks, such as storing and analyzing customer, loan, disbursement, and repayment data. You can use it to:

- Import and store microfinance data from external sources.
- Query and analyze data for reporting and decision-making.
- Expand and customize the data model to suit your specific needs.


### Contact Information

If you have questions or need support, you can contact me at mampionona@aims.ac.za or via my skype: Mampionona Rajaoferason.



