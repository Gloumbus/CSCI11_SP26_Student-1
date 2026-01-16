# Doing Your Homework

## To get the latest assignment, in the CSCI11_Instructor folder
1. In the Terminal:
    1. change directory (`cd`) to the **CSCI11_Sp26_Instructor** folder
    2. perform a `git pull` to obtain the latest assignment 
    3. copy (`cp`) the current week to your repo
```bash
cd CSCI11_Sp26_Instructor
git pull
cp -r week_2/ ../CSCI11_Sp26_Student/week_2
```

2. Go to your repository to begin work on the assignment:
```bash
cd ..
cd CSCI11_Sp26_Student/week_2
```

3. Once completed **OR** you have a question, **update** your work on GitHub:

    Be sure to use the week-specific directories in the ```student``` directory then commit and push to your repository using VS Code Source Control or Terminal:
```bash
git add -A # to add (stage) all of the changes
git commit -m "adding my changes for week 5" # to commit your changes
git push # to push your change to your remote repository on GitHub
```

## Overview

Your directory structure must be the following:
1. Repository Structure **Your top directory (*Documents, below*), might be *Desktop*, *OneDrive*, *MyDocuments* or something else.**

```
Documents/
├── CSCI11_Sp26_Instructor/ (Assignment repository)
|    ├── week_2/
|    ├── week_3/
|    ├── week_4/
|    ├── week_5/
│    └── README.md
│    └── .gitignore
├── CSCI11_Sp26_Student/.  (Homework repository)
|    ├── week_2/
|    ├── week_3/
|    ├── week_4/
|    ├── week_5/
│    └── README.md
│    └── .gitignore
```

