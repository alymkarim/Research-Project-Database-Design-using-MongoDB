# Research Project Database Design using MongoDB

A document-oriented database project built with **MongoDB** to manage scientists, research projects, and funding information. The project demonstrates NoSQL database modelling, document design, data validation, and advanced querying using **MongoDB Shell** and **MongoDB Compass**.

## Project Description

This project was developed to design and implement a document-based database capable of storing comprehensive information about scientists and their research projects across universities in **Ireland, Scotland, Wales, and England**.

Unlike traditional relational databases, this solution leverages MongoDB's flexible document model to efficiently manage complex and hierarchical research data.

## Video Link to Project
Youtube Links
- Video 1: https://youtu.be/ImHuT0ZtSoQ
- Video 2: https://youtu.be/JtdJFTK6Gk8

## Features

* Document-oriented database design
* Scientist profile management
* Research project management
* Funding information tracking
* Embedded document modelling
* Flexible schema design
* Data validation
* CRUD operations
* Advanced MongoDB queries
* Aggregation pipelines

## Database Structure

### Scientists Collection

Each document stores scientist information together with associated research projects.

**Example fields**

* `_id`
* forename
* surname
* nationality
* town
* county
* date_of_birth
* university
* degree
* highest_qualification
* years_experience
* number_of_publications
* largest_grant
* income
* research_projects

### Embedded Research Project

Each scientist document may contain multiple research project documents.

**Example fields**

* project_id
* description
* discipline
* subject_area
* funding_source
* project_value
* start_year
* end_year
* progress_report

## Data Validation

The project implements validation rules to improve data quality.

* Required fields
* Positive numeric values
* Valid date ranges
* Standardised funding sources
* Standardised qualifications
* Consistent discipline categories
* Unique document identifiers

## Technologies

* MongoDB
* MongoDB Compass
* MongoDB Shell
* NoSQL Database Design
* BSON Documents

## Skills Demonstrated

* NoSQL database modelling
* Document-oriented database design
* Embedded documents
* CRUD operations
* Aggregation Framework
* Data validation
* MongoDB Compass
* MongoDB Shell
* Query optimisation

## Example Queries

The database supports queries such as:

* Find all scientists from a specific university.
* Retrieve projects funded by the European Union.
* List scientists with the highest research grants.
* Calculate total funding by research discipline.
* Search projects by subject area.
* Analyse funding trends using aggregation pipelines.

## Future Improvements

* Separate Funding Agencies collection
* Publications collection
* User authentication
* MongoDB Atlas cloud deployment
* Dashboard integration with Power BI
* REST API using Python FastAPI

## Author

**Alya Karim**

MSc Data Analytics
