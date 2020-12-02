# intelliHR's hiring assessment for UX Engineers - Team Analytics

## Employee Data Visualization App

### Problem Description

`Wayne Enterprises` keeps all their employee data in a small csv file (`./data/employee.csv`).
`Bruce Wayne`, the CEO of the company, regularly asks his manager, Alfred, for various insights from the companys data.

Some of the insights that Mr. Wayne has asked for in the past include:
- What is the total headcount of Wayne Enterprises?
- How many Male employees work here?
- How many Female employees work here?
- What's the age distribution across all the business units of the company?
- How many part time employees work here?

Alfred isn't very tech savvy and his skills are limited to using excel spreadsheets. Consequently, each time Mr. Wayne asks for a specific insight, Alfred opens up the companys dataset in excel and creates a new formula or chart that answers Mr. Wayne's question. For example, when Mr. Wayne asked Alfred how many of the company's employees were Male, how many were Female, and how many were Non-binary, Alfred opened up excel and created the following formulas:

Number of Male employees = `SUM(COUNTIF(<Gender Column>, <Cell where gender is Male>))`
Number of Male employees = `SUM(COUNTIF(<Gender Column>, <Cell where gender is Female>))`
Number of Male employees = `SUM(COUNTIF(<Gender Column>, <Cell where gender is Non-binary>))`

He then displayed the values calculated above on a histogram and included the histogram in the company's monthly report. Now, everytime the data in the excel spreadsheet is updated, Alfred's formulas calculate the new number of Male, Female and Non-binary employees. Although this solution works, Alfred has idenitfied that it isn't ideal due to Mr. Waynes erratic needs. Immediately after showing Mr. Wayne the histogram, he asked Alfred to also include the number of `Male and Female` employees that work at Wayne Enterprises to the report. Consequently, Alfred had to go back into excel, create a new formula as follows and include its result in the histogram used in the monthly report:

Number of Male and Female employees = `SUM(COUNTIF(<Gender Column>, <Cell where gender is Male>))` + `SUM(COUNTIF(<Gender Column>, <Cell where gender is Female>))`

Since Mr. Wayne regularly asks for new insights from the companys dataset, Alfred has decided to hire a Design Engineer that is capable of creating a simple but eye catching application, that is easy to use and capable of querying the dataset for various insights that have already been asked for by Mr. Wayne and that may be asked for by him in the future.

### Assessment Goal
Build a simple but eye catching application that is easy to use, capable of querying the dataset provided for the insights listed below, and able to visually represent these insights:

- What is the total headcount of Wayne Enterprises?
- How many Male employees work here?
- How many Female employees work here?
- What's the age distribution across all the business units of the company?
- How many part time employees work here?

Additionally, the application should be capable of providing additional insights that Mr. Wayne may request for in the future. You do not know what these insights might be at the moment.

### Assessment Criteria

Your application will be assessed on the following criterias:

#### Main Criteria
1. Ease of use. Does it take a lot of effort to use your application and interpret the results it produces?

2. Aesthetics. How eye catching is your application?

3. Correctness. Does your application produce the correct answer when used to display certain insights?

4. Robustness of the solution. Can your application handle edge cases well?

5. Completeness. Can your application provide a wide range of insights that Mr. Wayne may ask for in the future?

6. Ease of interpretation. How easy is it to interpret the insights produced by your application?

#### Bonus Criteria
It is not mandatory for your application to meet these criteria but you will receive bonus points if it does!

1. Responsiveness. Is your application usable on different devices and screen sizes? (Mobile, Tablet, Desktop, etc)

2. Web Application based solution. Although you are not required to build a Web Application based solution, it would be advantageous if you could show us that you are familiar with Web Technologies.

3. Tech Stack comprising of one or more of the following technologies:
- JavaScript
- TypeScript
- React JS
- D3.js
- Python

### Some Final Notes
Please note that the `Main Criteria` will be given higher preference over the `Bonus Criteria`. That is, an application that strongly addresses the Main Criteria and doesn't address the Bonus Criteria at all may be given higher preference than one that loosely addresses both the Main and Bonus criterias.

If you have any questions or concerns regarding the assessment, please reach out to the hiring manager that sent you this assessment.

Have fun!
