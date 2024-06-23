
# 0x03. Git

GitCode versioningGithub

-   Weight:  1
-   Project over - took place from  Dec 5, 2023 5:00 AM  to  Dec 6, 2023 5:00 AM
-   An auto review will be launched at the deadline

#### In a nutshell…

-   **Auto QA review:**  26.0/26 mandatory & 11.0/11 optional
-   **Altogether:**  **200.0%**
    -   Mandatory: 100.0%
    -   Optional: 100.0%
    -   Calculation: 100.0% + (100.0% * 100.0%) == **200.0%**

### Concepts

_For this project, we expect you to look at these concepts:_

-   [Struggling with the sandbox? Try this: Using Docker & WSL on your local host](https://intranet.alxswe.com/concepts/100039)
-   [Source code management](https://intranet.alxswe.com/concepts/22)
-   [Right-engineering, right-documenting](https://intranet.alxswe.com/concepts/6)
-   [Authenticating Git](https://intranet.alxswe.com/concepts/100035)
-   [Git and Github cheat sheet - Everything in less than 30 seconds](https://intranet.alxswe.com/concepts/57)

## Resources

**Read or watch:**

-   [Resources to learn Git](https://intranet.alxswe.com/rltoken/fq9RPlPS5IdYzOWTvwbdFQ "Resources to learn Git")
-   [About READMEs](https://intranet.alxswe.com/rltoken/R7MeJ8alpK3JoVF8w24wiQ "About READMEs")
-   [How to write a Git commit message](https://intranet.alxswe.com/rltoken/FYsjjR-97Hk4NJtgqzWdtQ "How to write a Git commit message")

**Resources for advanced tasks**  (Read only after finishing the mandatory tasks):

-   [Learning branching](https://intranet.alxswe.com/rltoken/tN8ZJ0yWubOP6jdciqtrFw "Learning branching")
-   [Effective pull requests and other good practices for teams using GitHub](https://intranet.alxswe.com/rltoken/mjpQ9OCU0Dz-DFxZjASEJg "Effective pull requests and other good practices for teams using GitHub")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.alxswe.com/rltoken/jj0uPL9hiKF10KCH4u620A "explain to anyone"),  **without the help of Google**:

### General

-   What is source code management
-   What is Git
-   What is GitHub
-   What is the difference between Git and GitHub
-   How to create a repository
-   What is a README
-   How to write good READMEs
-   How to commit
-   How to write helpful commit messages
-   How to push code
-   How to pull updates
-   How to create a branch
-   How to merge branches
-   How to work as collaborators on a project
-   Which files should and which files should not appear in your repo

### Copyright - Plagiarism

-   You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
-   You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
-   You are not allowed to publish any content of this project.
-   Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements

### General

-   A  `README.md`  file at the root of the  `alx-zero_day`  repo, containing a description of the repository
-   A  `README.md`  file, at the root of the folder of  _this_  project (i.e.  `0x03-git`), describing what this project is about
-   **Do not use GitHub’s web UI**, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
-   Your answer files should only contain the command, and nothing else

## More Info

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main

```

### Quiz questions

**Great!**  You've completed the quiz successfully! Keep going!  (Hide quiz)

#### Question #0

You have the following files in your project directory:

```
julien@ubuntu:/tmp/git_project$ ls
0-test  0-test~ #0-test# file1  file2

```

You’ve edited  `0-test`  and you want to add it to your GitHub repo. What is the correct command to add  **only**  `0-test`?

-   `git add .`
    
-   `git add 0-test`
    
-   `git add -N 0-test`
    

#### Tips:

You should learn what each of these commands would actually do if you were to execute them!

#### Question #1

What command can you use to see what changes have been staged, which haven’t, and which files aren’t being tracked by Git?

-   `git init`
    
-   `git checkout`
    
-   `git status`
    

## Tasks

### 0. Create and setup your Git and GitHub account

mandatory

Score:  100.0%  (Checks completed: 100.0%)

#### Step 0 - Create an account on GitHub [if you do not have one already]

You will need a GitHub account for all your projects at ALX. If you do not already have a github.com account, you can create an account for free  [here](https://intranet.alxswe.com/rltoken/1vpH3ScWYjfgZD0J59jusA "here")

#### Step 1 - Create a Personal Access Token on Github

To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.

You can follow  [this tutorial](https://intranet.alxswe.com/rltoken/coQUsDnam4suGaXSVinQxA "this tutorial")  to create a token.

Once it’s created, you should have a token that looks like this:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/a449483cd76a72cef1b42df831e686c64faa1cf6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240620%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240620T040555Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=160326e62895c318c8cfc58b78591df315d9a67fa2194d266113f9f5af07c611)

#### Step 2 - Update your profile on the Intranet

Update your Intranet profile by adding your Github username  [here](https://intranet.alxswe.com/rltoken/9dthiwx9AyxxUzV_QPIRWQ "here")

If it’s not done  **the Checker won’t be able to correct your work**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/6270480a0a982cd1846b877eda2ee405d2e8f575.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240620%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240620T040555Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e180d5e2f9c4387ff30c473747f1613741bb0f8a5e2e8f7668e492bf1b0035cd)

#### Step 3 - Create your first repository

Using the graphic interface on the  [github website](https://intranet.alxswe.com/rltoken/1vpH3ScWYjfgZD0J59jusA "github website"), create your first repository.

-   Name:  `alx-zero_day`
-   Description:  `I'm now a ALX Student, this is my first repository as a full-stack engineer`
-   Public repo
-   No  `README`,  `.gitignore`, or license

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/2340a2d0f7c74b5dd6f8fc2aa58f94d13ea2c775.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240620%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240620T040555Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=56ed16de95e397c32a9d7f6eb05b1d3c085b22f0eceb16cd1fa67b772fa40618)

#### Step 4 - Open the sandbox

On the intranet, just under the task, click on the button  ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/9db8eece71455dfddf4b7d8585c037c535f1d18d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240620%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240620T040555Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=15e5559f544c1a69efc69707c9f34d4962165ab9202b8fb9eadfbf43720da992)  and  `run`  to start the machine.

Once the container is started, click on  ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/be9d1fbfb3d97e6924a4d2af7df9290ad7ae77df.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240620%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240620T040555Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7285b6658cf288e15bdbc68d5c2b420b4a445c8645e11e03b80f74d041159ff3)  to open a shell where you can start work from.

#### Step 5 - Clone your repository

On the webterm of the sandbox, do the following:

-   Clone your repository

```
root@896cf839cf9a:/# git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-zero_day.git                  
Cloning into 'alx-zero_day'...
warning: You appear to have cloned an empty repository.       

```

**Replace {YOUR_PERSONAL_TOKEN} with your token from step 1**

**Replace {YOUR_USERNAME} with your username from step 0 and 1**

**Pro-Tip:**  On windows, use CTRL + A + V to paste in the web terminal

#### Step 6 - Create the README.md and push the modifications

-   Navigate to this new directory.  [Tips](https://intranet.alxswe.com/rltoken/qSP5HcBSSIL0U23PdIGKLw "Tips")

```
root@896cf839cf9a:/# cd alx-zero_day/
root@896cf839cf9a:/alx-zero_day#

```

-   Create the file  `README.md`  with the content  `My first readme`.  [Tips](https://intranet.alxswe.com/rltoken/_SSotigVtvVNThTVLJKZPQ "Tips")

```
root@896cf839cf9a:/alx-zero_day# echo 'My first readme' > README.md                                                                 
root@896cf839cf9a:/alx-zero_day# cat README.md                                                                                      
My first readme                                                                                                                       

```

-   Update your git identity

```
root@896cf839cf9a:/alx-pre_course# git config --global user.email "you@example.com"
root@896cf839cf9a:/alx-pre_course# git config --global user.name "Your Name"

```

-   Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin

```
root@896cf839cf9a:/alx-zero_day# git add .
root@896cf839cf9a:/alx-zero_day# git commit -m 'My first commit'
[master (root-commit) 98eef93] My first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
root@896cf839cf9a:/alx-zero_day# git push                                                                                           
Enumerating objects: 3, done.                                                                                                         
Counting objects: 100% (3/3), done.                                                                                                   
Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.                                                                          
Total 3 (delta 0), reused 0 (delta 0)                                                                                                 
To https://github.com/{YOUR_USERNAME}/alx-zero_day.git                                                                                       
 * [new branch]      master -> master              

```

Good job!

You pushed your first file in your  **first repository**  of the  **first task**  of your  **first ALX School project**.

You can now check your repository on GitHub to see if everything is good.

**Repo:**

-   GitHub repository:  `alx-zero_day`
-   File:  `README.md`

Done!  Check your code  Get a sandbox  QA Review

### 1. Repo-session

mandatory

Score:  100.0%  (Checks completed: 100.0%)

Create a new directory called  `0x03-git`  in your  `alx-zero_day`  repo.

Make sure you include a not empty  `README.md`  in your directory:

-   at the root of your repository  `alx-zero_day`
-   AND in the directory  `0x03-git`

And important part:  **Make sure your commit and push your code to Github - otherwise the Checker will always fail.**

**Repo:**

-   GitHub repository:  `alx-zero_day`

Done!  Check your code  Get a sandbox  QA Review

### 2. Coding fury road

mandatory

Score:  100.0%  (Checks completed: 100.0%)

For the moment we have an empty project directory containing only a  `README.md`. It’s time to code!

-   Create these directories at the root of your project:  `bash`,  `c`,  `js`
-   Create these empty files:
    -   `c/c_is_fun.c`
    -   `js/main.js`
    -   `js/index.js`
-   Create a file  `bash/alx`  with these two lines inside:  `#!/bin/bash`  and  `echo "ALX"`
-   Create a file  `bash/school`  with these two lines inside:  `#!/bin/bash`  and  `echo "School"`
-   Add all these new files to git
-   Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

**Repo:**

-   GitHub repository:  `alx-zero_day`
-   Directory:  `0x03-git`
-   File:  `bash/alx, bash/school, c/c_is_fun.c, js/main.js, js/index.js`

Done!  Check your code  Get a sandbox  QA Review

### 3. Collaboration is the base of a company

mandatory

Score:  100.0%  (Checks completed: 100.0%)

A branch is like a copy of your project. It’s used mainly for:

-   adding a feature in development
-   collaborating on the same project with other developers
-   not breaking your entire repository
-   not upsetting your co-workers

The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.

For this project, create a branch  `update_script`  and in this branch:

-   Create an empty file named  `bash/98`
-   Update  `bash/alx`  by replacing  `echo "ALX"`  with  `echo "ALX School"`
-   Update  `bash/school`  by replacing  `echo "School"`  with  `echo "The school is open!"`
-   Add and commit these changes (message: “My personal work”)
-   Push this new branch  [Tips](https://intranet.alxswe.com/rltoken/tN31xFfDVctixZZ350tDGw "Tips")

Perfect! You did an amazing update in your project and it’s isolated correctly from the  **main**  branch.

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

-   Change branch to  `main`
-   Update the file  `bash/alx`  by replacing  `echo "ALX"`  with  `echo "ALX School is so cool!"`
-   Delete the directory  `js`
-   Commit your changes (message: “Hot fix”) and push to the origin

Ouf, hot fix is done!

**Repo:**

-   GitHub repository:  `alx-zero_day`
-   Directory:  `0x03-git`
-   File:  `bash/alx, bash/school, bash/98`

Done!  Check your code  Get a sandbox  QA Review

### 4. Collaboration: be up to date

mandatory

Score:  100.0%  (Checks completed: 100.0%)

Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.

For this task –  **and only for this task**  – please update your file  `README.md`  in the main branch from GitHub.com. It’s the  **only time**  you are allowed to update and commit from GitHub interface.

After you have done that, in your terminal:

-   Get all changes of the main branch locally (i.e. your  `README.md`  file will be updated)
-   Create a new file  `up_to_date`  at the root of your directory and in it, write the git command line used
-   Add  `up_to_date`  to git, commit (message: “How to be up to date in git”), and push to the origin

**Repo:**

-   GitHub repository:  `alx-zero_day`
-   Directory:  `0x03-git`
-   File:  `README.md, up_to_date`

Done!  Check your code  Get a sandbox  QA Review

### 5. HAAA what did you do???

#advanced

Score:  100.0%  (Checks completed: 100.0%)

Collaboration is cool, but not really when you update the same file at the same time…

To illustrate that, please merge the branch  `update_script`  to  `main`: “Cool, all my changes will be now part of the main branch, ready to be deployed!”

**HHHHHHHAAAAAAAA**

```
CONFLICT (content): Merge conflict in bash/alx

```

As you can see, you have conflicts between two branches on the same file.

Your goal now is to resolve conflicts by using the version of the branch  `update_script`, and push the result to the origin.

At the end, you should have all your work from the branch  `update_script`  (new file and two updated files) and all latest  `main`  commits (new files, delete folder, etc.),  _without_  conflicts.

**Repo:**

-   GitHub repository:  `alx-zero_day`
-   Directory:  `0x03-git`

Done!  Check your code  Get a sandbox  QA Review

### 6. Never push too much

#advanced

Score:  100.0%  (Checks completed: 100.0%)

Create a  `.gitignore`  file and define a rule to never push  `~`  files (generated by Emacs).  [Tips](https://intranet.alxswe.com/rltoken/sEKIVnR2lEL0sN4jc26hhA "Tips")

**Repo:**

-   GitHub repository:  `alx-zero_day`
-   Directory:  `0x03-git`
-   File:  `.gitignore`

Done!  Check your code  Get a sandbox  QA Review