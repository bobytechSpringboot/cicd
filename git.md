# How to content to gitHub?

## Clone empty repo and add files

## or create a new repository on the command line
<pre>
echo "# cicd" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/bobytechSpringboot/cicd.git
git push -u origin main
</pre>

## or push an existing repository from the command line
<pre>
git remote add origin https://github.com/bobytechSpringboot/cicd.git
git branch -M main
git push -u origin main
</pre>

# How to change user name and email
## Setting Global Git Username and Email
<pre>
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"
</pre>
it is in file ~/.gitconfig

## setting Username and email For a Single Repository
<pre>
git config user.name "Your Name"
git config user.email "youremail@yourdomain.com"
</pre>
It is in file .git/config