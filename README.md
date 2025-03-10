# testcafe-reporter-dashboard
[![Build Status](https://travis-ci.org/aleks-pro/testcafe-reporter-dashboard.svg)](https://travis-ci.org/aleks-pro/testcafe-reporter-dashboard)

This is the **dashboard** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

<p align="center">
    <img src="https://raw.github.com/aleks-pro/testcafe-reporter-dashboard/master/media/preview.png" alt="preview" />
</p>

## Install

```
npm install testcafe-reporter-dashboard
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter dashboard
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('dashboard') // <-
    .run();
```

## Author
aleks-pro 
