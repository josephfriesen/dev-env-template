# Epicodus Development Environment Template

## Description

Use this template repo for starting new projects while at Epicodus. Update with new technologies and packages as needed. Versions for all packages are pinned according to the version number specified in the Epicodus curriculum.

## Installation Instructions

* Clone this repo.
* *Copy contents to new project:*
  * *Option (1)*: Copy all files from root directory except folder .git and this readme file to a new, empty project folder.
  * *Option (2)*: Rename this repo's local file folder to your project's name, delete this *README.md* file, and, in terminal, run the command:
```
$ rm -rf .git
```
* *Initialize git, install packages:*  In terminal, navigate to your project folder run the following:
```
$ git init
$ npm install
```
* At Epicodus, or in terminal on a Mac, you can build and start the webpack dev server with the command:
```
$ npm run start
```
* At home, in Git Bash on your Windows machine, you need to build first, then start the dev server:
```
$ npm run build
$ webpack-dev-server --open --mode development
```
(note to self -- look into an alternative terminal that wouldn't have an issue with running command npm run start)

* To open karma, run command
```
$ npm test
```
