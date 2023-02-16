# GIT Procedure

## Manage multiple GIT accounts

[![Build Status](https://img.shields.io/badge/%20-Youtube-red)](https://www.youtube.com/watch?v=lLgWWtOk7gk&t=37s)
the video helps in developing the environment for to GIT accounts on the same system
also requires [GIT](https://git-scm.com/) to run

### _New repo initialization when working with two git accounts_

Initialize a new repo on github and add a plane Readme.md file from the same page.
Now go and clone this repo with a Readme.md file to start the project

```sh
-- git clone git@github.com-personal:Giri-Aayush/Nextjs_Learn.git
cd 'folder-name'
```

In this case the folder is Nextjs_Learn.
Now you can continue to developing the project and make changes as you like
##Personal
```sh
git status
git add .
git config user.email "aayushgiri1234@gmail.com"
git config user.name "Giri-Aayush"
git commit -m "1st commit"
git push
```
##Work
```sh
git status
git add .
git config user.email "aayush.giri@joinclamp.com"
git config user.name "Aayush-Giri-Clamp"
git commit -m "1st commit"
git push
```
