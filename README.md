# react-redux-boilerplate
[![Dependency Status](https://david-dm.org/Keats/react-redux-boilerplate.svg)](https://david-dm.org/Keats/react-redux-boilerplate)


Boilerplate containing a starter environment for react/redux dev:

- babel + eslint
- webpack with hot reload for code
- gulp task for SASS
- react
- redux
- react-redux
- immutablejs

A bunch of tasks exist, look at `package.json` to see them. The main one used while developing is `npm start`.
This starts webpack (including a server on localhost:3000), gulp and karma and watch over the files.


## Example
See https://github.com/Keats/react-example for an example a tiny app following that boilerplate.


## Notes
The script in bin is only tested on linux, it won't work on windows.


## Known issues
Karma doesn't refresh some cached files and thus run some stale tests.
There is an issue on that: https://github.com/karma-runner/karma/issues/1087
