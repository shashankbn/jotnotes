
# Create and push new repo

- echo "# Readme" >> README.md
- create .gitignore file , if not already created
- git init
- git add .
- git commit -m "first commit"
- git branch -M master
- create repo in Github (don't select Add .gitignore template or any readme file)
- git remote add origin https://github.com/shashankbn/<reponame>.git
- git push -u origin master