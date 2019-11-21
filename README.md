# Cheatsheet

```
1.) git init
```

```
2.) git add .
```

-> adds every file in local git repository in staged mode

```
3.) git commit -m "mycomment"
```

-> unstages with git commit to local repo

```
4.) git remote add origin https://github.com/oguzbits/myappsample
```

-> after origin put in your remote repo url

```
5.)git push -u origin master
```

-> adds local repo to remote repo

--> if 5.) doesnt work do,

```
git push -f origin master
```

but this deletes every file in remote repo and adds local repo to it

## more

--> To push the current branch and set the remote as upstream, use

```
    git push --set-upstream https://github.com/oguzbits/myappsample master
```

--> check status

```
1.) git status
```

--> when you add new files or change local repo

```
1.) git add .
2.) git commit -m "comment again"
3.) git push
```

-> pushes changes to local and remote repo if previously connected

--> remove staged but not committed files, e.g. index.html

```
1.) git rm --cached index.html
```

--> add new branch, e.g. user1

```
1.) git branch user1
```

--> switch to master branch

```
1.) git checkout master
```

-> switch to user1 branch (branch from above)

```
2.) git checkout user1
```

--> clone remote repo

```
1.) git clone https://github.com/oguzbits/myappsample
```

--> pull remote repo

```
1.) git pull https://github.com/oguzbits/myappsample
```
