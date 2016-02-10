# Portfolio
My Portfolio Project for my Deployment of Web Applications class

## Overview and Purpose:
---------------------

This is the deployment plan for [CoreyGumbs.com](http://wwww.CoreyGumbs.com), a personal portfolio website.  This portfolio is to showcase both current and past projects in which Corey Gumbs participated in or created for clients. As the portfolio expands, there will be a need to expand this portfolio website as well.

## Architecture:
-------------------
 [CoreyGumbs.com](http://wwww.CoreyGumbs.com) is currently a static website built upon the Bootstrap 3 framework.  There is a possibility of more dynamic aspects being added in the future. Currently the architecture of the site compromise
 
    source/
        - Index.html
        - Images
        - CSS
            |-  Bootstrap.css files
            |-  Main.css
        - JavaScript/JS
            |- Bootstrap.js files
            |- Main.js
        - Fonts 
            |- Bootstrap fonts file
            |- Bootstrap Glyph file


## Version
-------
The current version of this deployment is **Version 1.0**

This is the official repo for CoreyGumbs.com. Any and all version changes, updates, fixes, contributions will be found here. 

*Please make sure your local versions are up-to-date and running this current version before making any contributions as there may be bug fixes and/or code/features depricated.*

## Code Deployment
-------
Strict adherence to current versions is strictly enforced. Before any work can be done on the portfolio, it is your responsibility to make sure you are working on the latest approved version of the application. 

Ensure you are utilizing the current version of Corey Gumbs Portfolio. The current **version  1.0**. 

If you are current and up-to-date feel free to scoll to your needed section of this plan otherwise start here:

### Must Do First:
-------
**_If you are new to this project you must clone the Github repo into your local file directory:_**

1. cd into desired local directory (we recommend Documents or Desktop)
2. clone git repo into desired local directory:
    1. Git clone git@github.com:SonofLight/Portfolio.git

**_If you are currently contributing to project you must ensure you are working with the most current version:_**

1. Navigate to working local directory
2. Check status of branch files: 
    1. Git status
    2. Resolve all conflicts before pulling from master branch
    3. Push all changes to branch (see “ directions for instructions) before pulling most current version
3. Ensure you are on the master branch
    1. Check branches
    2. Git branch
    3. If not on master branch then change to master branch:
    4. Git checkout master
4. If needed update to most current version:
    1. Git pull origin master

### Contributions/Fixes:
---------
All contributions, changes, fixes, debugs, etc. must be submitted via branches for review before being merged to master branch. 

### Branch Formatting:
-------
1.  Ensure you are on proper branch before adding or committing any changes:
    1.  **To check current branch:** 
        1.  _Git Status_
        2.  _Look for “On [branchname]” message_
    2. **To see current branches in repo:**
        1. _Git branch_
    3. **To change to needed branch:**
        1. _Git checkout “[branchname]”_
    4. **To create branch:**
        1. See following section  
2.  Contributors must create local branches using the following format:
    +  All branches should have the following naming convention:
        +  File directory -contribution/fix title – version IE: CSS –layout-width-fix– V1 or CSS–All-Link-Hover-Effect- V1.2
    +  Create branch:
        +  Git Checkout –b Branch Name (please follow proper naming conventions as described on this document)
        + To push to branch see section 3 of Branch Formatting
3.  Add and Commit all file changes/contributions to new branch:
a.  To add all files:
i.  Git add .
b.  To add a particular/individual file:
i.  Git add [file]
c.  Commit changes to branch:
i.  Git commit –m “give detailed description of changes/contribution/additions”   (IE: Git commit –m “fixed site layout width error when on tablet screen resolution”)
4.  Push committed files to branch:
a.  Git push origin  [branch]
b.  Git status to ensure there are no conflicts
5.  Create Pull Request
a.  Create Pull Request on Git Hub Repo:
i.  Click on “New Pull Request” button on Repo Code page
ii. Find “Base” drop down and make sure it is on Master
iii.    Find “Compare” drop down and set it to your specific branch
iv. Enter in description of pull request 
v.  Click on “Create pull request” button
6.  Code Review and Approval
a.  Code will be merged to master branch upon code review and approval by Lead Developer/Approved Contributors


