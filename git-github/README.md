# For new repository
echo "# DevOps" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/redwanpp/DevOps.git
git push -u origin main

# For existing repository
git remote add origin https://github.com/redwanpp/DevOps.git
git branch -M main
git push -u origin main
