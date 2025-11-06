Netflix’s Drama Analysis

Overview
This project explores the use of the **Hadoop ecosystem** to analyze large-scale structured data using the **Netflix dataset**.  
The dataset contains details about Netflix’s movies and TV shows — such as titles, directors, countries, release years, ratings, durations, and genres.

The project demonstrates how **HDFS**, **Hive**, and **Sqoop** can be used together to:
Store big data efficiently  
Query and analyze it using HiveQL  
Integrate it with MySQL for further reporting or visualization

Objectives
Store the Netflix dataset in a distributed environment using **HDFS**  
Perform data analysis using **Hive**  
Import and export data between Hadoop and MySQL using **Sqoop**  
Demonstrate a complete **Big Data workflow** — from storage to analysis to integration  
Understand **scalability**, **fault tolerance**, and **parallel processing** in Hadoop

Columns:
| Column Name | Description |
|--------------|-------------|
| show_id | Unique ID for each title |
| type | Movie or TV Show |
| title | Name of the title |
| director | Name of the director |
| country | Country of production |
| release_year | Year of release |
| rating | Audience rating (e.g., TV-MA, PG-13) |
| duration | Duration of movie or seasons of show |
| listed_in | Genre or category |
| description | Short summary of the title |

Project Scope
This project demonstrates the end-to-end data processing workflow:
1. **Store** the dataset in **HDFS**
2. **Analyze** data using **Hive**
3. **Transfer** data using **Sqoop**
4. Generate **analytical insights** about Netflix content

Technologies Used
| Component | Description |
|------------|-------------|
| **Operating System** | Cloudera (CentOS/Linux) |
| **Big Data Framework** | Apache Hadoop 3.x |
| **Storage** | HDFS |
| **Query Engine** | Apache Hive |
| **Data Transfer Tool** | Apache Sqoop |
| **Database** | MySQL |
| **Interface** | Hadoop CLI |
| **Hardware Requirement** | 8 GB RAM, 100 GB Storage |

Implementation Summary
HDFS Commands
1. Upload CSV file and list directories  
2. Count total records  
3. Preview first 10 rows  
4. Filter data for India  
5. Check file/block information  
Hive Commands
1. Create Hive table  
2. Load data from HDFS  
3. Count Movies vs TV Shows  
4. Find Top 5 countries by content  
5. List recently released shows  
Sqoop Commands
1. Import data from MySQL to HDFS  
2. List all databases  
3. List all tables  
4. Incremental import  
5. Export processed data back to MySQL  

Results
Compared Movies vs TV Shows
Identified top content-producing countries
Found recent releases and trends  
Integrated data smoothly between Hadoop and MySQL

