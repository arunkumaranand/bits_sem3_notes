# Data Warehousing

Course no: CSI ZG515/ SS ZG515
Instructor: SWARNA CHOUDHARY
Credit: 5 units
    - Class room Hours - 2
    - Student Preparation - 2
    - Case Studies - 1

## Course Description
Corporate decision makers require access to all the organization’s data, wherever it is located. To provide comprehensive analysis of the organization, its business, its requirements and any trends, require access to not only the current data in the database but also to historical data. To facilitate this type of analysis, data warehouses have been created to contain data drawn from several sources, maintained by different departments of the organization.
This course will involve an in-depth study of various concepts needed to 
- design, 
- develop, and 
- maintain a data warehouse.

It also provides an introduction to end user access tools like **OLAP and reporting**.

## Course Objective

1. Understand the importance of data warehouse and the business intelligence that can be gained with the help of data warehouse
2. Understand schema designs, information delivery techniques and architectures that are appropriate for data warehouse
3. Understand processes, management, and infrastructure necessary for building data warehouse 
4. Understand evolution of data warehouse with the presence of big data and cloud environments.

## Text Books
1. T1: Ponniah P, “Data Warehousing Fundamentals”, Wiley Student Edition, 2012
2. T2: Kimball R, “The Data Warehouse Toolkit”, 3e, John Wiley, 2013
3. R1: Anahory S, & Dennis M, “Data Warehousing in the Real World”, Pearson Education, 2008.
4. R2: Kimball R, Reeves L, Ross M, & Thornthwaite, W, “The Data Warehouse Lifecycle Toolkit”, John Wiley, 2e, 2012.
5. R3: Jiawei Han, Micheline Kamber and Jian Pei,  “Data Mining: Concepts and Techniques”, Morgan Kaufmann Publishers  2012
6. R4: Krish Krishnan, “Data Warehousing in the Age of Big Data”, Morgan Kaufmann Publishers  2013
7. R5: William H Inmon, et al., “DW 2.0 : The Architecture for the Next Generation of Data Warehousing”, Morgan Kaufmann 2012

## Course Content

### M1: Introduction to Data Warehousing

1. Evolution of Data Warehousing
2. Operational System Characteristics
3. Data Warehousing System Characteristics
4. Data Warehouse Architecture
5. Introduction to ETL, Data Staging Area & Presentation Servers
6. Introduction to Data Warehouse Design
7. Continuum of Analysis

- Review of concepts of DW, ETL, Information Delivery
- Examples of Business Intelligence applications
- Challenges in designing DW 
- Compare DW with Data Mining 
- DW, Unstructured data and Big data

### M2: Introduction to Dimensional Modelling

1. E R Modelling 
2. Dimensional Modelling Vocabulary
3. ER Modelling vs. Dimensional Modelling - Qualitative Comparison
4. Data Warehouse Design Steps 
5. Grocery Store Case Study

- Review Dimensional Modeling 
- Compare ER and Dimensional Modeling 
- Explain Retail Store analysis requirements 
- Retail Store Dimensional Model

### M3:	Architectural Components of a Data Warehouse

1. Data Marts
2. ODS
3. Top-down vs. Bottom up approaches to Data Warehousing
4. ETL & Data Staging Area 
5. Presentation Servers
6. OLAP

- Review concepts of data mart 
- Explain pros and cons of taking data mart approach towards EDW 
- Explain concepts of staging and OLAP 

### M4: Extraction, Transformation & Loading

1. ETL Overview
2. Major ETL Tasks
3. ETL requirements
4. Data Extraction
5. Data Transformation
6. Data Loading
7. Initial Load & referesh Cycle
8. Data Quality

- Explain concept of ETL
- Why data requires preprocessing
- Major types of transformation
- Methods of applying data to the warehouse.

### M5: Advanced Dimensional Modelling

1. Changing Dimensions, Surrogate keys & Look up tables
2. Mini-dimensions & Outriggers
3. Time Dimension
4. Conformed Dimensions & Facts 
5. Multi-valued Dimensions (Bridge & Helper Tables)
6. Dimension Hierarchies
7. Role-playing Dimensions 
8. Factless Fact Tables
9. Academic Warehouse Case Study
10. Bank Data Warehouse Case Study

- Illustrate problems of changing dimensions
- Techniques to handle changing dimensions 
- Examples for mini-dimensions and outriggers 
- Illustrate time dimension 
- Explain enterprise bus architecture 
- Illustrate bridge, role-playing dimensions, factless fact tables.

### M6: Online Analytical Processing (OLAP) & Multidimensional Databases (MDDB)

1. Introduction to OLAP & Multidimensional Analysis
2. Limitations of Spreadsheets & SQL
3. Major OLAP Features & Functions
4. Cube Operator
5. Introduction to Multidimensional Databases (MDDB)
6. Multidimensional Analysis & MDDBs
7. OLAP operations using MDDBs
8. MDDB vs. RDBMS
9. Cube Computation: Complexity & Optimization

- Explain concepts of OLAP	 (T1, Ch 15)
- Various OLAP operations with examles (R3, Ch 4)
- Relative strengths of MOLAP, ROLAP, and HOLAP (R3, Ch 4)

### M7: Query Performance Enhancing Techniques

1. Aggregation
2. Sparsity Failure
3. Shrunken, Lost, & Collapsed Dimensions
4. Aggregate Navigator
5. Aggregate Navigation Algorithm
6. Partitioning
7. Partitioning wrt Time 
8. View Materialization
9. Selection of Views to Materialize
10. View Maintenance Strategies
11. Incremental Maintenance Algorithms
12. Bitmap Indices
13. Bitmap Compression Strategies

- Data Warehouse performance challenges(T1, Ch 18)
- Concepts of physical design (T1, Ch 18)
- Use of aggregates, partitions for performance and operations (R1, Ch 6, Ch 7)

### M8: Metadata

1. Role of Metadata
2. Types of Metadata
3. Metadata Design & Implementation

- Concepts of Metadata (T1, Ch 9)
- Why Metadata becomes more important in DW (T1,Ch 9)
- Examples of Metadata (T1, Ch 9)

### M9: Support for Data Warehousing in RDBMS/SQL

1. Support for Data Warehousing in RDBMSs
2. New Features in SQL
3. Commonality between DW and RDBMS(T1, Ch 1)
4. SQL extensions for analytics (R4,Ch 2, Ch 3, Ch 18)

### M10: Real-time Data Warehousing

1. Need for Real-time Data Warehousing
2. Solutions for Real-time Data Warehousing
3. Real-time ETL 
4. Role of ODS in RTDWH  

- Concepts of real-time solutions(T2, Ch 20)
- Challenges with real-time data warehousing (T2, Ch 20)
- ETL vs. ELT (R6, Ch 13)

### M11: Current Trends in Data Warehousing

1. Introduction to World's Largest Data Warehouse
2. Big Data Analytics 
3. Extended RDBMS Architecture
4. MapReduce/Hadoop Architecture

- Recent trends in data warehousing (T1, Ch 3)
- Place of structured DW vs. Unstructured data, Big Data (T2,Ch 21)
- Possibilities of convergence of DW and Big Data (R5, Ch 13)

## Learning Outcome

1. Knowledge of business intelligence that can be gained from data warehouse.
2. Knowledge of schema designs, information delivery techniques and architectures for data warehouse.
3. Knowledge of processes, management, and infrastructure for building data warehouse.
4. Evolution of data warehouse with the presence of big data and cloud environments.