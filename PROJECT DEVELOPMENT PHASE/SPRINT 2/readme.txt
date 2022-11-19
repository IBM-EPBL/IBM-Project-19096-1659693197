TEAM ID :PNT2022TMID07064

PROJECT:Skill and job recommender

TEAM LEADER:HARISH KUMAR

TEAM MEMBERS:DEEPAK ,GAUTHAM ,HEINRICH


SPRINT -2

*. Created an UI and local database to store the information of Job Seeker

*. He can create an account in this platform and he can share his projects in this platform where recruiters can have a look on it

*. He can Search the Job by typing the Skillset that he acquires and it displays all the jobs based on the search keyword

*. State of the user is managed by using JSON WEB TOKEN(JWT)

*. He can edit his feeds 

*. He can edit his profile section 

Routes:

"/user/signin"-sigin user

"/user/signup"-signup user

"/user/profile/editprofile"- to edit the profile which includes Education,name,about me ,skills etc

"/user/jobs"- to view all the jobs posted on the platform

"/user/view_application"-to view a particular file

"/user/newsfeed"-to view all the projects posted by the job seekers

"/user/feed/new"-to create an feed includes the project title and description

"/user/search" -to search the skill which returns the result based on the skillset

"/user/logout" -to logout from the platform





TO RUN THE PROGRAM

1.RUN THE DATABASE LOCALLY 

2.RUN THE APP (linux) - "python3 app.py"

3.RUN THE APP (windows) - "python app.py" 