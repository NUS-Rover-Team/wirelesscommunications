# GitHub Workflow Practice for Comms

## What is workflow?
"A Git Workflow is a recipe or recommendation for how to use Git to accomplish work in a consistent and productive manner. Git workflows encourage users to leverage Git effectively and consistently." (From: [Atlassian-Git](https://www.atlassian.com/git/tutorials/comparing-workflows))

## Why workflow?
* Makes for easier code management.
* Code can be reviewed and changed in an efficient manner.

## Workflow Practice
If you are new to Git it is likely that you are not very familiar with following a workflow on Git. Fret not! Here's some practice to bring you up to speed.

### Requirements:
* Git must be installed on your local system. You may use either git GUI or git bash for this exercise.
* We assume you know basic git commands such as git clone, git pull, merge, add, commit etc. If not, it is suggested that you read up the material given in the main ReadME website.

### Procedure Part I: Creating Feature Branch and PR:
Follow the steps in this specific order:
* Fork https://github.com/NUS-Rover-Team/workflow-test.git to your Github account, now you will have a repo in your account called [your_username]/workflow.test. We will refer to this as your **remote fork**.
* Clone your **remote fork** repo to your local machine. We will refer to this your **local fork** repo. 
* Create a new branch on your **local fork** and call it _branch-EditThis_. Checkout that branch.
* Make some changes to edit_this.txt file on your **local fork**. Write anything there, it doesn't matter (perhaps leave out expletives and such, lol).
* Stage and commit the changed file (Remember to supply apt commit message). Push the branch-EditThis to origin. This will push the changes to your **remote fork** repo on your github.
* Go to your **remote fork** on Github. See that the branch you newly pushed is a commit ahead of the original branch you forked from. You will have the option of creating a pull request (PR) . Create the PR from your branch-EditThis -> NUS-Rover-Team/workflow-test main. Add comments if necessary. 
* You will be able to see your PR from https://github.com/NUS-Rover-Team/workflow-test.git -> Pull Requests. On the right side of the screen, request for a review from Comms subteam. Do not merge the PR until it has been approved by the team leads.

### Procedure Part II: Merging PR, Merge Conflict and Updating Local & Remote Fork
_To be detailed in 1st meeting session_
