# glarimy-quiz

REST API for Glarimy Quiz

https://github.com/glarimy/cloud-services/ with MySQL

Models

Employee
ID
Name
Password
Role
QuizList
	QuizID
	Score

Subject
ID
Name

Quiz
ID
Date
From
To
Questions
Employees
	EmployeeID
	Score

HR

Add Employee
POST /employee

Remove Employee
DELETE /employee/{eid}

List Employees
GET /employee

View Employee
GET /employee/{eid}

Update Employee
PUT /employee/{eid}

Add Subject
POST /subject

List Subjects
GET /subject

Schedule Quiz
POST /quiz

Remove Quiz
DELETE /quiz/{qid}

List Quizes
GET /quiz

View Quiz
GET /quiz/{qid}

View Quiz Results
GET /quiz/{qid}/results

View Employee Results
GET /employee/{eid}/results

SME

Add Question
POST /question

List Questions
GET /question

Update Question
PUT /question/{qnid}

View Question
GET /question/{qnid}


Employee

List Quizes
GET /quiz

Take Quiz
GET /quiz/{qid}

Submit Quiz
POST /quiz/{qid}/answers

View Quiz Results
GET /quiz/{qid}/results

View All Results
GET /quiz/results

