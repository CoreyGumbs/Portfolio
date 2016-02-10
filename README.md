# Portfolio
My Portfolio Project for my Deployment of Web Applications class

## Overview and Purpose:


This is the deployment plan for [CoreyGumbs.com](http://wwww.CoreyGumbs.com), a personal portfolio website.  This portfolio is to showcase both current and past projects in which Corey Gumbs participated in or created for clients. As the portfolio expands, there will be a need to expand this portfolio website as well.

## Architecture:

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

The current version of this deployment is **Version 1.0**

This is the official repo for CoreyGumbs.com. Any and all version changes, updates, fixes, contributions will be found here. 

*Please make sure your local versions are up-to-date and running this current version before making any contributions as there may be bug fixes and/or code/features depricated.*

## Code Deployment

Strict adherence to current versions is strictly enforced. Before any work can be done on the portfolio, it is your responsibility to make sure you are working on the latest approved version of the application. 

Ensure you are utilizing the current version of Corey Gumbs Portfolio. The current **version  1.0**. 

If you are current and up-to-date feel free to scoll to your needed section of this plan otherwise start here:


#### Before You Proceed:
---

**_If you are new to this project you must clone the Github repo into your local file directory:_**

1. cd into desired local directory (we recommend Documents or Desktop)

2. clone git repo into desired local directory:
    1. _Git clone git@github.com:SonofLight/Portfolio.git_

**_If you are currently contributing to project you must ensure you are working with the most current version:_**

1. Navigate to working local directory

2. Check status of branch files:
    1. Git status
    2. Resolve all conflicts before pulling from master branch
    3. Push all changes to branch before pulling most current version
    
3. Ensure you are on the master branch
    1. Check branches
    2. Git branch
    3. If not on master branch then change to master branch:
        1. _Git checkout master_

4. If needed update to most current version:
    1. Git pull origin master


#### Contributions/Fixes:
---

All contributions, changes, fixes, debugs, etc. must be submitted via branches for review before being merged to master branch. 


#### Branch Formatting:
---

1.  Ensure you are on proper branch before adding or committing any changes:
    1.  To check current branch:
        1.  _Git Status_
        2.  _Look for “On [branchname]” message_
    2. To see current branches in repo:
        1. _Git branch_
    3. To change to needed branch:
        1. _Git checkout “[branchname]”_ 
    4. To create branch:
        1. _See following section_
    
2.  Contributors must create local branches using the following format:
    1.  All branches should have the following naming convention:
        1.  _File directory -contribution/fix title – version_
            1. **EXAMPLE 1:**  CSS –layout-width-fix– V1 or 
            2. **EXAMPLE 2:** CSS–All-Link-Hover-Effect- V1.2
    
    2.  Create branch:
        1.  _Git Checkout –b Branch Name_
        2. _To push to branch see section 3 of Branch Formatting_
        
3.  Add and Commit all file changes/contributions to new branch:
    1.  To add all files:
        1.  _Git add ._
    2.  To add a particular/individual file:
        1.  _Git add [file]_
    3.  Commit changes to branch:
        1.  Git commit –m “give detailed description of changes/contribution/additions”   (IE: Git commit –m “fixed site layout width error when on tablet screen resolution”)
    
4.  Push committed files to branch:
    1.  Git push origin  [branch]
    2.  Git status to ensure there are no conflicts
    
5.  Create Pull Request
    1.  Create Pull Request on Git Hub Repo:
        1. Click on “New Pull Request” button on Repo Code page
        2. Find “Base” drop down and make sure it is on Master
        3. Find “Compare” drop down and set it to your specific branch
        4. Enter in description of pull request 
        5. Click on “Create pull request” button

#### Code Review and Approval
---
Code will be merged to master branch upon code review and approval by Lead Developer/Approved Contributors


