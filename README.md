# githubFirst
echo "# githubSecond" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M develop
git remote add origin https://github.com/weizhao/githubSecond.git
git push -u origin develop
