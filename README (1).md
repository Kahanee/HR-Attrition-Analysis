# Navigating the Talent Drain: Analyzing Employee Attrition Factors and Crafting Solution

### Explore Attrition Trends and Strategies for Retaining Talents, Enhance Employee Satisfaction and Productivity

[Link to dataset](https://www.kaggle.com/datasets/rohitsahoo/employee?select=train.csv)

![Screenshot of dashboard](https://imgbox.io/ib/LNHBeDLy0N.png)
![Screenshot of dashboard](https://imgbox.io/ib/idrxpbwdAc.png)
![Screenshot of dashboard](https://imgbox.io/ib/3EKuj6QPkN.png)
![Screenshot of dashboard](https://imgbox.io/ib/8Wte2FzHSr.png)
![Screenshot of dashboard](https://imgbox.io/ib/ctwEwvTcK1.png)
![Screenshot of dashboard](https://imgbox.io/ib/cnbwBvUvjf.png)



#### Final Table Relationship Modal View after Transformation:

![Screenshot Table Relationship Model ](https://imgbox.io/ib/Mi0p94FHrm.png)



##### Description of dataset:
IBM employee dataset with close to 1500 rows and 35 columns:
To analyze the factors that contribute to employee attrition, organizations can identify ways to reduce turnover and save costs associated with recruiting and training new employees.

###### Importance of Employee Attrition Analysis:
Cost savings:

- Employee turnover can be expensive for an organization. By analyzing the factors that contribute to employee attrition, organizations can identify ways to reduce turnover and save costs associated with recruiting and training new employees.

Employee satisfaction: 

- Analyzing factors that contribute to employee satisfaction can help organizations identify areas for improvement in their work environment, which can lead to higher employee satisfaction and better performance.

Performance management:
 - Analyzing performance-related factors such as training, job satisfaction, and work-life balance can help organizations better manage their employee performance and optimize productivity.
 
Talent retention: 

- By identifying the factors that contribute to employee retention, organizations can take proactive measures to retain their top talent and avoid losing valuable employees to competitors.

Strategic decision-making: 

- By analyzing employee data, organizations can make informed decisions about HR policies, benefits, and training programs that can improve overall employee satisfaction and retention.

###### Possible Solutions for the given attrition scenarios:

Employment Duration: Most attrition occurs during the first few years of employment.

- Solution: Implement robust onboarding programs to ensure new employees feel supported and engaged from the start. Provide mentorship or buddy programs to help new employees acclimate to the company culture and work environment. Conduct periodic check-ins and performance reviews to address any concerns and provide opportunities for growth and development.

Age: Younger workers have higher turnover compared to older workers.

- Solution: Implement mentorship programs pairing younger employees with experienced mentors to provide guidance and support. Offer opportunities for career growth and professional development to engage  and retain younger talent.

Education: Employees with lower education have higher turnover.

- Solution: Offer educational and skill development programs to employees, providing opportunities for them to enhance their knowledge and qualifications. Create a supportive environment that values continuous learning and provides resources for further education.

Marital Status: Employees who are Single have higher attrition.

- Solution: Implement employee engagement initiatives that focus on work-life balance, social activities, and opportunities for team-building to create a supportive work environment for single employees. Consider offering benefits or programs that cater to the needs of single employees, such as flexible scheduling or wellness initiatives.

Distance from Workplace: Employees who live further from the workplace have higher attrition.

 - Solution: Explore options for remote work or flexible work arrangements to reduce commuting stress. Consider offering transportation benefits or subsidies to employees who live far from the workplace. Improve communication and collaboration tools to facilitate remote work and maintain strong connections with remote employees.

Job Level: Employees in lower job levels have the highest attrition.

- Solution: Create clear career development paths and opportunities for advancement within the organization. Provide regular performance feedback, recognition programs, and skill-building training for employees at lower levels. Offer competitive compensation packages that align with market standards to incentivize talent retention.

Department: Research and development department has the highest attrition.

- Solution: Conduct department-specific assessments to identify underlying issues causing high attrition. Address any work-related challenges, such as workload distribution, communication gaps, or lack of growth opportunities. Foster a culture of innovation, collaboration, and recognition within the department to enhance employee engagement and job satisfaction.

Job Role: Laboratory technicians have the highest attrition.

- Solution: Conduct exit interviews or surveys to understand the reasons for high attrition among laboratory technicians. Identify any concerns regarding workload, work environment, career growth, or job satisfaction. Provide opportunities for professional development and advancement within the laboratory technician role.


Current Manager: Employees who work with their current manager resign within one year

- Solution: Provide managerial training and support to improve leadership skills. Foster open and transparent communication between managers and employees. Encourage regular feedback and performance discussions. Address any conflicts or concerns promptly and create an environment of trust and support.

Overall, it is crucial to address the underlying factors contributing to attrition in each scenario by implementing targeted strategies and initiatives. Regular evaluation and monitoring of these solutions can help organizations improve employee retention and create a more positive and engaging work environment.

#### Data Cleaning and Transformation done using Power Query 
##### Including but not limited to :

###### Transform the raw data into proper column and rows
Original Raw Dataset :
![Screenshot Raw Data ](https://imgbox.io/ib/FLjytv9AFj.png)

Dataset after Power Query transformation
![ Screenshot Dataset transformation](https://imgbox.io/ib/Xbji27hLBM.png)
![Screenshot Dataset after Transformation](https://imgbox.io/ib/C4bdjSaEOF.png)

Creation of Customize Conditional Column -Create Conditional Column For Age,Department, Business Travel, Job Role, Educational field, Distance From Home,Total Working Year by grouping the values into ranges for better analysis.
![ Screenshot Custom Column creation](https://imgbox.io/ib/mZ4q000d8x.png)

Merge Queries
![ Screenshot Merge queries](https://imgbox.io/ib/H7IFx95y0Q.png)

Some of the Applied steps in Power Query for Data Transformation
![ Screenshot Applied steps](https://imgbox.io/ib/t2XW1ndRs0.png)

Final Data tables created and transformed from 1 single table
![ Screenshot Tables](https://imgbox.io/ib/Gpo6NNsB7O.png)

Sample DAX measures created in Power BI
![ Screenshot Measures](https://imgbox.io/ib/MpHJRx1T2p.png)

![ Screenshot Measures ](https://imgbox.io/ib/hA9RnJTNtL.png)

![ Screenshot Measures](https://imgbox.io/ib/Tx2zd8REeX.png)

All the Measures created in Power BI
![ Screenshot Measures](https://imgbox.io/ib/Piz97QHMmt.png)

Navigation page creation in Power BI
![ Screenshot Navigation ](https://imgbox.io/ib/pN06d273hh.png)

Drill-Through creation in Power BI
![ Screenshot Drill through](https://imgbox.io/ib/t0pEUCCAJl.png)

The Analysis is performed after full Data cleaning and Transformatio.

My LinkedIn
Sailaja Begum