# IS117-A03
Third assignment for IS117-005 course

**Installing and Configuring Webstorm**

Step 1 - Download Webstorm from https://www.jetbrains.com/student/ and install the application.


Step 2 - Download Git from https://git-scm.com/downloads and install it as a local program.

(As an option if already installed, you could uninstall the version of Git you have on your system and install the current version.)


Step 3 - Setup GitHub by creating a GitHub account at https://github.com/join.


Step 4 - Connect GitHub with Webstorm by pressing (Ctrl + Alt +S) to access the system preferences. Then, you select Version Control Git and enter the correct path to the Git executable.


Step 5 - Add your GitHub password to Webstorm by pressing (Ctrl + Alt + S) for system preferences and selecting Appearance and Behavior | System Settings | Passwords


Step 6 - Create a repository by navigating to GitHub. Then, click the + sign in the upper right corner and hoose “Create new repository”.


Step 7 - Make the repository public and add the README.md file. Then, click Create.


Step 8 - Create a repository from Webstorm by selecting VCS and importing into Version Control.


Step 9 - Import a repository from your GitHub account. From the main page, select Checkout from Version Control/Git. Alternatively from within Webstorm, select VCS/Checkout from Version Control/Git. Then, enter the name of the GitHub repository and enter the name of the local path.


Step 10 - Create a Webstorm file by choosing File/HTML/HTML 5 or File/Stylesheet.


Step 11 - The Add to Git dialog should open. To add your files on Git, click Add. This should add your files to your local file system.


Step 12 - Commit your changes by entering updated information in the "Update README.md" section.


Step 13 - Push the change to your remote repository by pressing (Ctrl + Shift + K) or clicking “VCS/Git/Push”


**Your file is now on GitHub!**


Step 14 - Setup your GitHub pages by clicking on Settings and checking the repository name.


Step 15 - Choose the GitHub page location by selecting "Master branch" and noting the published URL.


Step 16 - Check your GitHub pages by copying the GitHub.io URL into a browser. Then, post the URL into Moodle (or Canvas) with your GitHub account URL.



**References Used**

1) Beer, B. (2018). Introducing GitHub. 2ed. O’Reilly Press. 
2) GitHub (2019) GitHub Guides Tutorial. Retrieved  March 19, 2019, from https://guides.github.com/activities/hello-world/ 
3) Jetbrains. (2019). Git.   Retrieved March 21, 2019, from https://www.jetbrains.com/help/webstorm/using-git-integration.html






**Glossary**

1) **Branch:** A parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.

2) **Clone:** A copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.

3) **Commit:** A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.

4) **Fetch:** To add changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.

5) **Git:** An open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.

6) **GitHub:** A provider of Internet hosting that provide a service to an entire organization and use their own identity when performing their function. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks.

7) **Merge:** To take the changes from one branch (in the same repository or from a fork), and apply them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.

8) **Merge Conflict:** A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

9) **Push:** To send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.

10) **Pull:** To fetch in changes and merge them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.

11) **Remote:** The version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.

12) **Repository:** The most basic element of GitHub. They are easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.
