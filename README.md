# Operation-Analytics-and-Investigating-Metric-Spike

Description:
Operation Analytics is the analysis done for the complete end to end operations of a company. With the help of this, the company then finds the areas on which it must improve upon. You work closely with the ops team, support team, marketing team, etc and help them derive insights out of the data they collect.

Being one of the most important parts of a company, this kind of analysis is further used to predict the overall growth or decline of a company’s fortune. It means better automation, better understanding between cross-functional teams, and more effective workflows.

Investigating metric spike is also an important part of operation analytics as being a Data Analyst you must be able to understand or make other teams understand questions like- Why is there a dip in daily engagement? Why have sales taken a dip? Etc. Questions like these must be answered daily and for that its very important to investigate metric spike.

You are working for a company like Microsoft designated as Data Analyst Lead and is provided with different data sets, tables from which you must derive certain insights out of it and answer the questions asked by different departments.

Case Study 1 (Job Data)
Below is the structure of the table with the definition of each column
Table-1: job_data
job_id: unique identifier of jobs
actor_id: unique identifier of actor
event: decision/skip/transfer
language: language of the content
time_spent: time spent to review the job in seconds
org: organization of the actor
ds: date in the yyyy/mm/dd format. It is stored in the form of text and we use presto to run. no need for date function

OUTCOMES OF case study 1:
1) number of jobs reviewed per hour per day for November 2020?
2) 7 day rolling average of throughput
3) percentage share of each language in the last 30 days?


Case Study 2 (Investigating metric spike)
The structure of the table with the definition of each column

Table-1: users
This table includes one row per user, with descriptive information about that user’s account.
Table-2: events
This table includes one row per event, where an event is an action that a user has taken. These events include login events, messaging events, search events, events logged as users progress through a signup funnel, events around received emails.
Table-3: email_events
This table contains events specific to the sending of emails. It is similar in structure to the events table above.

OUTCOMES OF case study 2:
1) weekly user engagement
2) user growth for product
3) weekly retention of users-sign up cohort
4) weekly engagement per device
5) email engagement metrics

Project done in SQL on MySQL Workbench.
