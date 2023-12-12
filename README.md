# Macrosystems EDDIE Module 6: Understanding Uncertainty in Ecological Forecasts
  
This repository is a template for every student's Macrosystems EDDIE Module 6: Understanding Uncertainty in Ecological Forecasts. This is the fifth module of FREC 3044 Environmental Data Science, intended to introduce key concepts and skills to account for uncertainty in ecological forecasts.
  
## Assignment
  
All work for this assignment is in the `assignment` directory.  Code is contained in the `module6_assignment.Rmd` notebook, and final rendered output files (`module6_assignment.html` and associated files) are in the `assignment` directory as well. The general rubric you will be graded on is found in the `rubric.md` file. 
  
## Other files
  
Additionally this repository, and all student repositories, includes most of the files and folders found here:
  
- `README.md` a general overview of the repository in markdown format.  
- `lesson.md` a description of the assignment.
- `rubric.md` the rubric for how the module will be assessed.
- `.gitignore` an optional file, used to ignore common file types we don't want to accidentally commit to GitHub. Most projects should use this. 
- `*.Rproj` an R-Project file created by RStudio for its own configuration of the repo files. Some people prefer to `.gitignore` this file. It is optional for team repos to ignore or commit their own `<REPO-NAME>.Rproj` file. 
- `/module_admin` a folder containing data and code required for continued maintenance and development of the module. This folder is not needed to run the module. Students and instructors can `.gitignore` this folder. 

## How to run the module

Students will need [R](https://www.r-project.org/) and [RStudio](https://posit.co/download/rstudio-desktop/) downloaded on their computers to run this module. Student may access and run the code associated with this module in two ways:

### Option 1: Download a zip file of the code (easiest option)
1. Click the green "Code" button near the top of the repository page.
2. In the dropdown menu, select "Download ZIP".
3. Unzip the downloaded file; it will contain all the files you need to run the module. Use the instructions above to help you get started.

### Option 2: Create an R Project (advanced option)
1. If you don't already have one, [make a GitHub account](https://github.com/join).
2. Near the top of the repository page, click the "Fork" button to create your own copy of the module code repository in your GitHub account.
3. Open RStudio on your computer.
4. In the top right corner, click the "Project: (None)" button.
5. In the dropdown menu, click "New Project".
6. Select "Version Control".
7. Select "Git".
8. Go back to your internet browser. To retrieve the URL for this code repository, click the green "Code" button near the top of the repository page and copy the HTTPS link in the dropdown menu. 
9. Go back to RStudio. Paste the link into the "Repository URL" box. Type a name for your project into the "Project directory name" box. Select where you would like the project to be located on your computer in the "Create project as a subdirectory of" box.
10. Click "Create project".
11. RStudio should create a project which allows you to access and manipulate files locally.

### Committing and pushing changes back to GitHub
The advantage of accessing the module as an RProject via GitHub is that you now have version control, which means you can track (and revert if needed) your changes over time. You also have a copy of the project stored remotely (on GitHub) as a backup if your computer is lost or broken. However, in order to benefit from these advantages, you will need to commit and push any changes you make to the module files locally on your computer back to GitHub. To do this from RStudio:

1. Navigate to the "Git" pane in the top right panel of RStudio.
2. Click the check box next to each file you have changed.
3. Click "Commit".
4. In the top right corner of the pop-up window, type a brief but informative note to your future self documenting the changes you have made.
5. Under your message, click "Commit".
6. Once the changes are committed, click "Push".
7. RStudio will ask for your GitHub credentials to verify that you have rights to push changes to the remote code repository. Enter the email you used to create your GitHub account under 'username' as well as your GitHub token under 'password', then push your changes. Instructions for obtaining a token can be found [here](https://docs.github.com/en/enterprise-server@3.9/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens).
