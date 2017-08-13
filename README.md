# slcc_HTML
This repository contains files for the SLCC course, Website Structure with HTML. It is divided into 2 directories.  One directory is titled courseContent which will contain examples and activities for the course.  The second directory is titled students which will contain all the students work for the course.   

## Day 1 - Git Activity
This activity will guide you through some of the basics of using git.

### Git Config (one time initial setup)

```git config --global user.name "Jimi Jamison"```

```git config --global user.email "myemail@gmail.com"```

### Using Forks

Navigate to https://github.com/tharper/slcc_HTML.  Fork this repo using the fork button in the upper right-hand corner of the page. 

Clone your forked repo to you local machine using terminal / command line.
```git clone https://github.com/YourGitHubUsername/slcc_HTML```

### Making Changes

Navigate to the Repo.
```cd slcc_HTML/studentFiles```

If a directory does not exist with your name, create a new directory to store your completed assignments.  The new directory should be titled your name. Example:  firstNameLastName
```mkdir tysonHarper```

Now we need to commit the changes you made in the previously step. But first, lets check the status of our repo and files.  

```git status```

```git add . ```

```git commit -m "Some message goes here"```

Now that we have made the changes, you will need to merge these changes into your master forked branch.

```git push```

###Online tutorial
https://try.github.io/levels/1/challenges/1


## Day 2 - HTML Activity
Create a resume that includes your name, education, work history.  
Make sure to use semantic markup.
You may use placeholder text as needed (lorem ipsum).
Add photo of yourself to your resume.

## Day 3 - HTML Tables
Each student will create an HTML table containing class mates info.
First Name,
Last Name,
Hobby,
Favorite food

| First name        | Last Name          | Hobby | Favorite Food | 
| ------------- |:-------------:| -----:| ------ |
| Jimmy     | James| Swimming | Apples |
| Jimmy     | James| Swimming | Apples |
| Jimmy     | James| Swimming | Apples |

Recreate the following image using HTML Tables.  

![alt text](https://raw.githubusercontent.com/tharper/slcc_HTML/master/img/table.png)


