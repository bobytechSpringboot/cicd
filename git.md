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