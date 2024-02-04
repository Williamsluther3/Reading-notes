# Summary

In order to explain Git, we have to first understand the various aspects of it. What is the purpose of it and why would anyone even want to use it. I will summarize some of the facts about Git that I have learned so far. Things like:  

* *What Git is*  
* *Version Control*  
* *Cloning*
* *Commands*

## *Let's explore Git*

## What is Git

Git is one of the three Version controls that allows you to save versions of files in a Distributed Version Control systems (DVCS).

## What is Version control

*Version Control System (VCS)*: is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. There three types of version control are:  

* ### *Local Version Control:* Recording versions saved on your hard disk.  

* ### *Centralized Version Control (CVCS):*  A system that allows collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS).

* ### *Distributed Version Control (DVCS):* Allows you to revisit various versions of a file or set of files by saving the changes in different locations (mirrored repositories) . This addresses the major vulnerability of the Local and Centralized Version control where everything is stored in one place. And if the file fails or is damaged, that single point of failure causes you to loose everything.

## What is Cloning

Cloning is creating a copy of an existing Git repository from a particular server like GitHub and placing it in a application, that uses git commands, by using the clone command with a repository’s URL:  

### *git clone https://github.com/test*.

## Commands

After updating cloned repositories in tools like Visual Studio Code, you will need to save and send the updates back to the original repository location. To do this you will need to take the the following steps and commands:

1. ### *Git add filename & Git add*

   a. *Git add (filename)*: Afte making and saving changes to one file of the cloned repository you will use this command to track and stage the file preparing it to be saved.  
   b. *Git add*: Is when you have made changes to multiple files and it stages all the files in the cloned repository and prepares them to be saved.

2. ### *git status*  

After tracking and staging new files  use the git status command to make sure there are no errors and you're ready to move to the next step.

3. ### *git commit -m "Reason for chnages made to repository"*

After staging files, you run the *git commit -m "messege" command. This command commits a snapshot or saaves the modifications to tracked files in the working directory.

4. ### *git push origin main*

This command pushes changes from the local “master” branch to the remote repository named “origin or Main”. For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository. However, these names can be changed by the user.

After pushing the updates you will repeat the *git status* command to make sure there are no errors and after confirmation you can check the Repository for your updates.
