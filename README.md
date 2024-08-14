## Setting up my Git Repository

<h3>1. Instructions to set up local folder to point to GitHub</h3>

```BASH
echo "# colmaracademy" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/xuncsg/colmaracademy.git
git remote -v
git push -u origin main
```
<h4>* If pushing an existing repository from the command line </h4>

```BASH
git remote add origin https://github.com/xuncsg/colmaracademy.git
git branch -M main
git push -u origin main
```
