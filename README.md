# testcafe-reporter-slack-personalize
[![Build Status](https://travis-ci.org/patrickvibild/testcafe-reporter-slack-personalize.svg)](https://travis-ci.org/patrickvibild/testcafe-reporter-slack-personalize)

This is the **slack-personalize** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

<p align="center">
    <img src="https://raw.github.com/patrickvibild/testcafe-reporter-slack-personalize/master/media/preview.png" alt="preview" />
</p>

## Install

```
npm install testcafe-reporter-slack-personalize
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter slack-personalize
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('slack-personalize') // <-
    .run();
```

## Author
PatrickVibild 
