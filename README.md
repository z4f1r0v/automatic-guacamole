# Automatic Guacamole <img src="https://image.flaticon.com/icons/png/512/877/877724.png" width="64" height="64" /> [![Build Status](https://travis-ci.com/z4f1r0v/automatic-guacamole.svg?branch=master)](https://travis-ci.com/z4f1r0v/automatic-guacamole)
You have a great idea for an open-source project but get discouraged from having to wire up all many small finicky details?
You'd love to have your tests run at every commit just like Jenkins does it at work?
You like those fancy green `build|passing` icons?

Now you can have your (automatic) guacamole and eat it! 
Automatic guacamole is a small, lightweight, opinionated template Scala project to help you get started in no time,
focusing on what really matters - contributing to the Scala ecosystem :)

Simply clone/fork/replicate, adjust the details to your licking and hack away.

## What's inside
- [Travis](https://travis-ci.com/)
  - before you can use Travis you need to set up your account (using your GitHub account)
  - to get the sweet badge of success you can adjust this README accordingly
- [Mill](http://www.lihaoyi.com/mill/) 
  - Mill is the build tool of choice since it is fast and comes prepackaged in this project. That way the code can be
  run anywhere the repo is cloned
  - useful commands to get you going:
    - learn what is available in your Mill project - `./mill resolve foo._`
    - allow Intellij to recognize your Mill project structure - `./mill mill.scalalib.GenIdea/idea`
    - compile your project - `./mill -i foo.compile`
    - run tests - `./mill -i foo.test`
- [uTest](https://github.com/lihaoyi/utest) 
  - a small, tidy and to-the-point library to get you testing
