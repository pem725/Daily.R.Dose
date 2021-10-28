# Daily R Dose - A Year of Continuous R
Personalizing R with Simone and Patrick

## Day 1 (10/27/21):  Github workflow.  

Clone our Daily R Dose repo.  Before you do, [first read this page](https://happygitwithr.com/new-github-first.html) for how to setup RStudio with an existing GitHub repo.

Then do the following after you setup a new project with the following URL:

https://github.com/pem725/Daily.R.Dose.git

`gitcreds::gitcreds_set()`

Now, copy your PAT to the console and hit enter.  Make sure it works by editing the README.md file and then commit the changes and then push them to GitHub.

## Day 2 (10/28/21):  Create a new file and sync it.

In short, make a new file that will be included in the GitHub repo online AND in your local git repo (on your computer).  Once you have created the file, merge it to your local git and the github repo by committing the changes.  There are a ton of points and clicks that follow BUT you can also do it by code using the `usethis()` function.  

You do it and then paste your code below.

<SCM, insert your code here>

## Day 3 (10/29/21): Open a new session and project...

We will have two projects going simultaneously AT ALL TIMES with this tutorial.  Open this project as the small one and then another as instructed.  I want you to open the [NRL project repo](https://github.com/pem725/NRL2021-MCINC.git) and, if you have not already done so, make sure you have it connected as you did on Day 1 (and 2).

Just to be clear, you need the following URL to clone the repo to your local system:

https://github.com/pem725/NRL2021-MCINC.git

## Day 4 (10/30/21):  Browse the NRL and...

...type what you edited here.  Commit the changes to your local repo and the GitHub repo and report the update to me via email.

## Day 5 (10/31/21):  Create an NRL scratch sheet

In programming, we typically have multiple files that serve as temporary files to help us sort out code before we merge it into the big project.  These files include the following:

[Scratch file](https://www.collinsdictionary.com/us/dictionary/english/scratch-file)

[Sandbox](https://searchsecurity.techtarget.com/definition/sandbox)

Here, I want you to create an SCM scratch file that is clearly named and documented to be YOURS and nobody elses.  Why do you merge said file with the rest of the repo?  Usually so that you don't have to worry about losing your work.  Give it a go.  Create a scratch file for yourself, commit the changes to the repo and push the changes to the GitHub repo.

## Day 6 (11/1/21): Edit your scratch sheet

Put in some comments that outline the things you want to initially do with the NRL files.  Pick one.  You can find the code for the project hosted on the Rmd file.  I suggest you copy the read data section and use only a part of it - make it simple and small.  You will use the copied code as just a training ground.  Should you desire to post any code changes to the NRL project, feel free to do so.

## Day 7 (11/2/21):  Select some cases (just a few)

In your scratch file, I want you to continue with the NRL file and select only a few cases (N <= 100).  Once you do that, eliminate the object from this Daily.R.Dose project that contains the original files and such.  We don't want to make this project huge.

`rm(OJBECT NAME HERE)`

By now, you ought to have some code snippets that select one data file, subsets the data to a manageable size, and deletes the objects in R that you no longer need (we call this garbage collection).

<post your code here>

## Day 8 (11/3/21):  Summarize the data subset

You can use a variety of tools but I suggest you start with the basics with:

`summary(mydat)`

and then branch out to others like:

`psych::describe(mydat)`

or give tidyverse a shot.  I suggest you check out [this guide](https://towardsdatascience.com/a-gentle-guide-to-statistics-in-r-ccb91cc1177e) to get you going in the right direction.

<post your code here>

## Day 9 (11/4/21):  Get crackin' on R markdown

I suggest you start perusing the markdown cheat sheets so you can become more familiar with the syntax.  Start with [this page](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and eventually branch out to using [this cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf).

<insert some new markdown here>

## Day 10 (11/5/21):  Create a new Rmarkdown file in the repo

You will now take the past few days to create a new file that is an RMarkdown file.  Follow the second cheat sheet I posted on Day 9.  In that file, you will see a workflow.  I suggest you look it over carefully and try to do it as they laid out.  Once you have a new file in the repo, I want you to edit it so you can start tracking changes in a file that helps you both write and do analyses.  Step 1 though is to create the file.  Baby steps.

<indicate that you have a file initialized here>

## Day 11 (11/6/21):  Transfer your working R code to the R Markdown file

Copy and paste your working code to the R Markdown.  Write a few lines of text in the file, test out some formatting, and save it.  Remember, always pull, edit, commit, and push **EVERY TIME** you analyze data.  The habit will become second nature.

<indicate you have finished the task here>


