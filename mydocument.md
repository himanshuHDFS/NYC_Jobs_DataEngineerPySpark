 Data Engineering Take Home Assignment

1) Data Processing

Steps applied:
- Data cleaning
- Column standardization
- Feature engineering
- Feature removal
- Dataset transformation

2) Feature Engineering Techniques

1. Average salary calculation
2. Salary category classification
3. Degree requirement flag

3) Features Removed

Columns removed:
- recruitment_contact
- process_date
- internal metadata

4) Challenges

- Handling missing salary values
- Parsing text fields
- Extracting skills from descriptions

5) Assumptions

- Salary midpoint represents actual salary
- Degree requirement inferred from text

6) Deployment Proposal

Pipeline can be deployed using:

- Docker container
- Spark cluster (AWS EMR / Databricks)
- Scheduler (Airflow)

7) Triggering Approach

Pipeline execution using:

spark-submit pipeline.py