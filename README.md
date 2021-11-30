# create a new repository on the command line
echo "# testing_mood" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/goumadje/testing_mood.git
git push -u origin main
