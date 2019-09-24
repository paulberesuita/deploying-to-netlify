# deploying-to-netlify

## STEPS TO DEPLOY TO NETIFLY USING NUXT


## Local Project Setup

``` bash
# install vue cli
$ npm install vue-cli -g

# create nuxt starter
$ vue init nuxt/starter deployapp

# navigate to app
$ cd deployapp

# install deployapp dependencies
$ npm install

```

## Setup app for Github

``` bash
# initializes git
git init

# stages all files to be committed 
git add .

# commit (locally)
git commit -m "Initial commit"

```

## Pushing app to Github
``` bash
Go to Github and create an empty repo and get the clone url

# run the following to push to remote repo
git remote add origin git@github.com:paulberesuita/project-name.git
git push -u origin master

```

## Pushing to Netifly
``` bash
# Generate the dist folder
npm run generate
# Got to Netifly site and connect to the repo created
# Make sure in Build Command is setup to "npm run generate" and Public Directory to "dist"
# Click Deploy Site
```
