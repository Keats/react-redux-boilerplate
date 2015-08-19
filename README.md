# react-redux-boilerplate
[![Build Status](https://travis-ci.org/Keats/react-redux-boilerplate.svg?branch=master)](https://travis-ci.org/Keats/react-redux-boilerplate)
[![Dependency Status](https://david-dm.org/Keats/react-redux-boilerplate.svg)](https://david-dm.org/Keats/react-redux-boilerplate)


## Known issues
Karma doesn't refresh some cached files and thus run some stale tests: in my case modifying tests in tests/components/addForm_tests.js for example only use the initial file to be served.
There is an issue on that: https://github.com/karma-runner/karma/issues/1087
