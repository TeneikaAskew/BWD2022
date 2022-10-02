# Black Women in Data 2022

Black Women Data 2022 - Power BI Workshop
 

 <img src="https://github.com/TeneikaAskew/BWD2022/blob/main/Visuals/DashboardScreenshot.jpg" alt="Teneika HR Dashboard" style="height: 300px; width:300px" align="left"/>**Case:** You are a consultant working with a human capital division that provides people analytics services to Fortune 500 organizations. The organization has asked you to build a dashboard around their team and organizational performance and employee sentiment. This case is inspired by this[ Kaggle challenge](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set).

** **

**Data:**[ Introduction to the HR Dataset - Version 14](https://rpubs.com/rhuebner/hrd_cb_v14)  - Last Updated April, 2021. This HR Dataset is a synthetic data set created specifically to use for HR analytics cases and is updated every year or so, by the owners. Updates include additional columns, and to make slight changes to the underlying data.

** **

<br><br>**Inspirational Questions:** Here are some open-ended questions that you can explore and try to address through creating visualizations, or R or Python analyses.



*  **_Is there any relationship between who a person works for and their performance score?_**
*  **_What is the overall diversity profile of the organization?_**
*  **_What are our best recruiting sources if we want to ensure a diverse organization?_**
*  **_Can we predict who is going to terminate and who isn't? What level of accuracy can we achieve on this?_**
*  **_Are there areas of the company where pay is not equitable?_**
*  Is there any relationship between who a person works for and their performance score?
*  What is the overall diversity profile of the organization?
*  What are our best recruiting sources if we want to ensure a diverse organization?
*  Can we predict who is going to terminate and who isn't? What level of accuracy can we achieve on this?
*  Are there areas of the company where pay is not equitable?
*  Is there a relationship between age and performance
*  Does working on special projects affects performance




**[Google Jamboard](https://jamboard.google.com/d/1ooEhhoE0ltCEsq_k6_e082Krl0DX5Ty2rHS6M8hi_fY/edit?usp=sharing)


**Data Dictionary:**

** **


<table>
  <tr>
   <td><strong>Feature</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>DataType</strong>
   </td>
  </tr>
  <tr>
   <td>Employee Name
   </td>
   <td>Employee’s full name
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>EmpID
   </td>
   <td>Employee ID is unique to each employee
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>MarriedID
   </td>
   <td>Is the person married (1 or 0 for yes or no)
   </td>
   <td>Binary
   </td>
  </tr>
  <tr>
   <td>MaritalStatusID
   </td>
   <td>Marital status code that matches the text field MaritalDesc
   </td>
   <td>Integer
   </td>
  </tr>
  <tr>
   <td>EmpStatusID
   </td>
   <td>Employment status code that matches text field EmploymentStatus
   </td>
   <td>Integer
   </td>
  </tr>
  <tr>
   <td>DeptID
   </td>
   <td>Department ID code that matches the department the employee works in
   </td>
   <td>Integer
   </td>
  </tr>
  <tr>
   <td>PerfScoreID
   </td>
   <td>Performance Score code that matches the employee’s most recent performance score
   </td>
   <td>Integer
   </td>
  </tr>
  <tr>
   <td>FromDiversityJobFairID
   </td>
   <td>Was the employee sourced from the Diversity job fair? 1 or 0 for yes or no
   </td>
   <td>Binary
   </td>
  </tr>
  <tr>
   <td>Salary
   </td>
   <td>The person’s yearly salary. $ U.S. Dollars
   </td>
   <td>Float
   </td>
  </tr>
  <tr>
   <td>Termd
   </td>
   <td>Has this employee been terminated - 1 or 0
   </td>
   <td>Binary
   </td>
  </tr>
  <tr>
   <td>PositionID
   </td>
   <td>An integer indicating the person’s position
   </td>
   <td>Integer
   </td>
  </tr>
  <tr>
   <td>Position
   </td>
   <td>The text name/title of the position the person has
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>State
   </td>
   <td>The state that the person lives in
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>Zip
   </td>
   <td>The zip code for the employee
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>DOB
   </td>
   <td>Date of Birth for the employee
   </td>
   <td>Date
   </td>
  </tr>
  <tr>
   <td>Sex
   </td>
   <td>Sex - M or F
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>MaritalDesc
   </td>
   <td>The marital status of the person (divorced, single, widowed, separated, etc)
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>CitizenDesc
   </td>
   <td>Label for whether the person is a Citizen or Eligible NonCitizen
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>HispanicLatino
   </td>
   <td>Yes or No field for whether the employee is Hispanic/Latino
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>RaceDesc
   </td>
   <td>Description/text of the race the person identifies with
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>DateofHire
   </td>
   <td>Date the person was hired
   </td>
   <td>Date
   </td>
  </tr>
  <tr>
   <td>DateofTermination
   </td>
   <td>Date the person was terminated, only populated if, in fact, Termd = 1
   </td>
   <td>Date
   </td>
  </tr>
  <tr>
   <td>TermReason
   </td>
   <td>A text reason / description for why the person was terminated
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>EmploymentStatus
   </td>
   <td>A description/category of the person’s employment status. Anyone currently working full time = Active
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>Department
   </td>
   <td>Name of the department that the person works in
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>ManagerName
   </td>
   <td>The name of the person’s immediate manager
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>ManagerID
   </td>
   <td>A unique identifier for each manager.
   </td>
   <td>Integer
   </td>
  </tr>
  <tr>
   <td>RecruitmentSource
   </td>
   <td>The name of the recruitment source where the employee was recruited from
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>PerformanceScore
   </td>
   <td>Performance Score text/category (Fully Meets, Partially Meets, PIP, Exceeds)
   </td>
   <td>Text
   </td>
  </tr>
  <tr>
   <td>EngagementSurvey
   </td>
   <td>Results from the last engagement survey, managed by our external partner
   </td>
   <td>Float
   </td>
  </tr>
  <tr>
   <td>EmpSatisfaction
   </td>
   <td>A basic satisfaction score between 1 and 5, as reported on a recent employee satisfaction survey
   </td>
   <td>Integer
   </td>
  </tr>
  <tr>
   <td>SpecialProjectsCount
   </td>
   <td>The number of special projects that the employee worked on during the last 6 months
   </td>
   <td>Integer
   </td>
  </tr>
  <tr>
   <td>LastPerformanceReviewDate
   </td>
   <td>The most recent date of the person’s last performance review.
   </td>
   <td>Date
   </td>
  </tr>
  <tr>
   <td>DaysLateLast30
   </td>
   <td>The number of times that the employee was late to work during the last 30 days
   </td>
   <td>Integer
   </td>
  </tr>
  <tr>
   <td>Absences
   </td>
   <td>The number of times the employee was absent from work.
   </td>
   <td>Integer
   </td>
  </tr>
</table>

