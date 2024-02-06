Git tutorial: https://www.youtube.com/watch?v=RGOj5yH7evk&ab_channel=freeCodeCamp.org
tutorial2:https://www.youtube.com/watch?v=Ez8F0nW6S-w&ab_channel=ApnaCollege

git -is a open and free version control system - you can install git in your device and track your changes.
all your files together called as repository.

github - is a website, which host your repositories

you can move the contents/files from your location machine to github website and viseversa using git tool.

some of the important terms in git:
clone- to download the repository from github to local machine
pull - to pull single file/few to from repository
push - reverse of above
commit- to save content in git 
add - add any file to git system 

clone/pull - the file you want to edit from github to local machine/else use the local one.
first make changes to your local file
add to git software
the commit it - it will have the version info now w.r.t previous
push it to move it to github

using github:
First log in to Github
user name: dvikramgoud@gmail.com
password:Visha1@7 (or Visha1@d - same for mail id as well both)

Once you login, for every project(topic), you can create new repository
once you create it, add your files - using create new file under code option.

readme.md ia added as the file name.. md extention means markdown.
then type text you want to add and commit it. while commiting the file - you can give message related to this commit.
for every commit we can give different message - so that it will be easy to track.

adding headings and other paragraphs.
# for main header.
## for sub


# connecting to visual studio
open terminal in the visual studio (click on three dots present on the top )
then in Github, click on code in green color, it will give clone option - copy the ssh key
then enter: git clone that ssh code
it will clone the repository into your local machine.

#adding public ssh key to github
to add new public ssh key to github
enter this in your terminal 
ssh-keygen -t rsa -b 4096 -C "dvikramgoud@gmail.com"
or
ssh-keygen -t ed25519 -C "dvikramgoud@gmail.com"

press enter 3times

then the following file will be created
C:\Users\dell\.ssh\id_ed25519.pub

then copy the content of this file 
paste it in the website in the new ssh key content location, you can give any name of your wish.

it will save your device info to save/edit- your github content.

# cloning the content from git to local machine.
frist copy the ssh clone command from code option in the repository
then enter
git clone command
eg:
git clone git@github.com:dvikramgoud/github_tutorial.git

it will download the content from git to the local machine.


# for adding the content in the next line use br as shown in the below, initially all lines were showing up in continuous mannar
# even though we added them in next line
vik<br>ram

