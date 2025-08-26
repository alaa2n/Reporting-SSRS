The project was divided into several stages:

Tabular Student Report

Created using the Report Wizard to display student data in a tabular format.

Added header with a logo image and footer displaying the username and execution time.

Used an expression to concatenate first and last names into a full name.

Applied conditional formatting to highlight students older than 23 years.

Added interactive sorting on the student age column.

Displayed the total student count in the last row.

Rendered the report as PDF.

Topic & Courses Report

Built with the Report Wizard to display each topic with its courses.

Configured page breaks to show each topic on a separate page.

Added built-in expressions to display page number out of total pages in the footer.

Matrix Report for Sales Data

Designed a matrix report that displays the sum of quantities per ProductID and SalesmanName.

The data was first generated using a custom SQL script to populate a Sales table.

Chart Report

Converted the matrix report into a chart visualization for clearer sales analysis.

Student Grades Report

Displayed student grades with student and course names.

Implemented indicator-based color coding for grades:

0–50 → Red

51–60 → Yellow

61–100 → Green

Stored Procedure Reports

Created reports that retrieve all courses using stored procedures.

Built parameterized reports for students, where the procedure accepts two parameters [Age1, Age2] and displays them in the header using expressions.

Parameterized Department Report

Designed a report with a dropdown parameter for Dept_ID, allowing users to select multiple departments.

All selected departments were displayed dynamically in the report header.

Linked Reports

Implemented linked reports by reusing an existing report and customizing parameters (e.g., showing only students above a certain age).

SSAS Cube Report

Connected the report to an Analysis Services cube as a data source.

Allowed filtering by Year dimension for analytical reporting.
