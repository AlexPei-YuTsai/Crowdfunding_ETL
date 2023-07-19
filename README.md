# Berkeley Data Bootcamp: Project 2
> Crowdfunding Data: The Extract, Transform, Load (ETL) Process

## Folder Contents
- A `Resources` folder containing both the `.xlsx` Excel files processed and the `.csv` exported after processing.
- A `ETL_Mini_Project_RDizon_JMickle_EMusa_SSohal_ATsai.ipynb` Notebook file that transforms the `.xlsx` files into normalized `.csv` SQL-compatible table schemas.
- A `Crowdfunding_db_ERD.jpg` Entity Relationship Diagram describing the relations between the table schemas.
- A `crowdfunding_db_schema.sql` file used to build the tables on a Relational Database Management System (RDBMS).
- A `.gitignore` file for Jupyter Notebook checkpoints and other commonly gitignored Python entities.

### Installation/Prerequisites
- Make sure you can run Python. The development environment we used was set-up with:
```
conda create -n dev python=3.10 anaconda -y
```
#### Imported Modules
- Installing via the conda command given should give you access to all of the script's modules locally. However, if you don't have them, be sure to grab yourself the following libraries:
  - [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)
  - [NumPy](https://numpy.org/install/)
  - The other imports you may notice are the Datetime and JSON modules. However, they are native Python modules and should have come with your Python downloads, no links are necessary. Any errors on that end are dependent on the machine's Python installation and pathing process.
 
#### SQL Dependencies
- Make sure you can run SQL and import all the CSV data in this directory. The code used was developed on pgAdmin4 and PostgreSQL 15.3 is the RDBMS used for implementation and testing.
  - Both Postgres and pgAdmin4 can be downloaded from the [same EDB download link here](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads) and no stacks or plug-ins were used during the creation of the attached SQL scripts.
  - Please follow [pgAdmin documentation](https://www.pgadmin.org/docs/pgadmin4/7.4/getting_started.html) or the standard importing procedure of your RDBMS administrator *after* running the `crowdfunding_db_schema.sql` file and building your tables.

## FINAL NOTES
> Project completed on July 20, 2023
