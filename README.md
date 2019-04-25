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

### Online tutorial
https://try.github.io/levels/1/challenges/1


## Day 1 - HTML Activity
Create a resume that includes your name, education, work history.  
Make sure to use semantic markup.
You may use placeholder text as needed (lorem ipsum).
Add photo of yourself to your resume.

## Day 2 - HTML Tables

### Table Exercise 1
Each student will create an HTML table containing class mates info.
First Name,
Last Name,
Hobby,
Favorite food

| First name        | Last Name          | Hobby | Favorite Food | 
| ------------- |:-------------:| -----:| ------ |
| Jimmy     | James| Swimming | Apples |
| Ryan      | Butner| Golf | eggs |
| Jeff     | Clementine| Drawing | pizza |


### Table Exercise 2
Recreate the following image using HTML tables.  

![alt text](https://raw.githubusercontent.com/tharper/slcc_HTML/master/img/table.png)

### Form Exercise 
Create a simple contact form that captures
* Name
* Phone
* Email
* Comments Box

* Use the POST method and inspect the data being passed in the browser. Then change to GET method and inspect the data being passed.
* What is different between the 2 methods.
* When would you use GET vs POST?.


## Course Assessment
Commit your code for your resume, table exercises, and form exercise.  Once you have pushed to your repo generate a pull request.


