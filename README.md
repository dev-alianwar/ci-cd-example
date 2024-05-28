# cicd-tests-dev


The required for this task is to streamline release management and deployment processes using CircleCI and GitHub Actions. The goal is to adapt and implement a GitFlow branching strategy to enhance development lifecycle.


Implement GitFlow Branching Strategy:



Set up and configure the branching model to support development and release cycle.
Ensure that developers can create feature/fixes/hotfixes branches that automatically generate release pr/mr (associate it with the upcoming release) and initiate a release branch. (the idea is to promote isolation and prevent dead branches)
Automate the synchronization between the release branches and the main and development branches.



CircleCI and GitHub Actions Integration:
Configure CircleCI and GitHub Actions for continuous integration and continuous deployment.
Create automated workflows for merging pull requests to development and release branches simultaneously.
Implement automatic versioning to increment release numbers seamlessly. i.e. nodejs project auto increment the build version. Also, manage QA tagging build and properly construct the build version i.e. major, minor and so on.