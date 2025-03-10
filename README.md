# Analytics Engineering Resources

A  list of tools, concepts, and learning resources for analytics engineers. It covers essential technologies, frameworks, and best practices. While most of the links focus analytics enginnering there's some that are data engineering. Since there's so much overlap between the two fields.

## 🖥️ Contributing
Feel free to contribute to this list by adding links you've found helpful. Submit a Pull Request (PR) with your suggestions.

## ⏰ Getting Started

- What is Analytics Engineering?
  - [What is an analytics engineer?](https://www.kellyjadams.com/post/what-is-an-analytics-engineer)
  - [The Rise of Analytics Engineering (and Why You Should Care)](https://youtu.be/Qj1_KgakzqU?si=gO5rKvuHY84KjyJU)
  - [What is an Analytics Engineer? Everything you need to know](https://www.datacamp.com/blog/what-is-an-analytics-engineer-everything-you-need-to-know)
  - [Analytics Engineer vs Data Analyst](https://www.getdbt.com/blog/analytics-engineer-vs-data-analyst)
  - [What is Analytics Engineering?](https://www.getdbt.com/blog/what-is-analytics-engineering)
  - [Analytics Engineering Life Cycle](https://www.getdbt.com/resources/guides/the-analytics-development-lifecycle)
  - [Analytics Engineer Responsibilties](https://handbook.gitlab.com/job-families/marketing/enterprise-data/analytics-engineer/)
- Need real-world data? Check out [Sites to Find Public Datasets](#sites-to-find-public-datasets)
- Looking for courses? See [Specific Courses](#specific-courses)
- Need an overview? Checkout [A guiode to the data landscape](https://www.metabase.com/learn/grow-your-data-skills/data-landscape/data-landscape)

---

## ⚒️ Tools & Concepts for Analytics Engineers  

### Data Transformation  
- [dbt](https://www.getdbt.com/) – Modular SQL-based transformations
- [SQLMesh](https://sqlmesh.com/) – Open source Data Transformations
- [DataForm](https://cloud.google.com/dataform?hl=en) – Google BigQuery specific Data Transformation tool
- [SQL Basics](https://www.w3schools.com/sql/) – Querying and transforming structured data
- [Apache Spark](https://spark.apache.org/) – Large-scale distributed data processing

### Orchestration  
- [Apache Airflow](https://airflow.apache.org/) – Workflow automation & scheduling
- [Dagster](https://dagster.io/) – Workflow automation & scheduling
- [Prefect](https://www.prefect.io/) – Pythonic Workflow orchestration
- [Google Cloud Workflows](https://cloud.google.com/workflows?hl=en) - Google's version of Workflows 

### Data Storage  
- [Snowflake](https://www.snowflake.com/) – Cloud data warehousing
- [BigQuery](https://cloud.google.com/bigquery) – Serverless, scalable data warehouse
- [Databricks](https://www.databricks.com/) – Data Lakehouse from creators of Apache Spark
- [PostgreSQL](https://www.postgresql.org/) – Relational database

### Version Control & CI/CD  
- [Git](https://git-scm.com/) – Version control for data projects
- [GitHub Actions](https://github.com/features/actions) – Automate testing and deployment

### Business Intelligence (BI) Tools  
- [Looker](https://looker.com/) – Modern BI platform
- [Metabase](https://www.metabase.com/) - Open source & scalable
- [Power BI](https://www.microsoft.com/en-us/power-platform/products/power-bi) - One of the major players, from Microsoft
- [Tableau](https://www.tableau.com/) – The other major player, from/owned by Salesforce

### Infrastructure & Deployment  
- [Docker](https://www.docker.com/) – Containerization for data apps
- [Kubernetes](https://kubernetes.io/) – Orchestrate and scale data pipelines
- [Terraform](https://www.terraform.io/) – Infrastructure as code

## ✏️ Best Practices

⚠️This section is still a work in progress, feel free to add more ⚠️

### Data Modeling

- Use a Star Schema – Organize data into fact and dimension tables to improve query performance.
- Partition & Cluster Large Tables – Partition by date and cluster by frequently filtered columns to speed up queries.  
- Documentation – Document the data models to keep schema and relationships clear.

---

## 📚 Learning Resources
- Specific Courses
- Sites to Find Datasets
- LinkedIn Creators
- Books
- Newsletters

### Specific Courses

- [Hands-On Analytics Engineering Project - LinkedIn Learning Course](https://www.linkedin.com/learning/hands-on-analytics-engineering-project?trk=profile_featured_learning_course&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BVP3qykzJS%2BeH05NxdZYLLw%3D%3D)
- [Git Immersion - Free course in Ruby to learn basics of Git](https://gitimmersion.com/)
- [Data Engineering with dbt - LinkedIn Learning Course](https://www.linkedin.com/learning/data-engineering-with-dbt/build-your-first-dbt-project?u=57888345)
- [Microsoft's Fabric Analytics Engineer Assosciate](https://learn.microsoft.com/en-us/credentials/certifications/fabric-analytics-engineer-associate/?practice-assessment-type=certification
)

### Sites to Find Public Datasets

Note this is very similar to the same section in [data-analytics-resources](https://github.com/kellyjadams/data-analytics-resources).

- [Datahub](https://datahub.io/collections)
- [Dataset Search](https://datasetsearch.research.google.com/) 
- [Kaggle](https://www.kaggle.com/datasets) 
- [Data Gov](https://data.gov/)
- [Maven Analytics Data Playground](https://www.mavenanalytics.io/data-playground)
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
- [Datacamp Datasets](https://www.datacamp.com/workspace/datasets)
- [NASA Data](https://data.nasa.gov/)
- [Google BigQuery](https://cloud.google.com/bigquery/docs/sandbox)
- [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/datasets)

### LinkedIn Creators

- [Madison Schott](https://www.linkedin.com/in/schottmadison/)
- [Connor Dickson](https://www.linkedin.com/in/connordickson2/)
- [Bruno Souza de Lima](https://www.linkedin.com/in/brunoszdl/)
- [Redha Cherif](https://www.linkedin.com/in/redhacherif/)

### Books

- [Fundamentals of Data Engineering](https://a.co/d/drxVkzH) by Joe Reis, Matt Housley 
- [Data Pipelines Pocket Reference](https://a.co/d/ckHnFB3) by James Densmore
- [The ABCs of Analytics Engineering - Ebook](https://madisonmae.gumroad.com/l/learnanalyticsengineering) by Madison Schott
- [Data Wrangling on AWS](https://a.co/d/3zxPxdL) by Navnit Shukla, Sankar M, Sam Palani

### Newsletters 

- [Learn Analytics Engineering](https://learnanalyticsengineering.substack.com/subscribe) from [Madison Schott](https://www.linkedin.com/in/schottmadison/)
- [Analytics engineering](https://redhacherif.substack.com/) from [Redha Cherif](https://www.linkedin.com/in/redhacherif/)
