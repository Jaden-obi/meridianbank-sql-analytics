# MeridianBank SQL Analytics Project

This project uses a simulated retail banking database to practice and demonstrate SQL analysis for customer relationships, branch performance, transaction activity, merchant/card spending, risk flags, and data quality checks.

## Project Files

- `meridianbank_sql_project.sql` - Full SQL script with schema, sample data, and analysis queries.
- `docs/Jaden_SQL_Project_With_Insights.docx` - Recruiter-friendly portfolio document with business explanations, SQL comments, and insights.
- `docs/Jaden_SQL_Project_With_Insights.pdf` - PDF version for easy viewing.

## Skills Demonstrated

- SQL querying with `SELECT`, joins, filtering, grouping, and ordering
- Aggregation with `COUNT`, `SUM`, `AVG`, and conditional aggregation
- Window functions including `RANK`, `NTILE`, and `LAG`
- Customer segmentation and branch performance analysis
- Merchant/category spending analysis
- Risk and anomaly flagging
- Data quality checks using `LEFT JOIN` and `NULL` logic

## Database Model

The project uses six tables:

- `branches`
- `merchants`
- `customers`
- `accounts`
- `account_holders`
- `transactions`

The `account_holders` table supports many-to-many customer/account relationships, including joint accounts. Positive transaction amounts represent inflows, while negative amounts represent outflows.

## How to Run

1. Open SQLite Online, DB Browser for SQLite, DBeaver, or another SQLite-compatible tool.
2. Run the setup section in `meridianbank_sql_project.sql` to create and populate the database.
3. Run each analysis query one at a time to review the results.

## Portfolio Summary

The project is structured to show not just SQL syntax, but analyst thinking: each query is tied to a business question, the document explains what the query returns, and the insight bullets show how results can be interpreted for stakeholders.
