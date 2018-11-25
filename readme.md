# e's notes

* Since this is node.js and not python, there are a few differences
* I'd recommend an editor like Atom. You don't have to use Atom but I guarantee it'll make your life easier with how customizable it is.
* First, fork this repo to give you your own copy to do all your work on
* Clone it down to your machine in your terminal by cd'ing into your umbrella folder where you want your project folder and `git clone {url}` (obviously without the brackets)
* cd into your new project directory
* Back in your terminal, `npm i` or `yarn`. This is to tell your console to download all the dependencies for the test suite (in other projects like with React, it's to run your project locally).
* if you installed Atom, `atom .` will open that folder in Atom and show you all the different files to work on.
* Each of the store folders has the file that is tested and a linked file with your faux database in it. The goal of this is for you to return the value that is asked for.
i.e. (/store1/index.js first question's solution):
`// Return the value '4.63' from store1
function accessesingData1() {
  return store1['2015-01-08'][0][1]
}`
* To check if you have that right, now that you've `npm i`'d or `yarn`'d already, you can `npm test` or (I think... I've only recently started using yarn) `yarn test` and your console will give you a read of every question and your answers/responses with the response it was expecting and the response it got.


## Crushing Candy Code

A local chain of candy stores has hired you to draw conclusions from their sales data. This is made difficult by the fact that each store keeps track of their own inventory sales in a slightly different manner. Use the data sets contained in each folder to complete the exercises.

### Setup

1. Fork and clone the repo down to your local environment.
1. Run `npm install` or `yarn` to get testing packages.

### Recommended execution of these exercises

Write your code as functions that return the result and then run `npm test ./test/store[#].test.js` on the command line.

For example:

```bash
npm test ./test/store1.test.js
```

### Tips

* Be sure to review dot notation vs. bracket notation and when you need to use one over the other.

* If you're stuck on a problem, move on to a new problem! Maybe you'll learn something new in a different problem that will help!

* The challenge questions are _not_ required.
