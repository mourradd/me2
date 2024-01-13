# me2
## Sample of code
```bash
   4 git init
   5 git remote add origin 
   6 git branch -M main
    // create a file called main.txt
   9 git add --all
  10 git commit -m "add main"
  11 git push -u origin main
  15 git branch dev
  16 git branch test
  18 git checkout dev
     create 2 files called dev1.txt and dev2.txt
  21 git add --all
  22 git commit -m "add dev1 and dev2"
  24 git push -u origin dev
  25 git checkout test
    // create 2 files called test1.txt and test2.txt
  29 git add --all
  30 git commit -m "add test1 and test2"
  31 git push -u origin test
  32 git checkout main
  34 git merge dev
  35 git merge test
  37 git push
  41 git tag -a v1.4 -m "my version 1.4"
  49 git push origin --tags
```
remove repo locally and remotely

 remove them locally:
```bash
git branch -d test
git branch -d dev
```
 remove them remotely:
```bash
git push origin --delete test
git push origin --delete dev
```
 Create Tag Name
```bash
git tag -a v1.4 -m "Version 1.4"
```
 Push Tag Name
```bash
git push origin v1.4
```
 List Tag Name
```bash
git tag
```
 Delete Tag Locally and remotely
Delete Tag Locally
```bash
git tag -d v1.4
```
 Delete Tag Remotely
```bash
git push origin --delete v1.4
  ![alt text](https://img.freepik.com/free-photo/painting-mountain-lake-with-mountain-background_188544-9126.jpg)
