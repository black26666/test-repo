# test-repo
echo "# test-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/black26666/test-repo.git
git push -u origin main
