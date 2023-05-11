# ngstarter

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/json-server-yyzhot)

# Ng Starter
Welcome to Speed Code Academy Starter project.
This project basiccally has just a "ng new" content

## Angular Job Skill

This skill set is dedicated for real world job competency.
The assignments here are based on real assignments in real production workplaces.

# This version : zero-branch : 20230507-1653

This current version is an "ng new ..." project.
It's purpose is to be a starting point for every assignment.

# How to create an assignment branch from zero-project

## Step 1 : Create a name for the branch
- (1) Each assignments has 2 branches, a "Question" and an "Solution" branch.
- (2) The question branch has all the codebase needed to start the assignment.
- (3) The solution branch has all the codebase for the solution.
- (4) Name Question branch with this convention: CARD-Q-YYYMMDD-HHMM
    - For the solution branch use "S" instead of "Q".
    - The timestamp section of the convention is from the card creation spreadsheet.

## Step - 2 : Create the branch
- (1) Checkout "zero-branch". FYI it is locked so cannot change its content.
- (2) From this branch create your question branch example: git switch -c CARD-Q-20231106-1417
- (3) Work on that branch and commit as many times as needed.
- (4) When done create from it another branch for the solution: git switch -c CARD-S-20231106-1417
- (5) When done commiting all your coding sessions you are done working on the branch.

## Step - 3 : Maintenance
- (1) When need to fix bugs or update the Question or Soultion you can open a temporary branch under the branch you want to fix/update, when done merge to the parent branch and delete the temporary branch.