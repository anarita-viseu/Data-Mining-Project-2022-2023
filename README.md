# Data-Mining-Project-2022-2023

Group project for the Data Mining course of the Master's Degree in Data Science and Advanced Analytics at NOVA IMS.

## Project Description
A2Z Insurance (A2Z) is a portuguese insurance company that serves a wide array of insurance services: Motor, Household, Health, Life and Work Compensation. Although A2Z primarily serves portuguese customers, a significant portion of their customer acquisition comes from their web site. Customers can sign up to A2Z services through their branches, by telephone, or on the web site.

In 2016, A2Z became one of the largest insurers in Portugal. However, the lack of a data driven culture in the company ultimately led to poorly maintained databases over the years. A2Z is trying to make better use of the database it has regarding its customers. So far, it has simply mass-marketed everything. All potential and existing customers get the same promotions, and there are no attempts to identify target markets for cross-selling opportunities. Now, A2Z wants start differentiating customers, and developing more focused programs.

A2Z provided an ABT (Analytic Based Table) with data regarding a sample of 10.290 Customers from its active database. These are customers that had at least one insurance service with the company at the time the dataset was extracted. The objective is to segment the database and find relevant clusters of customers. To do this, different approaches were used to segment the customers and the results were combined and analyzed. The value and demographics of each customer segment were explored, and the types of insurance they will be more interested in buying were identified.

Outcomes:
1. Exploration of data and identification of the variables that should be used to segment customers.
2. Identification of customer segments.
3. Justification of how clusters were found (taking in consideration the business use as well).
4. Exploration of the customer segments found.
5. Suggestion of business applications for the findings and creation of general marketing approaches for each cluster.

## Metadata
| Variable | Description | Additional Information |
|----------|-------------|------------------------|
| ID | ID |
| First Policy | Year of the customer’s first policy | May be considered as the first year as a customer |
| Birthday | Customer’s Birthday Year | The current year of the database is 2016 |
| Education | Academic Degree |
| Salary | Gross monthly salary (€) |
| Area | Living area | No further information provided about the meaning of the area codes |
| Children | Binary variable (Y=1) |
| CMV | Customer Monetary Value | Lifetime value = (annual profit from the customer) X (number of years that they are a customer) - (acquisition cost) |
| Claims | Claims Rate | Amount paid by the insurance company (€)/ Premiums (€) Note: in the last 2 years |
| Motor | Premiums (€) in LOB: Motor | Annual Premiums (2016). Negative premiums may manifest reversals occurred in the current year, paid in previous one(s) |
| Household | Premiums (€) in LOB: Household | Annual Premiums (2016). Negative premiums may manifest reversals occurred in the current year, paid in previous one(s) |
| Health | Premiums (€) in LOB: Health | Annual Premiums (2016). Negative premiums may manifest reversals occurred in the current year, paid in previous one(s) |
| Life | Premiums (€) in LOB: Life | Annual Premiums (2016). Negative premiums may manifest reversals occurred in the current year, paid in previous one(s) |
| Work | Compensation Premiums (€) in LOB: Work Compensations | Annual Premiums (2016). Negative premiums may manifest reversals occurred in the current year, paid in previous one(s) |


