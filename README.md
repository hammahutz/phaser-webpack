# Phaser Webpack

## What?

Phaser setup with webpack that integrates with Github Action and auto deploys to Github Pages.

## Why?

For my personal learning about Phaser, NPM, Webpack, Github Pages and CI/Github Action.

## How?

Then pushes to master branch it triggers the action to install dependencies with NPM, build with Webpack and deploys with
Github Action to Github Pages

### Instruction

Instructions to start development with the template

#### Install

Instruction on how to install

1. Clone the repo
1. __OPTIONAL__ Make a new branch, ex "develop"
1. Run "npm update"

#### Development

How to develop your phaser game

* The development files is in src
* Use "index.html" and "style.css" to make the static website
* Make your phaser game in "game.js"
* Put your scenes in the "scenes" folder
* Put your images, sounds, music in the folder assets

#### Build and start

How to build and start the phaser game

* "npm run dev" for a developing build
* "npm run build" for build a publishable build
* "npm run start" for start the local server and view your game
  * __ALTERNATIV__ run liveserver on Visual Studio Code

#### Publish to github pages

When the repo is publish to the main branch the github action triggers an deploy and publish the phaser game to github pages

Deploys to: https://"USERNAME".github.io/"REPONAME"

* Merge your "develop"-branch on github
* __ALTERNATIV__ Push directly to the main branch

## Credit

__TODO__ Add credit
