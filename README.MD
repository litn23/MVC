echo "# MVC" >> README.md
git init
git add README.md
git commit -m "first commit"
git tag -a v1.0.0 -m "Release version 1.0.0"
git branch -M main
git remote add origin git@github.com:litn23/MVC.git
git push -u origin main
git push origin --tags