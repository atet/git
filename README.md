﻿# [atet](https://github.com/atet) / [learn](https://github.com/atet/learn) / [git](https://github.com/atet/learn/tree/master/git)

[![.img/logo_git.png](.img/logo_git.png)](#nolink)

# Introduction to Git (Incomplete)

* _Git and run_ in 15 minutes.
* This quick introduction to [Git](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics) is meant to cover only the absolute necessary material to get you up and running in a minimal amount of time.
* You are here because you want to use a [Version Control System (VCS)](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) to help manage your solo and/or team-based projects.
* We will be using [Git Graphical User Interface (GUI)](https://git-scm.com/download/) to connect with the [GitHub](https://github.com) web-based platform to perform basic operations; advanced material is not covered here.

--------------------------------------------------------------------------------------------------

### Table of Contents

#### Introduction
* [0. Requirements](#0-requirements)
* [1. Installation](#1-installation)
* [2. New Repository](#2-new-repository)
* [3. Add Files](#3-add-files)
* [4. Saving Changes](#4-saving-changes)
* [5. Typical Workflow](#5-typical-workflow)

#### Supplemental
* [Epilogue](#Epilogue)
* [Additional Tutorials](#additional-tutorials)
* [GitHub vs. other Git platforms](#gitHub-vs-other-git-platforms)

--------------------------------------------------------------------------------------------------

### 0. Requirements
* This tutorial was developed on Microsoft Windows 10.
* You are using two platforms hand-in-hand:
   * **Git GUI** downloaded on your computer (also available for MacOS and Linux).
   * **GitHub Website** accessed through most web browsers.

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

### 1. Installation

#### Git GUI

* We will use Git GUI to interface with GitHub's Website.
* Download the "64-bit Git for Windows Portable" version: [https://github.com/git-for-windows/git/releases/download/v2.23.0.windows.1/PortableGit-2.23.0-64-bit.7z.exe](https://github.com/git-for-windows/git/releases/download/v2.23.0.windows.1/PortableGit-2.23.0-64-bit.7z.exe)
   * Note: This link may break as new versions are released, if so go to: [https://git-scm.com/download/](https://git-scm.com/download/)

[![.img/step01a.png](.img/step01a.png)](#nolink)

* Unzip the file find and run "".
* After choosing your language setting and you will be presented with your working environment.

#### GitHub Website

* You must sign up for a free account with GitHub at [www.github.com](www.github.com) and sign in.

[![.img/step01b.png](.img/step01b.png)](#nolink)

**After downloading and installing Git GUI and registering for a GitHub account, you should be able to complete a typical Git workflow within the next 10 minutes.**

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------


### 2. New Repository

#### Create a New Repository on GitHub

* We will create a new **repository** and **initialize** it to begin using the _repos_ (short for repository).
* After you log in, click on the green "New" button:

[![.img/step02a.png](.img/step02a.png)](#nolink)

* Give your repository a name (e.g. "TEST"), click on "Initialize this repository with a README" (this is important), and then click the green "Create repository" button.

[![.img/step02b.png](.img/step02b.png)](#nolink)

* After your new reposity is created, click on the green "Clone or download" button on the top right and copy the information you see here "Clone with SSH", e.g. git@github.com:atet/TEST.git

#### Clone Repository to Local Computer

* We just created the repository on GitHub's platform, let's **clone** that repository so it also exists on your local computer.

[![.img/step02b.png](.img/step02b.png)](#nolink)

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

### 3. Add Files

* You can think of each repos as all the content that comprises a single project.
* Drag and drop all the files you want to include in your project in this folder

[![.img/step03.png](.img/step03.png)](#nolink)

* `git add .` (have this in this section or the next?)

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

### 4. Saving Changes

* By **commit**ing changes, you are telling the Git system that these new, deleted, and/or modified files are ready to be incorporated in the main repository.
   * You will not see any changes on GitHub at this point.

[![.img/step04a.png](.img/step04a.png)](#nolink)

* By **push**ing all your commits, everything gets incorporated to the master branch.
   * You will now be able to see all your commits on GitHub now.

[![.img/step04b.png](.img/step04b.png)](#nolink)

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

### 5. Typical Workflow

* Identify breakpoints in a project and organize your efforts (and commits) around them:
   * "_Initial commit of project framework including X, Y, and Z._"
   * "_Implemented backend code to allow users to sort GUI results table._"
   * "_Fixed login bug #2 that caused QA's 'Unknown User' error._"
* Once you start getting used to the version control workflow, you'll notice it's mostly just `add` → `commit` → `push`.

[![.img/step05.png](.img/step05.png)](#nolink)

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

### Epilogue

* Anyone can incorporate Git into their development workflow and immediately gain benefits:
   * **Redundancy and Backup**: Copies of your files will exist in multiple locations (on the GitHub platform, your computer, collaborators, etc.)
   * **Versioning**: Revert back to any previous version of your repos
* This was a quick introduction, but Git can be more powerful (and complex):
   * **Branching**: Collaborators can work on their own branch without affecting anyone else's and submit changes for review
   * **Command Line Access**: Quickly `add` → `commit` → `push` through a terminal instead of GUI drag-dropping

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

### Additional Tutorials

Title | Link
--- | ---
Git Concepts | [https://git-scm.com/book/en/v1/Getting-Started-Git-Basics](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics)
GitHub's Web-GUI Introduction | [https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)
Git Commands Cheatsheet | [https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

### GitHub vs. other Git platforms

* Git and GitHub are two different systems that work together:
   * Think of GitHub as a service like Dropbox or OneDrive, both providing cloud storage that can be accessed from the Windows operating system
   * Think of Git as that common operating system that can access different service providers
* GitHub is a popular service provider that will host your repository online, but there are many others that can be accessed with the same Git GUI or Git through command line and use the same workflow:

Company | Service | Website
--- | --- | ---
Microsoft | GitHub | www.github.com
Atlassian | Bitbucket | www.bitbucket.org
GitLab, Inc. | GitLab | www.gitlab.com

[Back to Top](#table-of-contents)

--------------------------------------------------------------------------------------------------

<p align="center">Copyright © 2019-∞ Athit Kao, <a href="http://www.athitkao.com/tos.html" target="_blank">Terms and Conditions</a></p>