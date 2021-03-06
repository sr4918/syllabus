---
title: "Software & Tools"
output: html_notebook
---

# Software & Tools
In this course we will be using several online services and software packages. In order to participate in the class you will need to have operational, up-to-date accounts and installations of these tools.

## Online Services

#### Slack
Slack is an online team collaboration tool. Our [LADS-EDU Slack space](https://ladsedu.slack.com) will be the hub for our communication and the go-to place for discussing the readings and connecting with classmates when you have technical problems. Use this [invitation link](https://join.slack.com/t/ladsedu/shared_invite/enQtNTM5NTk2NjQ1NTU0LTQxYmExYWExNTg2MjgzODVlM2FlODlkNzJhOWM1MTdlMzI5ZDY3MTI4OTA0OWZhNGIzNGY2YmQ1ZDhiMTM1NTg) to join our Slack team. 

You should either download the Slack app for your computer or mobile device, enable desktop notifications from the browser, or plan to check in daily to make sure you don't miss any important course announcements.

#### Github
GitHub is an online repository using the Git version control system. Our [LADS-EDU Github space](https://github.com/learninganalytics-datascience-edu) is where I will upload course documents, links to readings and assignments. It is also where you will submit your completed assignments. You will need to [create a (free) personal Github account](https://github.com/join?source=header) if you don't have one already. When you have a Github account, share your username in the #githubdeets Slack channel and I will add you to our class organization so you will have full access to all the files and I will be able to see when you have work ready for me to review.

**Important: Make sure to choose usernames for Slack and Github that are (a) the same or very similar to each other and (b) are easily connected to your official name in the NYU system.**

## Software

#### Git
Git is a version control system (a way to keep track of changes in files across multiple copies accessed by multiple users). You will need this installed on your computer in order to work with our class files on Github.

  + [Install Git](https://git-scm.com/downloads)
  
#### R and RStudio
R is an open source programming language for statistical computing and graphics widely used in data mining and learning analytics. RStudio is an open source development environment that supports work in R with a variety of functionalities. You will need to install both of these on your computer.

  + [Install R 3.4.3](https://cran.rstudio.com/)
  + [Install RStudio 1.1.419](https://www.rstudio.com/)

You will be assigned some basic tutorials for using R that you can complete within R itself (using the Swirl R package). NYU also offers additional [Tutorials and Resources for R](http://guides.nyu.edu/r) including access to modules on Lynda.com.
  
## Connecting your Github account to your RStudio installation 
In order to complete your course assignments you will need to *pull* down files I provide from a Github *repository* to your computer, work with them using R in RStudio, *commit* the changes and *push* the files back up to the repository. (*Tip: This is an important sequence of events that you will need to do many times this term*). For this to work, you will need to set-up your RStudio installation to use Git to communicate with Github. 

Here is a pretty good set of instructions to follow: **[Setting Up GitHub with RStudio](http://www.molecularecologist.com/2013/11/using-github-with-r-and-rstudio/)**

Here is a second set that some students have also found useful: **[Version Control in RStudio with Git](https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN)**

Once you have set-up the connection, I **highly** recommend that you follow the instructions at the end of the first set of instruction to create a test repository with the default README.md file, pull it down into a new project in RStudio, make some edits to the text (it doesn't matter what), commit the changes and push back up to github. You should then be able to view the modified file in your github account and know that you are ready to go for next week. Testing your code (or in this case your installation) is a critical part of the process.

**IMPORTANT NOTES / CLARIFICATIONS / TROUBLESHOOTING HELP FOR THE FIRST SET OF INSTRUCTIONS BASED ON PRIOR STUDENT EXPERIENCE** 

*For Everyone:*

  + The two lines you need to type into the GIT Cmd/Bash terminal each have **two** short dashes in them (i.e. "git config –-global user.name "your GitHub account name"), not one long one.
  + The current Github interface is different than what’s in the tutorial. When you want to get the repository URL, just click the green “Clone or Download” button, and you’ll see it. 
  
*For Mac Users:*
  
  + After you have installed Git, you may not see an executable file in the location of the installation. If so, it will be in /usr/bin/. This folder is normally hidden, if you don’t know how to access this folder, open Finder, click Go (on the file menu) and choose “Go to folder” and then type in “/usr/bin/” and then press return/enter key. You will likely find it there (though see next bullet)
  + Some Mac users have found their git exe in a slightly different place (/usr/local/bin/git/ rather than /usr/bin/git/). You can run "which git" in the terminal and it will tell you exactly where git was installed. 
  + When the tutorial says “Open up the bash version of Git” you need to open a new terminal window (if you don’t know how to do this, just use spotlight search (command + space) and type “terminal” and then press return key). After you open a new terminal window, drag the git file from the finder window to the terminal window and press return. Then you can type in the commands in the tutorial.
  + If you get the following error trying to open the git bash from the terminal "xcrun: error: invalid active developer path" type the followign commaned (in the terminal): "xcode-select --install" and then try to drag the git file to the terminal again.
  + If you recieve the follow error, please follow instructions [10.1.1](http://ohi-science.org/manual/#rpostback-askpass-error) to correct it:  "error: unable to read askpass response from 'rpostback-askpass' fatal: could not read Username for github.com: Device not configured"
 
  
**IMPORTANT EMOTIONAL WELL-BEING INFORMATION**

While the instructions given for connecting GitHub and RStudio are clear and thorough, it is still possible to run into challenges getting the systems to talk to each other. Don't be discouraged -  figuring out how to get the tools to do what you want is a big part of data science. What is important is not giving up when things don't work right away and learning to troubleshoot problems. If you do run into difficulties you can (a) look for help for the specific problem you are encountering online (there are many helpful forums devoted to working with R, RStudio, Git and Github); (b) ask your classmates for help in the [Slack #ask-give-tech-help channel](https://ladsedu.slack.com/messages/ask-give-tech-help/) - others may have run into the same issue. Conversely, if you have been successful in connecting the systems, please check Slack to see if you can be of help to others; (c) if searching for help and asking your classmates hasn't resolved the issue, send me an email and we can set up a time to meet *before* next class. 
