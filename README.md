🌱 Boston Women Entrepreneurship Incubator Tracker

Relational Database Design & Analytics System

📌 Overview

This project designs and implements an industry-ready relational database system to support the Boston Women Entrepreneurs ecosystem. The system centralizes data related to women-led startups, entrepreneurs, mentors, investors, funding rounds, and events, enabling efficient data management and analytics-driven decision-making for incubators and accelerators. 

🎯 Problem Statement

Incubators and accelerators supporting women entrepreneurs often store critical data across fragmented systems, leading to duplication, inconsistency, and limited analytical insight. The absence of a centralized database makes it difficult to track startup progress, mentor engagement, funding history, and ecosystem-wide trends.

💡 Solution

The Boston Women Entrepreneurship Incubator Tracker provides a structured, scalable relational database that consolidates entrepreneurial activity into a single source of truth. The system supports:

Efficient data retrieval

Reduced duplication

Advanced analytics and reporting

Data-driven support for women founders

🧠 Key Features

Centralized tracking of startups, entrepreneurs, mentors, investors, events, and funding rounds

Extended Entity-Relationship (EER) and UML-based data modeling

Fully normalized relational schema implemented in MySQL

Support for advanced SQL analytics and reporting

NoSQL (MongoDB-style) queries for exploratory aggregation

Python-based database access and visualization

🗂️ Data Modeling
Conceptual Design

EER Diagram to capture entities, relationships, cardinalities, and constraints

UML Diagram to map object-oriented structure and inheritance

Relational Mapping

Superclass–Subclass hierarchy for people (Entrepreneur, Mentor, Investor)

Junction tables for many-to-many relationships (mentorships, investments, event participation)

Enforced primary and foreign key constraints for data integrity

🛠️ Technologies Used

Database: MySQL, NoSQL (MongoDB-style queries)

Modeling: EER Diagram, UML Diagram

Programming: Python

Libraries: pandas, mysql.connector, matplotlib

Analytics: SQL aggregates, joins, subqueries, NoSQL pipelines

📊 Analytics & Queries Implemented
SQL (MySQL)

Aggregate funding statistics per startup

Mentor–startup relationship analysis

Entrepreneurs with multiple startups (nested queries)

Event participation analysis (correlated subqueries)

Funding comparison using ALL and LEFT JOIN queries

NoSQL

Industry-based startup filtering

Investor capacity and preference matching

Top startups by total funding (aggregation pipeline)

🐍 Database Access via Python

Connected MySQL database using mysql.connector

Executed SQL queries programmatically

Converted query results into pandas DataFrames

Visualized analytics using matplotlib:

Funding vs number of rounds (scatter plot)

Event participation (pie chart)

Funding distribution (boxplot)

🔍 Key Insights

Funding distribution varies significantly across startups and industries

Certain mentors and investors play a disproportionately active role

Event participation patterns highlight high-impact networking formats

Centralized data enables ecosystem-wide visibility that fragmented systems cannot provide
