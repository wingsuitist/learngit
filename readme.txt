apt-get install git
git init
git config --global user.name "your user name"
git config --global user.email "your e-mail"
ssh-keygen -t rsa -C "youremail@example.com"
add ssh key to "https://github.com/settings/ssh"

git clone git@github.com:xx/**.git

git remote add origin git@github.com:xx/*.git
git pull -u origin master
git push -u origin master
git push origin master

