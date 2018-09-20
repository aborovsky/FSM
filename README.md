# Finite State Machine (FSM)

[![Build Status](https://travis-ci.org/GetmeUK/FSM.svg?branch=master)](https://travis-ci.org/GetmeUK/FSM)

> A minimal finite state machine (FSM) for Javascript.

## Install

**Using bower**

```
bower install --save FSM
```

**Using npm**

```
npm install --save FSM
```

## Building
To build the library you'll need to use Grunt. First install the required node modules ([grunt-cli](http://gruntjs.com/getting-started) must be installed):
```
git clone https://github.com/GetmeUK/FSM.git
cd FSM
npm install
```

Then run `grunt build` to build the project.

## Testing
To test the library you'll need to use Jasmine. First install Jasmine:
```
cd %FSM_project_root_directory%
git clone https://github.com/pivotal/jasmine.git
cd jasmine
git checkout v2.0.3
mv dist/jasmine-standalone-2.0.3.zip ./
unzip -o jasmine-standalone-2.0.3.zip
grunt spec
```

Then open `FSM/SpecRunner.html` in a browser to run the tests.

Alternatively you can use `grunt jasmine` to run the tests from the command line.

## Documentation
Full documentation is available at http://getcontenttools.com/api/fsm

## Browser support
- Chrome
- Firefox
- IE9+
