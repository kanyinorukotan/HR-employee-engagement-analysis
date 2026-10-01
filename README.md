# HR Employee Engagement Analysis

## Project Overview

This project analyzes employee engagement survey responses using Microsoft
Power BI and Excel.

The purpose of the analysis was to measure employee engagement, identify
the strongest and weakest workplace factors, compare results across
departments and job roles, and recommend actions that could improve the
employee experience.

The project analyzes 14,710 survey answers across 21 departments and
10 employee engagement questions.

## Business Questions

The analysis was designed to answer the following questions:

1. What percentage of survey responses are favorable?
2. What is the overall employee engagement score?
3. Which workplace factors receive the highest ratings?
4. Which workplace factors receive the lowest ratings?
5. How does engagement differ across job roles?
6. Which departments have the highest and lowest favorable scores?
7. What actions could improve employee engagement?
8. Are there any data-quality limitations that affect the analysis?

## Tools and Skills

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX
- Data cleaning
- Data transformation
- Survey data analysis
- Data modeling
- Data visualization
- Dashboard development
- Business analysis
- Data storytelling

## Dataset

The dataset contains employee survey answers across:

- 21 departments
- 10 employee engagement questions
- Five role categories
- 14,710 survey-answer records

Each row represents one answer to one survey question rather than one
individual employee.

The response scale includes:

- Strongly Agree
- Agree
- Disagree
- Strongly Disagree
- Not Applicable
- No Response

## Data Preparation

The following steps were completed before building the dashboard:

1. Reviewed survey responses for incomplete and missing values.
2. Corrected data types in Power Query.
3. Standardized question and response categories.
4. Distinguished valid answers from Not Applicable and No Response records.
5. Created a role category from the Director, Manager, Supervisor, and
   Staff fields.
6. Created measures for favorable and unfavorable survey responses.
7. Calculated the overall average survey score.
8. Calculated completion and non-response rates.
9. Compared engagement results by department, role, and survey question.
10. Validated the dashboard measures against the source data.

## Key Performance Indicators

- **Survey answers:** 14,710
- **Departments:** 21
- **Survey questions:** 10
- **Favorable responses:** 77.3%
- **Unfavorable responses:** 22.7%
- **Average score:** 3.07 out of 4
- **Completion rate:** 99.1%

## Key Insights

### 1. Overall engagement was positive

The survey recorded a 77.3% favorable response rate and an average score
of 3.07 out of 4.

This indicates that most valid answers were Agree or Strongly Agree.
However, approximately one in four valid answers was unfavorable.

### 2. Employees understood their responsibilities

The highest-rated statement was “I know what is expected of me at work,”
with a 92.6% favorable score.

The result suggests that job expectations and responsibilities were
generally communicated clearly.

### 3. Supervisor support was a major strength

Approximately 86.4% of responses to the supervisor-care question were
favorable.

This suggests that most employees believed their direct supervisor cared
about them.

### 4. Employee recognition was a weak area

Only 65.2% of answers to the recent-recognition question were favorable.

This indicates that a significant group of employees did not feel
regularly recognized or praised for good work.

### 5. Workplace connection was the weakest engagement factor

The statement relating to having a best friend at work received a
52.4% favorable score, the lowest result among the ten questions.

This area may indicate weaknesses in employee connection, collaboration,
mentoring, or team belonging.

### 6. Engagement decreased lower in the role hierarchy

Directors recorded an 86.6% favorable score, compared with 73.9% for
Staff, representing a gap of approximately 12.7 percentage points.

The largest difference involved recent recognition. Directors recorded
92.9%, while Staff recorded 59.2%.

### 7. The Sheriff's Department was the main departmental outlier

The Sheriff's Department recorded a 51.5% favorable result, approximately
26 percentage points below the overall organizational score.

Five engagement questions in the department received favorable scores
below 50%, including recognition, overall satisfaction, learning and
growth, accountability, and connection to the organizational mission.

### 8. Some departments achieved very strong results

The Communications Office and Emergency Management both recorded favorable
scores above 90%.

These departments may contain management or engagement practices that
could be studied and adapted by other departments.

## Recommendations

1. **Build a consistent recognition programme**

   Encourage managers to provide regular and specific recognition.
   Recognition efforts should initially prioritize frontline staff.

2. **Investigate the Sheriff's Department results**

   Conduct listening sessions, focus groups, or follow-up surveys to
   understand the reasons for its low engagement scores before selecting
   an intervention.

3. **Strengthen employee connection**

   Introduce mentoring, peer-support, team-building, and cross-departmental
   collaboration opportunities.

4. **Improve job-role data collection**

   Make job-role selection a required field in future surveys to improve
   the reliability of comparisons across organizational levels.

5. **Learn from high-performing departments**

   Examine management and communication practices in the Communications
   Office and Emergency Management and determine whether they can be
   adapted elsewhere.

## Data Limitations

- Each row represents one survey answer, not one employee.
- Not Applicable and No Response answers were excluded from favorable,
  unfavorable, and average-score calculations.
- Approximately 72% of answers do not have a recorded job role, so role
  comparisons represent only a partial view.
- Small departments have fewer answers, which can cause their percentages
  to change considerably based on a small number of responses.
- The analysis identifies patterns and associations, but it does not prove
  the causes of employee engagement outcomes.

## About the Analyst

I am Kanyin David Orukotan, an entry-level data analyst developing skills
in Excel, SQL, Power BI, Power Query, DAX, data cleaning, data
visualization, business analysis, and data storytelling.
