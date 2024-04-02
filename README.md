### Step by step instruciton

1. Create new folder

```
mkdir new-project
```

2. Go to new folder

```
cd new-project
```

3. Create file and write content

```
echo "# init" >> README.md
```

4. Initialize repo

```
git init
```

5. Add fille to commit

```
git add README.md
```

5. Commit file with comment

```
git commit -m "init"
```

6. Add remote repo from github (should be created before)

```
git remote add origin git@github.com:morke/new-project.git
```

7. Push changes in repo in main branch

```
git push -u origin main
```

8. For create new branch from current use command - branch (like on example)

```
git branch development
```

9. For switch between branches use command checkout

```
git checkout development
```

10. Add any content in README.md use any editor

### Some Notes

1. For merge branches use command merge. For example if we want to merge from development to main we should do

```
git checkout main
git merge development
```

2. For check statuses use command

```
git status
```
