# Github Task

### Establish a new directory

```bash
mkdir github_task
```
### populating script files with some content

```bash
touch script1.sh script2.sh
echo > "Hello world from script1.sh file"
echo > "Hello world from script2.sh file"
```

### Initiate an empty repository on GitHub, convert the local directory into a Git repository, and link it to GitHub for pushing the code into the repository.

```bash
git init
git commit -m "This is a test commit msg"
git branch -M main
git remote add origin https://github.com/visshnnu-tejaa-98/github_task.git
git push -u origin main

```

link to other tasks: https://github.com/visshnnu-tejaa-98/Devops/tree/main/Activities
