Task 1 - Jenkins Freestyle with Docker (Task1-Repo)

This repo contains configuration for a Jenkins Freestyle Job that verifies Docker installation and runs basic Docker commands.

Files:

README.md

logs/build_output.txt

screenshots/job_success.png

Steps performed:

Configured Jenkins with correct Docker path (/usr/local/bin/docker) in environment variables.

Created a Freestyle Job with a build step → Execute Shell:

docker --version
docker ps


Ran the job and verified Docker commands execute successfully.

Output:

Job built successfully inside Jenkins.

Docker version and running containers list displayed in console output.
