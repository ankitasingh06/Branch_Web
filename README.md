# Branch_Web

This practical implementation is done for the project  to complete automation with DevOps with the help of Jenkins.

Here with the help of git software, I created  local repository, and pushed it in the public Centralised version system (CVCS) i.e. "github".

Here, we have two branches ,one is master branch and one is dev1 branch.

Simple html webpage(a1.html) is to be deployed, automatically with the Jenkins -----> jobs.

Some basic idea of Jenkins jobs======>>>>
JOB#1
If Developer push to dev1 branch then Jenkins will fetch from dev1 and deploy on Testing environment.

JOB#2
If Developer push to master branch then Jenkins will fetch from master and deploy on Production environment.
 Note :- 
both Production environment and Testing environment are on different docker containers.

JOB#3
Manually the QA team will check (test) for the website running in dev-docker environment. If it is running fine then Jenkins will merge the dev1 branch to master branch and trigger #job 2

With the help of git/github + Jenkins + docker containers, This project is completed.

Here is my linkedin Article link = https://www.linkedin.com/feed/update/urn:li:activity:6664215386822709249/

Go through this link for proper understanding.
