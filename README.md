# phase-0-gps-1
1260  cd ..
#Navigate to the previous directory
 1261  ls -la
#Checks for Git folder using a long listing format
 1262  git clone https://github.com/clr2107/phase-0-gps-1
#Clones the repo to the computer
 1264  cd phase-0-gps-1
#Navigate to the repo
 1265  touch awesome_page.md
#Add the awesome page
 1267  git add awesome_page.md
#Adds awesome_page.md to the staging area
 1268  git commit -m "add awesome page"
#Commits the changes with a commit message
 1269  git push origin master
#Push changes to GitHub master branch
 1270  git checkout -b add-command-log
#Create a new branch and then checkout
 1271  git checkout --help
#Checkout git help
 1272  subl README.md
#Open file in Sublime

