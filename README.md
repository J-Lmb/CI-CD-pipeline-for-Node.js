# CI-CD-pipeline-for-Node.js
--> Create a CI/CD pipeline for Node.js with the Azure

To sets up a continuous integration (CI) and continuous delivery (CD) pipeline for your Node.js app, you will need a valid AZURE account.

1. Sign into the Microsoft Azure portal.
2. Choose the Create a resource icon in the left navigation bar,
3. Search for "DevOps project" and choose "Create"
4. Set up all by keeping default settings

The Azure DevOps project created a Git repository in your VSTS or GitHub account. 

Before going any further, clone this GitHub repo on your local drive:

git clone https://github.com/J-Lmb/CI-CD-pipeline-for-Node.js.git

5. Select the link for your master branch on your DevOps project dashboard.
6. This link will open a the newly created Git repository on Azure with a sample code for your project.
7. Delete the existing code and commit and push from your Git terminal the repo that you have previously cloned, to your AZURE git repository.
8. And once done, the script will automatically run in the background with an automatic build and release.
9. From your Dashboard, click on browse to visit the website or under the "Dev" section, click on release.
10. In the Build & Release hub, open the Releases tab. Select your release pipeline and, in the right pane, choose Edit to play around or see the existing pipelines and environments.

