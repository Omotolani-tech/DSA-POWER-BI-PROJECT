# DSA-POWER-BI-PROJECT
## Project Topic: Palmora Group HR Analysis

### Project Overview
This Data Analysis project aims to gives insights on the issues of Gender inquality in the 3 regions of the organisation. By analysing the given parameters in the data received, i seek to gather enough insights to make reasonable decisions and come up with recommndation to put an end to gender inequality in the organisation.

### Data Sources
The primary source of Data used here is provided by DSA the Incubator Hub

### Tools Used
- **Power BI** : For data Visualization and Dashboard creation
- **Excel** : For initial Cleaning and Preparation
- **Power Query**: For Data transformation

### Data Cleaning and Preparation
- Assigned Generic Gender to employees that refused to disclosed their gender
- Removed Department and Salary that are Null which reduced the rows from 1016 to 946
- Merged the bonus mapping table and the employee data table
- Created calculated columns in power query for:
   - Annual Bonus
   - Total Pay
   - Salary Band

### Exploratory Data Analysis
  EDA involved the exploring of the Data to answer some questions about the Data such as;
  - What is the gender distribution in the organisation
  - what is the ratings based on gender
  - Is there a gender pay gap
  - Does the organsation pay employees the minimum salary

### Data Analysis
#### Statistics
- Total Employees: 946
- Total Salary paid: $71.92M
- Average Salary: $73.70k

## Key Insights by Dashboard Section

![Power bi project 1](https://github.com/user-attachments/assets/b4332e7c-138e-4550-b3c7-e0b964af6ad7)

- Demographics: Males are more than females with difference of 24 in the organisation
- Department:
   - The **Product Management** Department leads with highest employees
   - The **Legal** Department has the most males
   - The **Services** Department has the most females
- Ratings:
   - A higher number of males receive “Average” ratings than females.
   - Females have slightly more “Good” and “Very Good” ratings, but fewer "Not Rated" entries, suggesting slightly better recognition/performance levels.

  ![Power bi project 2](https://github.com/user-attachments/assets/a61f784c-95fc-4e8a-916c-37ed93d026e1)

 - Regional Salary Gap:
     - Kaduna has the highest pay total (27M), followed by Abuja (25M) and Lagos (20M).
     - Kaduna and Abuja also have the most employees below the minimum salary: Kaduna: 250 employees, Abuja: 238 employees, Lagos: 166 employees.
Suggests potential inequality or underpayment issues affecting larger employee groups in these regions.


## Recommendation
- Enhance Data Collection
   - Reduce “N/A” or missing gender values by encouraging voluntary disclosures.
   - This will allow more precise analytics and informed equity actions.
- Conduct Regular Pay Audits
   - Implement transparent gender pay audits across all departments and regions.
   - Adjust salaries to reflect equal pay for equal performance, roles, and experience
- Region-Specific Compensation Strategy
   - Investigate why Kaduna and Abuja have the most underpaid employees despite high total salaries.
   - Review whether location-based bias or cost-of-living misalignment contributes to the inequality.
- Create Gender Diversity Targets
   - Set inclusion goals for departments with skewed gender distributions, especially in Legal, Product Management, and Sales.
   - Encourage female recruitment in male-dominated units and vice versa.

  
