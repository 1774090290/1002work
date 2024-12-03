Fish Eat Fish Game
Overview
The Fish Eat Fish Game is a fun and interactive 2D game where players control a fish using the mouse. The objective is to grow by eating smaller fish while avoiding larger ones. The game spans multiple levels with increasing challenges and tracks the player’s score.

This project is developed in Java using the NetBeans IDE and utilizes JFrame for the graphical user interface.

Gameplay Mechanics
Control: Use the mouse to guide your fish around the game environment.
Objective:
Eat smaller fish to grow in size and progress to the next level.
Avoid larger fish that can eat you and end the game.
Progression:
Multiple levels with increasing difficulty.
Scores are tracked throughout the game.
No Timer: Play at your own pace until you win or lose.
Features
Sound Effects: Enjoy sound effects as you eat fish or encounter other game events.
Multiple Fish Types: Different fish species to eat or avoid, adding variety to the gameplay.
Graphics: Vibrant visuals with a 2D fish theme.
Animations: Planned for future updates but not implemented yet.
Levels: Multiple levels, each with unique challenges and increasing difficulty.
Setup Instructions
Follow these steps to run the game in NetBeans IDE:

Clone or download the project to your local machine.
Open NetBeans IDE.
Import the project:
Go to File > Open Project.
Select the FishEatFish folder.
Ensure all required libraries and assets are present.
Contributors can upload custom assets (images, sounds, etc.).
Place assets in the designated folders (src/assets/images, src/assets/sounds, etc.).
Run the project:
Right-click on the main class file (e.g., GameLauncher.java) and select Run File.
Contributing
Steps (after cloning)
Ensure your code is up to date (pull from main if not)
Create branch for your feature
Work on the code
Push to this repo
Pull request
Branch Management
Create a new branch for your feature
Open the Git Menu

In the Projects window, right-click on your project.
From the context menu, go to Git > Branches > Create....
Set Branch Name

In the dialog box that appears, you’ll be prompted to enter a branch name.
The branch name should be descriptive and in kebab-case (e.g., add-new-feature, fix-issue-123).
Select the Base Branch

Select the base branch from which the new branch will be created (typically main or master).
If you want to create a branch from another existing branch, choose it from the list.
Create the Branch

After setting the name and selecting the base branch, click the Create Branch button.
NetBeans will create the new branch and automatically switch to it.
Naming convention:
feature/ - for new features
bugfix/ - for bug fixes
hotfix/ - for urgent fixes
update/ - for updates to existing features
Git Pull and Push Guide in NetBeans
This guide will walk you through how to pull (fetch and update) and push (send your changes) in NetBeans IDE using Git.

Prerequisites
Ensure your project is connected to a Git repository.
Make sure Git is installed on your system and properly configured in NetBeans.
How to Pull Changes in NetBeans
Pulling updates from the remote repository ensures your local project is up to date with the latest changes.

Open your project in NetBeans

Launch NetBeans IDE and open the project that is connected to a Git repository.
Navigate to the Git Menu

Go to the Team menu at the top of the NetBeans window.
From the drop-down menu, select Git > Pull....
Configure Pull Settings

A dialog box will appear with options to pull from the remote repository.
Remote: Choose the remote repository (typically origin).
Branch: Select the branch you want to pull from (typically main or master).
You can leave the default settings for a regular pull or adjust based on your needs.
Pull the Latest Changes

Click OK to fetch and merge the latest changes from the remote repository.
NetBeans will pull the latest changes into your local repository. You’ll see updates or new commits reflected in your project.
Check for Conflicts

If there are merge conflicts, NetBeans will notify you and offer a merge tool to help resolve them.
Once resolved, commit the merge and continue with your work.
How to Push Changes in NetBeans
Pushing sends your local changes to the remote repository, making them available to others.

Make Sure Your Local Changes Are Committed

Before pushing, ensure all your changes are committed.
Go to the Git tab and right-click on the project directory.
Select Git > Commit... and commit your changes.
Navigate to the Git Menu

Go to the Team menu in NetBeans.
Select Git > Push... from the drop-down menu.
Configure Push Settings

A dialog box will appear with options to push to the remote repository.
Remote: Choose the remote repository (typically origin).
Branch: Select the branch to push to (typically main or master).
You can select additional options, such as forcing the push or pushing tags, if necessary.
Push Your Changes

Click OK to push your committed changes to the remote repository.
NetBeans will push your changes to the specified branch on the remote repository.
Verify the Push

Once the push is successful, verify the changes by checking the repository on GitHub or the relevant Git hosting service.
Additional Notes
Fetch: If you want to check for updates from the remote repository without merging them, use the Git > Fetch option.
Sync: To easily sync your local repository with the remote, use Team > Git > Remote > Pull and Team > Git > Push from the same menu.
Pull Request Process
Go to GitHub repository
Click "New Pull Request"
Select your branch
Fill in the PR template:
Description of changes
Related issue(s)
Testing completed
Screenshots (if applicable)
Request review from team members
Address any feedback
Team Members
KHONG YIROU
CLAIRE SIEW ZHI-XUAN
LIU MING JING
WANG ZHE
