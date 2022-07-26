# Employee_Compensation_K-means

![68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f3730302f312a6a67393056435f497434324371304b5a4f364a5133412e706e67](https://user-images.githubusercontent.com/29124048/180904011-bb5f7001-cdba-4170-a9ea-b5bb097f1869.png)

# Source of Data
The San Francisco Controller's Office maintains a database of the salary and benefits

paid to City employees since fiscal year 2013. This data is summarized and presented on

the Employee Compensation and is also

available in CSV format in the directory.

# Overview of the problem

## Description of Data :
Each row is an employee, and has columns about employee's information like their job type,salary, hours of overtime,other benefits etc.Overall there are 22 columns.


## Column definations:
* Year Type Fiscal (July through June) or Calendar (January through December)

* Year An accounting period of 12 months. The City and County of San Francisco operates on a fiscal year that begins on July 1 and ends on June 30 the following year. The Fiscal Year ending June 30, 2012 is represented as FY2011-2012.

* Organization Group Code Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.

* Organization Group Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.

* Department Code Departments are the primary organizational unit used by the City and County of San Francisco. Examples include

* Code Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).

* Union Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).

* Job Family Code Job Family combines similar Jobs into meaningful groups.

* Job Family Job Family combines similar Jobs into meaningful groups.

* Job Code Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.

* Job Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.

Employee Identifier Each distinct number in the “Employee Identifier” column represents one employee. These identifying numbers are not meaningful but rather are randomly assigned for the purpose of building this dataset. The column does not appear on the Employee Compensation report hosted on openbook.sfgov.org, but that report does show one row for each employee. Employee ID has been included here to allow users to reconstruct the original report. Note that each employee’s identifier will change each time this dataset is updated, so comparisons by employee across multiple versions of the dataset are not possible.

* Salaries Normal salaries paid to permanent or temporary City employees.

* Overtime Amounts paid to City employees working in excess of 40 hours per week.

* Other Salaries Various irregular payments made to City employees including premium pay, incentive pay, or other one-time payments.

* Total Salary The sum of all salaries paid to City employees.

* Retirement City contributions to employee retirement plans.

* Health and Dental City-paid premiums to health and dental insurance plans covering City employees. To protect confidentiality as legally required, pro-rated citywide averages are presented in lieu of employee-specific health and dental benefits.

* Other Benefits Mandatory benefits paid on behalf of employees, such as Social Security (FICA and Medicare) contributions, unemployment insurance premiums, and minor discretionary benefits not included in the above categories.

* Total Benefits The sum of all benefits paid to City employees.

* Total Compensation The sum of all salaries and benefits paid to City employees.
