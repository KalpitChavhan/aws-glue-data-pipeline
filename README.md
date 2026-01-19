# AWS Glue Data Pipeline Project

## Overview
This project demonstrates a serverless AWS data pipeline using S3, Glue, Athena, and QuickSight.

## Architecture
CSV → S3 → Glue Crawler → Glue ETL → Processed S3 → Athena → QuickSight

## Steps
1. Upload CSV to S3
2. Run Glue crawler
3. Transform data using Glue ETL
4. Store transformed data in S3
5. Query using Athena
6. Visualize using QuickSight

## Services Used
- Amazon S3
- AWS Glue
- Amazon Athena
- Amazon QuickSight

## Output
Salary increased by 10% and stored as FY26 dataset.
