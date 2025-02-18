# JavaScript Day 2 Exercises

* **Purpose** - To gain familiarity the following features
  * loops
  * arrays
  * iterables
* **Description** - Please complete the hands on exercises on [slides](https://docs.google.com/presentation/d/e/2PACX-1vTLTPpI0CX-AxgZIFuTKe4BgrEKyPFrEN9EktgLv5ep0xHf3cbxi8HymgCwmoyunA/pub?start=false&loop=false&delayms=3000#slide=id.p22) 22 to 26





## How to Download

#### Part 1 - Forking the Project
* To _fork_ the project, click the `Fork` button located at the top right of the project.


#### Part 2 - Navigating to _forked_ Repository
* Navigate to your github profile to find the _newly forked repository_.
* Copy the URL of the project to the clipboard.

#### Part 3 - Cloning _forked_ repository
* Clone the repository from **your account** into the `~/dev` directory (or the parent directory of your repositories).
  * if you do not have a `~/dev` directory, make one by executing the following command:
    * `mkdir ~/dev`
  * navigate to the `~/dev` directory by executing the following command:
    * `cd ~/dev`
  * clone the project by executing the following command:
    * `git clone https://github.com/${MYUSERNAME}/${NAMEOFPROJECT}`

#### Part 4 - Setting upstream remote
* Link the local repository just created with the original you forked from 
  * If new content is added to this repository, you can pull the new changes, but the remote 'origin' points to your forked version
  * Add another remote and call it 'upstream':
    * `git remote add upstream https://github.com/Java-Full-Stack-TEK/javascript_day-2-exercises`
* To fetch or pull changes, we tell git to look at the Github upstream remote (pointing here) instead of the origin remote (which points to your fork):
  * For git to try and merge changes, we use git pull <remote> <branch>:
    * `git pull upstream master`
  * In case there of a merge conflict, we can update all remote branches, but save merging for later using git fetch <remote>:
    * `git fetch upstream`




## How to Submit

#### Part 1 -  _Pushing_ local changes to remote repository
* from a _terminal_ navigate to the root directory of the _cloned_ project.
* from the root directory of the project, execute the following commands:
    * add all changes
      * `git add .`
    * commit changes to be pushed
      * `git commit -m 'I have added changes'`
    * push changes to your repository
      * `git push -u origin master`

#### Part 2 - Submitting assignment
* from the browser, navigate to the _forked_ project from **your** github account.
* click the `Pull Requests` tab.
* select `New Pull Request`
