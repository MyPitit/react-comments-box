# React Comments Box Tutorial

## What
This repo is designed for `FAC8 students` from [Founders and Coders](www.foundersandcoders.com), in order to teach them [React](https://facebook.github.io/react/index.html).


## How
Into this tutorial we are going to learn how to build a simple but very realistic comments box.

This is how is going to look like:

![react_tutorial](https://cloud.githubusercontent.com/assets/2573931/16735861/8b5dc766-4782-11e6-893d-7d06b7827499.png)


This tutorial is from the official  React](https://facebook.github.io/react/index.html), click [here](https://facebook.github.io/react/docs/tutorial.html) documentation, click [here](https://facebook.github.io/react/docs/tutorial.html) to see more details.

## Let's get started!

Before we go any further download [this]([react-tutorial-master.zip](https://github.com/MyPitit/JavaScript-Tutorial/files/357369/react-tutorial-master.zip)) zip file which contains all you need to get get started.

+ Open `public/index.html` file in Atom or nay other text editor.

You should see something like this:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>React Tutorial</title>
    <!-- Not present in the tutorial. Just for basic styling. -->
    <link rel="stylesheet" href="css/base.css" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.2.0/react.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/15.2.0/react-dom.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.6.16/browser.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.2.2/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/remarkable/1.6.2/remarkable.min.js"></script>
  </head>
  <body>
    <div id="content"></div>
    <script type="text/babel" src="scripts/example.js"></script>
    <script type="text/babel">
      // To get started with this tutorial running your own code, simply remove
      // the script tag loading scripts/example.js and start writing code here.
    </script>
  </body>
</html>
```

+ Remember to start the server before writing any code:

```
npm install
node server.js
```

You server will run on `http://localhost:3000`.

As in this tutorial we do not have any live-reloading, you will need to refresh your browser to see the updates after saving your changes.



+ Let's go to `scripts/example.js` and delete all the code. We are going to build our Comment Box here.

+ Awesome! Once you have deleted the code let's build the `CommentBox` component, which is going to be a simple `<div>`:



## Stretch goals
Style the Comments Box using [SASS](http://sass-lang.com/guide)!
