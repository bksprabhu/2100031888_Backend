# SQLite Database Setup

This repository contains Python code for setting up and querying an SQLite database for the work associated with **2100030140 - D BALAJI REDDY**. Two versions of the setup are provided: one without using JOIN and another using JOIN.

## File Structure

- **safertek_without_join.db**: SQLite database file created without using JOIN.
- **safertek_task_join.db**: SQLite database file created using JOIN.
- **README.md**: This README file.

## Database Schema

### Tables

1. **locations**: Stores information about various locations.
   - Columns:
     - `location_id`: Unique identifier for each location.
     - `street_address`: Street address of the location.
     - `postal_code`: Postal code of the location.
     - `city`: City of the location.
     - `state_province`: State or province of the location.
     - `country_id`: Identifier for the country of the location.

2. **countries**: Contains information about different countries.
   - Columns:
     - `country_id`: Unique identifier for each country.
     - `region_id`: Identifier for the region of the country.
     - `country_name`: Name of the country.

## Running the Code

1. Ensure you have Python and SQLite installed on your system.
2. Two SQLite database files (`safertek_without_join.db` and `safertek_task_join.db`) will be generated.
3. You can execute SQL queries directly on these databases or modify the Python script to perform additional operations.

## Queries

Two types of queries are demonstrated in the script:

1. **Without JOIN**: Directly selects data from both tables based on a common column.
2. **With JOIN**: Utilizes the JOIN operation to retrieve data from multiple tables based on a related column.

## Note

- Ensure that the SQLite3 library is installed in your Python environment to run the script successfully.
