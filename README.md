# Automating Kubernetes With Jenkins
## Project Description:
1. Create a job chain of Job 1, Job 2, Job 3 and Job 4 using build pipeline plugin in Jenkins
2. Job 1: Pull the Github repo automatically when some developers push the repo to Github.
3. Job 2 :
By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code on top of Kubernetes( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )
Expose your pod so that testing team could perform the testing on the pod
Make the data to remain persistent ( If server collects some data like logs, other user information )
4. Job 3: Test your app if it is working or not.
5. Job 4: if the app is not working, then send email to the developer with error messages and redeploy the application after code is being edited by the developer
## Pre-requisites for the practical :
Git Installed on Your System

A Github Repository should be there to commit the code or cloned in the local system.

Create a post-commit hook in .git/hooks folder in Git for git push so that if a developer commits code then it automatically pushes to Github.

Configure Kubernetes in your Rhel OS.

Configure Jenkins in your Rhel OS.
