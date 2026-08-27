Jenkins:

Jenkins is a open-source continuous integration tool. It is cross-platform tool that supports different OS like Windows, Linux and Mac which are popular OS.

Background programming language for Jenkins is Java

* Important port numbers 
  - Nexus port is 8081
  - Tomcat port is 8080
  - Sonarqube port is 9000
  - Jenkins port is 8080

Koushke Kawaguchi is developer of Jenkins (formerly Hudson)

Advantages of Jenkins:
1. OpenSource project with good community support
2. Easy to install, simple configuration through web-based UI, that speeds deployment process
3. Have more than 2000+ plugins. If plugin not available, just code it up and share with the community
4. Good documentation and support articles

Continuous integration: Continuous integration is the process of automating the build and testing of code every time a team member commits changes to version control/git. 
Another definition: CI is the development practise where developers integrate their code into shared remote repostory frequently, preferably severla times a day. Each integration is verified by automatic build that get triggered to check integration errors as quickly as possible.

CI Advantages:
- Immediately able to detect bug
- Less merge conflict issues
- Deploy application at any given point of time
- You can send notification through Jenkins, will get immediate feedback

CD/ Continuous Delivery not equal to Continuous Deployment
CI Part:
Github code + maven build tool + Sonarqube report generated + pushed artifactory to Nexus

CD Part: 
Project application code + 

2 Types of Projects:
In-house or External projects: Like company payroll, HR sites, and other inhouse projects -> Do continuous deployment
Continuous Delivery is manual - 

Continuous Deployment - Fully automated - In-house projects
Continuous Delivery - Automated CI + Manual Delivery after approvals - External Projects

===

In got invloved in multiple projects and for internal projects we used CD(deployment) and for external projects used CD(Delivery)

===

What Jenkins can do:
- It will integrate easily with multiple version control systems like, github, gitlab
- You can generate unit testcases
- Send notifications to customers via Teams and Slack

Cloudbee Jenkins is Enterprise version - Paid version

Other CI/CD tools
Jenknins
CloudBees Jenkins
Bamboo
Cruise Control
Travis CI
Circle CI
itlab CI
Teamcity

Other than Jenkins - what tool you know - Github actions


