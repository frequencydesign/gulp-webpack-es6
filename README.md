# gulp-webpack-es6

## NPM to Start!

Start by running a blank task!
First, Command-line in the project folder of your choice:
```sh
$ npm install
```

Second,
```sh
$ gulp
```

That's it for now!


## Next, add Webpack and default webpack gulp commands

I added the gulp-util to help colorize console/command line output as well as a few other things I will explain over time.
I added webpack per my preferance and the webpack-dev-server for hot swapping code and simply running a server easily integrated with webpack.

## Installing Babel for Webpack, Bootstrap for quick UI examples, and react-bootstrap

Babel for Webpack will help us take advantage of the latest JavaScript version, while also transpiling the code down to older version for older browsers
Bootstrap and react-Bootstrap will help us get some quick user interface elements up and running. WIth this version, I will be using React.js to build out interface examples. We will install that in the next Git commit.

## Adding Routes!

In a single page application - a web application that acts like a single page - you still need to switch to different "pages". In a Single-page application, these are called "routes" - at least the URLs are.
We are adding react-router to handle that. This seems to be the most popular way to do it for a React app.
We are also adding react-router-bootstrap for some bootstrap integration.



