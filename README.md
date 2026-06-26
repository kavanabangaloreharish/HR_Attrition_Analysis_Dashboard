# HR Attrition Analysis Dashboard

## Objective
Analyze IBM's HR employee dataset to understand why employees leave, which departments are most affected, and how salary and experience relate to attrition and translate those findings into actionable business recommendations.

## Tools Used
Excel, Power BI

## Dataset
IBM HR Analytics Employee Attrition & Performance (Kaggle) 1,470 employees, 35 attributes including department, salary, tenure, satisfaction scores, and attrition status.

## Business Questions
1. Why do employees leave?
2. Which departments have the highest attrition?
3. Does salary affect attrition?
4. Does experience/tenure affect retention?
5. Do age and gender play a role in attrition?

## Key Insights

### Attrition by Department
- Sales has the highest attrition rate at 20.6%, followed by HR at 19.1%, and R&D the lowest at 13.8%
- Sales is losing roughly 1 in 5 employees — worth investigating targets, workload, or compensation structure specific to this department

### Salary vs Attrition
- Employees who left earned an average of $4,787/month, compared to $6,833/month for those who stayed — roughly 30% less
- Salary is a clear factor, though it may be tied to department and seniority rather than acting alone

### Experience & Tenure vs Attrition
- Employees who left had less experience both at the company (5.1 years vs 7.4 years) and in total career experience (8.2 years vs 11.9 years)
- Attrition is concentrated in early-career employees, not specifically people new to the company but experienced elsewhere

### Satisfaction Factors
- Every satisfaction metric (Job Satisfaction, Work-Life Balance, Environment Satisfaction) is lower for employees who left
- No single factor stands out — the pattern suggests overall dissatisfaction, not one fixable issue, is driving attrition

### Age & Gender
- Attrition is heavily concentrated among employees in their 20s, dropping sharply for employees over 30
- Gender is fairly balanced among leavers (53% male vs 47% female), suggesting it is not a meaningful driver of attrition

## Business Recommendations
- **Compensation**: Review pay bands for junior/entry-level roles, especially in Sales, where both attrition and the salary gap are highest
- **Sales department**: Conduct exit interviews specifically within Sales to identify whether targets, commission structure, or management style are driving turnover
- **Early-career retention**: Strengthen onboarding, mentorship, and growth paths for employees in their 20s, where attrition risk is highest
- **Retention check-ins**: Introduce a structured check-in at the 1-2 year mark, since attrition tends to occur well before the average 7-year tenure
- **Gender**: No targeted intervention needed — attrition is balanced across gender, so focus should remain on salary, department, and early-career factors

## Power BI Dashboard
Built an interactive dashboard featuring:
- KPI cards: Total Employees, Avg Salary, Avg Tenure, Attrition Rate
- Attrition rate by department
- Attrition rate by age group (binned)
- Attrition rate by gender
- Average salary comparison (stayed vs left)
- Written business recommendations embedded directly in the dashboard

## Repository Structure
