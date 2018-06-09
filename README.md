# jenkinsfile
echo "# jenkinsfile" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/demo79/jenkinsfile.git
git push -u origin master
