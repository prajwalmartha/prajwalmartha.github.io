\# CI/CD Pipeline Report



\## Student Information

\- Name: Sai Prajwal Martha

\- Date: November 16, 2025

\- Repository: https://github.com/prajwalmartha/prajwalmartha.github.io

\- Live URL: https://prajwalmartha.github.io

\# CI/CD Pipeline Report



\## Student Information

\- Name: Sai Prajwal Martha

\- Date: November 16, 2025

\- Repository: https://github.com/prajwalmartha/prajwalmartha.github.io

\- Live URL: https://prajwalmartha.github.io



---



\## Deployment History



GitHub Actions successfully deployed every update pushed to the \*\*main\*\* branch.  



---



\## Iteration Summary



\### 1. \*\*Initial Deployment\*\*

\- Commit: `b18a393fba7a5cd93ab8fd1c7d91f44a2e8d0c61`

\- Time to Deploy: ~2 minutes

\- Status: \*\*Success\*\*

\- Description: Added initial portfolio website (index.html, about.html, projects.html, style.css) and enabled GitHub Pages.



---



\### 2. \*\*Iteration 1: Trello Link in README\*\*

\- Commit: `c92df3e7e44556ab7b218a1db8fb4d02aa63b8c4`

\- Changes Made:

&nbsp; - Added a new `## Project Tracking` section in README.md

&nbsp; - Added Trello board link for project tracking

\- Deployment Time: ~2 minutes

\- Status: \*\*Success\*\*

\- Purpose: To integrate Agile project management with GitHub for CI/CD visibility.



---



\### 3. \*\*Iteration 2: Deploy Info + Website Personalization\*\*

\- Commit: `f31a8b77d9e4c5afab1234ea99d27b6ed8aee1b0`

\- Changes Made:

&nbsp; - Replaced \*\*Your Name\*\* → \*\*Sai Prajwal Martha\*\* across all pages

&nbsp; - Updated About page with:

&nbsp;   - University: Oklahoma City University

&nbsp;   - Graduation Year: 2026

&nbsp; - Added `deploy-info.json` with metadata:

&nbsp;   - version

&nbsp;   - lastUpdated

&nbsp;   - environment

&nbsp;   - author

&nbsp;   - buildTool

&nbsp;   - autoDeployEnabled

&nbsp; - Added a new project card in `projects.html` linking to deploy info

\- Deployment Time: ~2 minutes

\- Status: \*\*Success\*\*



---



\### 4. \*\*Iteration 3: Feature Branch Workflow\*\*

\- PR Number: \*\*#1\*\*

\- Feature Branch: `feature/add-contact`

\- Commit for Contact Page: `e4cb09a52d19e2f1170ab830ef98c4af73c01beb`

\- Deployment triggered by: \*\*Merging Pull Request into main\*\*

\- Changes Made:

&nbsp; - Added new `contact.html` page with:

&nbsp;   - Email  

&nbsp;   - GitHub link  

&nbsp;   - LinkedIn link  

&nbsp;   - Office hours

&nbsp; - Updated navigation links across all pages:

&nbsp;   - index.html  

&nbsp;   - about.html  

&nbsp;   - projects.html  

\- Deployment Time: ~2 minutes

\- Status: \*\*Success\*\*



---



\## CI/CD Understanding



\### What is CI/CD?

CI/CD (Continuous Integration and Continuous Deployment) is an automated software development practice where every code update is automatically built, tested, and deployed. CI integrates code frequently, while CD deploys the new version automatically without manual steps. This makes development faster, reduces errors, and ensures the live website is always up to date.



---



\## Benefits Observed

1\. \*\*Automatic Deployments\*\* — Every push triggered a new deployment without any manual work.

2\. \*\*Clear Build Logs\*\* — GitHub Actions provided full transparency for each deployment run.

3\. \*\*Safe Feature Development\*\* — Feature branch + pull requests allowed adding new pages without affecting the live site until approved.



---



\## Challenges Faced

\- Encountered a \*\*git push rejection\*\* due to remote changes; fixed by running `git pull origin main` first.

\- Needed to ensure GitHub Pages was correctly set to deploy from the \*\*main\*\* branch.

\- Learned how to work with feature branches, merge conflicts, and pull requests.



---



\## Real-World Application

CI/CD pipelines are used in professional software teams to automate testing and deployment. GitHub Pages offers a simple version of this, but the same workflow is used with tools like Jenkins, AWS CodePipeline, GitLab CI, and Azure DevOps.  

For large applications, CI/CD reduces human error, speeds up releases, improves collaboration, and ensures the product is always stable and deployable.



---



\## Screenshots Checklist



\- \[x] Initial website deployment screenshot  

\- \[x] GitHub Actions workflow runs (multiple green checks)  

\- \[x] Final website showing Home / About / Projects / Contact  





