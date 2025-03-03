# Project Name

## Introduction
Job hunting is a tedious process due to endless searching through job boards or preparing their resume/cover letter and interview. <br>
It is equally exhausting for the employer as well to filter through countless job applications, scheduling arranging interviews etc. <br>
This project aims to create an all in one platform using LLMs that provides AI agents/tools that can speed up the process for both job seekers and employers.  <br>
The job application process involves different platforms for different steps and some steps are completed manually. Hence this make the process cumbersome and time consuming.  <br>

## Job Application Process
Here are the current job application process for both job seekers and employers view

Job Application Process (Job Seeker)

| Steps                	| How                                                                                                   	| Pain Points 
|---------------------	|-------------------------------------------------------------------------------------------------------	| -------- | 
| Resume/Cover letter 	| Google Search or Use Chatgpt for templates.  Manually fill up the template                              | Time consuming to search and input data. Not sure which template is correct as too many options.|  
| Job Application     	| Job boards / Recruitment agencies & direct to companies / Web extension to fill up fields 	            | Not sure which jobs are suitable or which pathway to take. Too many job boards to apply and keep track of applications. Excel sheet is needed to keep track of all applications offline  | 
| Interview prep      	| Mock Interview platform (Mock AI) or Peer to Peer Interview platform (Pramp). Research company / job role| Tedious to research company history,culture and job role, most common interview questions. Mock Interview platforms may use cookie cutter questions and may not be relevant. Tedious to use another platform        | 
| Tech interview prep 	| Practicing leetcode questions. Researching most common questions by company                            	| Tedious to research common questions on the web. Grinding leetcode is time consuming and may not be helpful | 
| Liaise with HR      	| Communicate via email to ask questions or reschedule                                                  	| Reply is not instant and may take 1-2 days to receive response         | 
| Take tech tests     	| Live coding interview.  HackerRank platform                                                            	| Nil         | 

Job Application Process (Employer)

| Steps                	| How                                                                                                   	| Pain Points
|---------------------	|-------------------------------------------------------------------------------------------------------	|------------ |             
| Job Posting	          | Post Jobs on intranet, job boards or recruiters or company website                                      | Time consuming and tedious due to many job boards to post and edit |  
| Application Review    | Retain top x applicants on platform (Workday/Lever) and reject the rest. Manually review cv and resume  | Time consuming and tedious. Rating of candidates by platform may not reflect true potential of candidate.               |
| Schedule Interview    | Schedule interview date and time with job seeker. Liaise with interview panels to get avaliable dates. Zoom / Google Meet platform | Tedious to schedule virutal meeting as there may be changes in both interviewers and interviewees |
| Send test             | Send links to job seeker to attempt psychometric / coding test on platforms (HackerRank/TestGorilla)    | Scores may not reflect actual skills due to usage of AI. Reviewing the videos/test results is done manually and time consuming. Using an external platform is tedious as procurement to setup accounts is time consuming |
| Liaise with Candidate | Communicate via email to ask questions or reschedule                                                    | Nil |
                                                    
## Platform Goals
- Reduce the time taken to do the tasks manually
- Enable users & employers to use just one platform instead of multiple software from recruiting to job offer process
- Utilize new technologies to create a better product than existing products on the market 

## Functional Requirements
Job Seekers
- User Authentication: Users can sign up/login/reset their account on the platform
- Job listings: Listings are web-scraped from companies itself. The companies will be Singapore fin-tech companies
- Jobs Tracker: Users will be able to extract job application details from hyperlink and save them on platform or export as csv. This will be useful for users to track all their job applications on one page 
- Jobs Application Filler: Input details from resume for job applications without manually input
- Jobs Application Reviewer: Score will be generated when comparing their resume and job description. Users need not apply for the role if the score is low
- Resume Helper: Users will upload their resume / cover letter for review. The tool will explain on how to improve and what points to improve.
- Test Helper: Users will be able to practice common interview questions and leetcode questions and psychometric test questions. The tool will review and comment on what to improve
- Interview Helper: Users will be able to practice mock interview sessions or technical interview questions with a real person

Employers
- User Authentication: Employers can sign up/login/reset their account on the platform
- AI Agents: Create AI-Agents that handle each of the functions below
- Schedule interviews: Schedule interviews with panel and interviewees
- Job listings: Able to post job listings on their website and review candidates applications 
- Test Checker: Review or Check that candidate is not using any AI-tools to answer the questions
- Job Application Chatbot: Answer questions relevant to the job application or asked by job seeker

## Non-Functional Requirements
- Security
- Performance

## Technical Requirements
- Backend: Django
- Frontend: ??
- Database: SQL
- APIS: ??

## Architecture Overview
- Placeholder

## Tools 
- Job Tracker: It allows users to save applied job appication details to track their all applications.

## Design 
- Job Seekers Platform
![job_seeker_sketch](https://github.com/user-attachments/assets/d941f092-da07-45df-86d0-8a8207d0a293)

- Employers Platform
![employers_sketch](https://github.com/user-attachments/assets/836b981f-61db-477a-b808-a4809b6861b7)


