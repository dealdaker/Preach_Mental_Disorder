# preach_mental_disorder

1.1 How to clone a Git Repository?

You can use Sourcetree, Git from the command line, or any client you like to clone your Git repository. These instructions show you how to clone your repository using Git from the terminal.
From the repository, click + in the global sidebar and select Clone this repository under Get to work.
Copy the clone command (either the SSH format or the HTTPS).
If you are using the SSH protocol, ensure your public key is in Bitbucket and loaded on the local system to which you are cloning.
From a terminal window, change to the local directory where you want to clone your repository.
Paste the command you copied from Bitbucket, for example:

1.2 How to download project?
You can either clone the repository from the github or downlad the zip.
Clone link and download option can be found from right side of the repository  page.C
Clone can be done by using the command

*git clone (repostiory link)*
Here is the repository Link
github.com/dealdaker/preach_mental_disorder

2 COLLABORATING ON GITHUB

2.1 FORK AND PULL MODEL
This is the template used by U of T Coders on their own website and repositories.
The “owner” / “project manager” of the upstream repo assigns rights to “employees”
Employees do not have push access to the main repo (upstream)
The project manager accepts employee Extraction Requests (PRs), examines them, and then merges them into the main repository.

2.2 SOME GIT / JARGON TERMINOLOGIES
REST AND BRANCHES
Description of term
Origin (repo) Your remote repo (on Github); this is the "origin" of your local copy. Either this is a repository you created yourself, or a fork of someone else's GitHub repository.
Upstream (repo) The main repository (on GitHub) from which you forked your GiHub repository.
Local (repo) Repo on your local computer.
Master The main branch (version) of your repo.


2.3 BASIC CONTROLS / ACTIONS
Explanation of the term
Fork Make a copy of someone else's GitHub repository in your own GitHub account.
Clone Make a copy of your GitHub repository on your local computer. In the CLI: "git clone" copies a remote repository to create a local repository with a called remote origin automatically configured.
Sweater You incorporate changes into your repo.
Add Add snapshots of your changes to the "Staging" area.
Commit Takes the files as they are in your staging area and stores a snapshot of your files (changes) permanently in your Git directory.
Push You “push” your files (modifications) to the remote repository.
Merge Incorporate the changes into the branch you are on.
Extract request term used in collaboration. You “issue a pull request” to the upstream repository owner asking them to check out your changes to their repository (accept your work).

2.4 CONFIGURING GLOBAL GIT SETTINGS ON YOUR LOCAL COMPUTER
You only have to do this once; global settings apply to all your git repositories.
Note: Any locale that you initialize in individual git repositories will override the global settings.

username
E-mail
display colors
preferred text editor
The command line git syntax is: verb git

One of you will be the “owner” and one of you will be the “collaborator”.

THE OWNER GIVES COLLABORATORS ACCESS TO THEIR REPO.
Go to your GitHub repository
Add a file called "tenlines.txt" and place the Etherpad text in the file. Validate your modifications.
Click on the Settings tab.
Click on Collaborators
Enter the username of the collaborators

2.5 OWNER'S REPO OF COLLABORATOR CLONES
Go to https://github.com/notifications and accept access to the owner's repo.
On the CLI, clone the owner's repo by issuing the command:
$ git clone URL-of-Origin-Repo Directory-Address-of-Local-Repo

2.6 OWNER'S REVIEW AND ACCEPTS COLLABORATOR CHANGES
Take a look at the owner's GitHub repository and see the new Collaborator commit (s).

Download (extract) changes made by collaborators to the owner's local repository:
$ git pull origin master

3.0 App Objective
The app is used by people with all the facilities of life but still has mental issues. It is basically for businesspeople. This document specifies the requirements for the development and design of an application. The user interface will represent a unique theme and allow the user to use it with ease. The application will use smartphones and the Android operating system that is mostly used is the market.

4.1 User Setup
This module deals with setting up the user with the system. It comprises all the functionalities and interfaces for profile creation, including sign up, logs in, creating a profile, and setting up a dashboard.
User Authentication
This sub-module deals with all the interfaces related to the users' authorization, including registration/Sign Up, Login, Forgot Password, etc.

4.2 Profile Creation
This sub-module deals with the interfaces and functionalities that deal with getting the user's personal information and creating a profile based on that information in the system.

4.3 Dashboard

The dashboard will be shown having the following tabs
•	Hadith for mental disorder
•	Quranic Verse for mental disorder
•	Past Islamic Leaders History
•	Users can set the alarm to fill the computation form daily.
•	The Computations based on Namaz, numbers of good deeds, helping others, etc.
•	The app will generate a score.
•	Users can track daily and weekly performance of computations.
•	Users can search using semantics/meanings.
•	It will provide the most related results to the user.
•	Users can do input using English, Urdu language, and voice.
•	The output will be in English and Urdu and audio.


5.0 Scope
Although our system is finished, we have planned to include the detection of facial expressions. It will search or measure what percentage of mental disorder had. We believe that our system still has growth potential. We will add more functions and widgets to the system. We are taking this as a business opportunity and will market and promote the app using social media and paid campaigns. It will be a passive income source for us.


6.1 User characteristics
Humans will interact directly with the app.
Human beings having age between 25 to 50 Years
No robotics will interact

6.2	Operating environment
Android OS for mobile application. We will develop a mobile application. Android maintained its position as the world's leading mobile operating system in July 2020, controlling the mobile OS market with a 74.6% share. Windows operating system (7,8,10) for application development. IDE (Android Studio), language (Kotlin), supported devices (AVD for Android SDK), database (MySQL).


6.3	System constraints
	Software constraints
	This app only works on the Android operating system.
	It requires an active internet connection to function.
	Requires a MySQL database to function.

6.4 Hardware constraints
o	Mobile phone:
    It will only work on mobile phones and tablets.
    Speed (3-4 GHz), RAM (1 GB)
    Operate on the Internet, therefore, require some battery power.
o	Computer.
    The Hard drive (80 GB), for computer or Laptop, 50GB for the window 10Gb for Android Studio, and 20 Gb for other supporting programs.
    Processor (Core i3)
    Motherboard (Intel dual or quad-core)
o Cultural constraints
    Application is available in English and Urdu Language.
o Environmental constraints 
    This app cannot be used outside of a specified local area.
o User constraints
    Any user who wants to use the app can register as a regular user or a Guest. Must know primary Android phone usage and understand conversational language.

6.5	Hardware Interfaces
•	The only hardware interfaces required for this application are Android Mobile or Tablet.
•	The user will use the Android device for desire tasks.
•	A computer or Laptop is used to develop this application.
•	The device must have DDR3 RAM and a Core i5 processor
•	Both interfaces require an internet connection. No other hardware interface is required.

6.6	Software Interfaces
This application includes the following tools and software interfaces:
IDE: 		Android Studio
Languages: 		XML for GUI and Kotlin for backend
Supported devices: 	Genny Motion, AVD, and Android SDK
Database: 		MySQL

7.0	User Documentation
    All documents will be produced following the requirements for open-source software under the GNU General Public License. This system is user-friendly. The user documentation will include the user manuals provided with the software, related topics for getting help will be available on the Internet. Give directions to the application. There is a unique training section for users on how to use this app.

7.1 User documentation includes the following project-related items:
    Table of contents.
    Short introduction and overview of the application.
    Briefly describe technical details such as hardware and software requirements to run the system.
    Indexes.
    References.

