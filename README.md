#phase0-gps-1
============

##Phase 0 GPS 1.1

###Release 1: Clone the Repo

1.  git clone https://github.com/hoathenguyen85/phase0-gps-1.git
* Cloned my git repository onto my local machine
2.  cd phase0-gps-1/
* Changed directory
3.  touch awesome_page.md
* Create markdown file
4.  git add awesome_page.md
* Adding the page to the cloned repository I created with "git add"
5.  git commit -m "Added - awesome_page.md yaaaaygit add awesome_page.md "
* Commits the added file my local repository wuth the message. Like making a save point!
6.  git push
* Pushes my commits to github
* git push <remote> <branch>
* Without arguments it pushes to origin and master branch
7.  ssh-keygen -t rsa -C "hoathenguyen85@gmail.com"
* Creating key for access to github
8.  eval "$(ssh-agent)"
* Apparently you have to eval to get the agent running?
9.  ssh-add ~/.ssh/id_rsa
* Add the private key to ssh
10.  cat ~/.ssh/id_rsa.pub
* Copy the public key to add to Github for secure communication
11.  ssh -T git@github.com
* Test ssh to Github
12.  git remote set-url origin git@github.com:hoathenguyen85/phase0-gps-1.git
* Whoops, I was supposed to connect using the ssh way, change the origin's url!
13.  git push
* Finally pushing commits to Github 
14.  git checkout -b add-command-log
*Made a new branch! and switches to the new branch as well.

###Release 2: Create a Feature Branch

1.  git branch
* List all the branches available. The star shows current branch you are in
2.  git add README.md
3.  git status
* Show what changes you have made
* Have to add any file you updated!
4.  git commit -m "Updated - README.md with notes how I did this"
5.  git push origin add-command-log
* Gotta push to the right branch