phase0-gps-1
============

Phase 0 GPS 1.1

1  git clone https://github.com/hoathenguyen85/phase0-gps-1.git
Cloned my git repository onto my local machine
2  cd phase0-gps-1/
Changed directory
3  touch awesome_page.md
4  git add awesome_page.md
Adding the page to the cloned repository I created with "git add"
5  git commit -m "Added - awesome_page.md yaaaaygit add awesome_page.md "
Commits the added file my local repository wuth the message. Like making a save point!
6  git push
Pushes my commits to github
git push <remote> <branch>
Without arguments it pushes to origin and master branch
7  ssh-keygen -t rsa -C "hoathenguyen85@gmail.com"
   42  eval "$(ssh-agent)"
   45  ssh-add ~/.ssh/id_rsa
   46  clip < ~/.ssh/id_rsa.pub
   47  cat ~/.ssh/id_rsa.pub
   48  ssh -T git@github.com
   52  cd phase0-gps-1/
   53  git push
   55  git --help
   56  git remote set-url origin git@github.com:hoathenguyen85/phase0-gps-1.git
   57  git push
900  git checkout -b add-command-log
Made a new branch! and switches to the new branch as well.
