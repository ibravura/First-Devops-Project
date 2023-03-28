# First-Devops-Project
#Development: Developers write code in Java using their favorite IDE and push changes to Git for version control.
#	Continuous Integration: Jenkins pulls the latest changes from Git and compiles the code using Maven. It runs unit tests and checks for code style and quality using SonarQube. If the build passes, Jenkins creates an artifact (a WAR file) and deploys it to Nexus.
#	Continuous Delivery: Jenkins deploys the artifact from Nexus to a staging environment using Tomcat. It runs integration tests and smoke tests to ensure the application is functioning correctly.
# User Acceptance Testing (UAT): Once the staging environment is validated, Jenkins deploys the same artifact to the UAT environment for user acceptance testing.
# Continuous Deployment: If the UAT passes, Jenkins deploys the same artifact to the production environment automatically.
# Infrastructure as Code: All infrastructure components, including Tomcat, Nexus, and SonarQube, are managed using scripts written in Bash and run on Linux servers.
