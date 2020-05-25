# Automatic Guacamole [![Build Status](https://travis-ci.com/z4f1r0v/automatic-guacamole.svg?branch=master)](https://travis-ci.com/z4f1r0v/automatic-guacamole)
You have a great idea for an open-source project but get discouraged from having to wire up all many small finicky details?
Now you can have your (automatic) guacamole and eat it! 
Automatic guacamole is a small lightweight opinionated example Scala project. 
Simply clone/fork/replicate, adjust the details to your licking and hack away.

## What's inside
- [Travis](https://travis-ci.com/)
  - before you can use Travis you need to set up your account (using your GitHub account)
  - to get the sweet badge of success you can adjust this README accordingly
- [Mill](http://www.lihaoyi.com/mill/) 
  - Mill is the build tool of choice since it is fast and comes prepackaged in this project. That way the code can be
  run anywhere the repo is cloned
  - useful commands to get your going:
    - learn what is available in your project - `./mill resolve foo._`
    - allow Intellij to recognize your mill structure - `./mill mill.scalalib.GenIdea/idea`
    - compile project - `./mill -i foo.compile`
    - run tests - `./mill -i foo.test`
- [uTest](https://github.com/lihaoyi/utest) 
  - a small tidy and to-the-point library to get you testing
