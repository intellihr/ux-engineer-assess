# intelliHR's hiring assessment for UX Engineers - Team Analytics

## Employee Data Visualization App

### Problem Description
**Wayne Enterprises** keeps all their employee data in a small csv file (`./data/employee.csv`).
**Bruce Wayne**, the CEO of the company, regularly asks his manager, **Alfred**, for various insights from the companys dataset.

Some of the insights that Mr. Wayne has asked for in the past include:

- What is the headcount of Wayne Enterprises when broken down by gender, work rights, work classes, age groups, and business units?
- What is the age distribution of our employees across these categories?
- How has the headcount of Wayne Enterprises changed over time across these categories?

Answers to these questions help Mr. Wayne identify potential issues across his business and tend to them well ahead of time. For example, by studying the change in headcount over time across different **business units**, Mr. Wayne might identify a rapid decrease in headcount over time within the **Finance** business unit and accordingly carry out investigations to identify and rectify the root cause for this decreasing trend.

Alfred, however, isn't very tech savvy, and his skills are limited to using excel spreadsheets. Consequently, each time Mr. Wayne asks for a specific insight, Alfred loads the companys dataset in excel and manually creates a new formula or chart that answers Mr. Wayne's question. For example, when Mr. Wayne asked Alfred how many of the company's employees are **Male**, how many are **Female**, and how many are **Non-binary**, Alfred opened up excel and created the following formulas:

Number of Male employees = `SUM(COUNTIF(<Gender Column>, <Cell where gender is Male>))`
Number of Female employees = `SUM(COUNTIF(<Gender Column>, <Cell where gender is Female>))`
Number of Non-binary employees = `SUM(COUNTIF(<Gender Column>, <Cell where gender is Non-binary>))`

He then displayed the values calculated above on a histogram and included the histogram on the companys internal website. Everytime the data in the excel spreadsheet is updated, Alfred's formulas calculate the new number of Male, Female and Non-binary employees, which updates the histogram. Alfred then manually updates the chart on the companys website. Although this solution works, Alfred has idenitfied that it isn't ideal due to Mr. Waynes erratic needs. Immediately after showing Mr. Wayne the histogram, he asked Alfred to also include the number of **Male and Female** employees that work at Wayne Enterprises to the chart. Consequently, Alfred had to go back into excel, create a new formula as follows and include its result in the histogram:

Number of Male and Female employees = `SUM(COUNTIF(<Gender Column>, <Cell where gender is Male>))` + `SUM(COUNTIF(<Gender Column>, <Cell where gender is Female>))`

The tedious nature of having to manually manipulate the excel spreadsheet everytime Mr. Wayne asks for new insights has led Alfred to look for a UX Engineer capable of building a simple but eye catching application that is able to interpret the companys dataset and produce a wide range insights when requested for. Additionally, Alfred would prefer for the application to be accessible by a web browser, so that Mr. Wayne can directly interact with it whenever he requires new insights. Doing so would mean that Alfred never has to worry about manually generating insights for Mr. Wayne ever again!

### Assessment Goal
Build an application that is easy to use, capable of reading and interpreting the dataset provided for the insights listed below, and able to visually represent these insights in an aesthetic manner:

- What is the headcount of Wayne Enterprises when broken down by gender, work rights, work classes, age groups, and business units?
- What is the age distribution of our employees across these categories?
- How has the headcount of Wayne Enterprises changed over time across these categories?

Additionally, the application should be capable of providing insights that Mr. Wayne may request for in the future. You do not know what these insights might be at the moment.

### Assessment Criteria
Your application will be assessed on the following criteria:

#### Main Criteria
1. Ease of use. Does it take a lot of effort to use your application?
1. Ease of interpretation. How easy is it to interpret the insights produced by your application?
1. Creativity. How original are you ideas and designs?
1. Aesthetics. How eye catching is your application?
1. Correctness. Does your application produce the correct result when displaying certain insights?
1. Robustness. Can your application handle edge cases well?
1. Completeness. Can your application provide all possible insights that Mr. Wayne may ask for in the future?

#### Bonus Criteria
It is not mandatory for your application to meet these criteria but you will receive bonus points if it does!

1. Web Application based solution. Although you are not required to build a Web Application based solution, it would be advantageous if you could show us that you are familiar with Web Technologies.
1. Responsiveness. Is your application usable on different devices and screen sizes? (Mobile, Tablet, Desktop, etc)
1. Tech Stack comprising of one or more of the following technologies:
- JavaScript
- TypeScript
- React JS
- D3.js
- Python

### Submission Notes
You can submit your solution in whatever way you see fit. That is, you can use GitHub, GitLab, .zip files or any other method to submit your solution. However, please state the steps required to get your application up and running with minimal effort. If we can't get your application running, we can't assess it!

### Some Final Notes
Please note that the **Main Criteria** will be given higher preference over the **Bonus Criteria**. That is, an application that strongly addresses the Main Criteria and doesn't address the Bonus Criteria at all may be given higher preference over one that loosely addresses both the Main and Bonus criterias.

Additionally, if you feel like the the solution to the problem and technologies listed above are limiting your creativity, please feel free to use whatever technologies or tools that you see fit to show us what you are capable of. For example, if you believe that you can design beautiful charts and animations using photoshop, by all means do so!

If you have any questions or concerns regarding the assessment, please reach out to the hiring manager that sent you this assessment.

Have fun!
