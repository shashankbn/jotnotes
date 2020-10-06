
# Create and push new repo

echo "# Readme" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/shashankbn/<reponame>.git
git push -u origin main