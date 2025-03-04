# final-cloud-app-with-database
An online course app ('Final Project' in [Django Application Development with SQL and Databases](https://www.coursera.org/learn/developing-applications-with-sql-databases-and-django) course, part of [IBM Full Stack Software Developer Professional Certificate](https://www.coursera.org/professional-certificates/ibm-full-stack-cloud-developer)).

# What does the project do?
## Overview
Using the skills I learned in the 'Django Application Development with SQL and Databases' course, I planned and implemented improvements in an application given its boilerplate code; these improvements include:

1. Create Question, Choice, and Submission models.
2. Create a new course object with exam-related models using the admin site.
3. Update the course details template to show questions and choices.
4. Create a new exam result template to show the result of the submission.
5. Create a new exam result submission view.
6. Create a new view to display and evaluate exam result.

## Review criteria
1. Implement changes in Question, Choice and Submission model.
2. Register models.
3. Get admin site working.
4. Design Course Details section.
5. Wite function-based views.
6. Write URLs for access.
7. Show final result.

# Why is the project useful?
The project and [the course's Hands-on Labs](https://gist.github.com/nathandeflavis/37e02781c7110e96ac5f50defceab7dd) are opportunities to put my Django and SQL skills into practice.

# How can users can get started with the project?
You can run the application in [an IBM Skills Network lab environment](https://skills.network).

## Steps
1. Open a terminal window.
2. Clone this repository: `[ ! -d 'final-cloud-app-with-database' ] && git clone https://github.com/nathandeflavis/final-cloud-app-with-database.git`
3. Change to the directory **final-cloud-app-with-database**: `cd final-cloud-app-with-database`
4. Set up a virtual environment:
`pip install --upgrade distro-info`
`pip3 install --upgrade pip==23.2.1`
`pip install virtualenv`
`virtualenv djangoenv`
`source djangoenv/bin/activate` 
5. Set up the Python runtime: `pip install -U -r requirements.txt`
6. Create the initial migrations and generate the database schema:
`python3 manage.py makemigrations`
`python3 manage.py migrate`
7. Create an admin user following the given prompts: `python3 manage.py createsuperuser`
8. Run the server: `python3 manage.py runserver`

The base URL is: http://localhost:8000

9. To access the admin interface, visit: \<base URL\>/admin
10. To access the end-user interface, visit: \<base URL\>/onlinecourse
11. To stop the server, press Ctrl-C.

# Where can users can get help with the project?
Users can contact the project's maintainers and contributors for help.

# Who maintains and contributes to the project?
@nathandeflavis

README adapted from [GitHub Docs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes).
