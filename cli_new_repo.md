# New Repo

To create a new repository "new_repo":

```console
echo "# new_repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:oolongyuan/new_repo.git
git push -u origin main
```

To push an existing repository:

```console
git remote add origin git@github.com:oolongyuan/new_repo.git
git branch -M main
git push -u origin main
```


