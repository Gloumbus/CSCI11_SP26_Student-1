# Github Documentation for CSCI11 Spring 2026

Repositories for students to exchange homework with the instructor.

For *CSCI11*, there are **two** repositories:
* *[CSCI11_Sp26_Instructor](https://github.com/lkoepsel/CSCI11_Sp26_Instructor)* - one repository, which will be the same for **all** students. It is *public* and hosted on *github.com/lkoepsel*. It contains the assignments for each week.
* *[CSCI11_Sp26_Student](https://github.com/lkoepsel/CSCI11_Sp26_Student)* - a clone of this repository for **each** student, it will be private and hosted on *github.com/student_username*. It contains each student's work on the weekly assignments.

### Important
1. **Please make sure your version of the student repository (*CSCI11...Student*) on GitHub is private and is accessible by only the instructor and you.**
2. **Please do NOT make changes or add files to the *CSCI11...Instructor* folder, as this is where you will receive new versions of files from the instructor**

## Installation

### 1. Clone this repository

    1. Go to the [CSCI11_Sp26_Student](https://github.com/lkoepsel/CSCI11_Sp26_Student) on my github.
### 3. Create a new CSCI11_Student repository on your system

In this step you will be making changes to CSCI11_Student**s** (*plural*), to convert it to CSCI11_Student (*singular*).

1. Delete the instructor folder
2. Change the name of CSCI11_Students (*plural*) to CSCI11_Student (*singular*)

### 4. Create a new CSCI11_Student repository on Github
1. On Github, click on Repositories.
2. Click on the new button on the far right. (*See image below.*)
 ![](./github_new.png)
3. In the box beside your user name enter: *CSCI11_Student*  (**Exactly!**)
 ![](./github_name.png)
4. Click on the green Create Repository at the bottom of the page.
 ![](./github_create.png)

**Do NOT close the next page shown on Github, it has your next steps!**

### 4. Connect your **local** repository to your **Github** repository.

Perform the four commands below, **one by one**, ensuring there is **NOT** an error, before going to the next step:
   1. Remove the original connection, if the result is "*error: No such remote: origin*", this is fine:
```bash
git remote remove origin
```

   2. Add the origin which will point to *your* GitHub account, so you will **need to change username**:

```bash
git remote add origin git@github.com:username/CSCI11_Student.git
```

   3. Add the branch, *main*:
```bash
git branch -M main
```

   4. Push the local branch *main* to your Github repository:
```bash
git push -u origin main
```


## Ongoing Operations:

### To get the latest assignment, in the CSCI11_Instructor folder
   1. To **sync** with *lkoepsel* (or class) updates:
   ```bash
   git fetch origin
   git merge origin/main
   ```

   2. To **update** your work on GitHub:
   - Be sure to use the week-specific folders in the ```student``` folder then commit and push to your repository using VS Code or CLI:
   ```bash
   git add -A # to add all of the changes
   git commit -m "adding my changes for week 5" # Commit your changes
   git push origin # push your change to your repository on GitHub
   ```
