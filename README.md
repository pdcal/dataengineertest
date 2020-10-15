![Airangel Logo](Airangel-200.png)

# Data Engineer Technical Test

## Instructions

* Include the source code for all phases of the process - ETL, data storage (schema), and data analysis (queries).
* At Airangel we don't currently have a standard set of data engineering tools, so we are happy for you to use your prefered toolset. Please include clear instructions on how to install/run the tools you select. 
* The solution must be reusable - we should be able to change the contents of the input file and be able to answer the same questions without updating code.
* You do not need to provide a visual representation of the output (e.g. a “dashboard”)
* Include a README, which includes a brief explanation of your design and assumptions, as well as instructions on how to run your solution. Also talk about how you could improve the process or next steps you could have taken if you had more time.

## Evaluation Process
We assess a number of things, including the design of your solution, program correctness, coding style, and general maintainability. While it is a small-ish problem, we expect you to submit what you believe is production-quality code – code that you’d be able to run, maintain, and evolve. You don’t need to “gold plate” your solution; however we are looking for something more than a quick and dirty answer.

## The Task

### Build a Schema

Using the data in the [Excel spreadsheet](Data.xlsx), build a schema that will make it possible to slice and dice the attached data. Create hierarchies in your schema (where possible) to aid with reporting and drilling through the data.

### Cleanse The Data

The data has numerous issues in it that will need to be dealt with. Decide on a strategy for cleansing the data and explain your reasoning.

### Answer These Questions

Use the schema you built to answer the following questions, for example by writing T-SQL:

1. How many academies have Standard 7 pupils as of July 1, 2014?
2. Out of the Standard 7 pupils enrolled as of July 1, 2014, what percentage has a `+` vs `-` status?
3. How many of the Standard 7 enrollees present as of February 1, 2014 are no longer present as of July 1 2014?
4. How many of the Standard 7 pupils joined in February 1, 2014?
5. How many unique Standard 7 pupil IDs do we have in Quarter 1 of 2014?
6. What percentage of Standard 7 enrollees share an exact name with another Standard 7 enrollee at the same academy? What is the count?

### Make Recommendations

With the information provided and your findings above, what would be your top three recommendations to Bridge to help ensure that pupil ID's can be trusted as the unique identifier to each and every pupil?
