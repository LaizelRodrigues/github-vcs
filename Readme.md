echo "# github-vcs" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/LaizelRodrigues/github-vcs.git
git push -u origin main
