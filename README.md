# reactjs-guide

My personal collection of notes related to Reactjs

## React Events

* Events are delegated to the document level
* Listeners are tracked and therefore only added once

## Testing

[jest - react tutorial](http://facebook.github.io/jest/docs/tutorial-react.html)

### Shallow Rendering

* [egghead video on shallow rendering](https://egghead.io/lessons/react-testing-intro-to-shallow-rendering)
* npm i --save-dev react-addons-test-utils
* get an object back that shows what would have been rendered to the dom

### Testing Interactions

* fake user input, check output
* npm i --save-dev jsom (JEST has built-in)
  - need to create setupDom script to fake dom for react
* 

### Libraries

* React
  - Enzyme (nicer api than react test utils)
    + helpers for shallow renderer
    + easier interaction testing
* Assertion
  - Chai
  - Expect
  - Nodejs/assert
* Testing Framework
  - mocha (no assertion lib included)
  - ava (parallel tests; es2015 built in)
  - jest (built on jasmine;
  - jasmine (built in assertion lib)
  - qunit
* End-to-End Framework
  - Nightwatchjs (selenium)
  - Casperjs (phantom
  - Protractor (selenium)
* Unit Test Runner
  * karma
  * wallabyjs (commercial)

## Resources

* Redux
  - [Getting Started Redux - Egghead](https://egghead.io/courses/getting-started-with-redux)
  - [Building React Applications with Idiomatic Redux - Egghead](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)
* Events
  - [React Events podcast](https://www.youtube.com/watch?v=dRo_egw7tBc)
    + Includes a code walkthrough of synthetic event implementation
* Testing
  - [React Testing Cookbook - Egghead Course](https://egghead.io/courses/react-testing-cookbook)
  - [Testing React Apps](https://www.youtube.com/watch?v=eWN8F_WOBAQ)
  - [Jest talk by Jeff Morrison](https://www.youtube.com/watch?v=5ZEloUxx0FM)
