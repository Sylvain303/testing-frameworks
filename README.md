# testing-frameworks
Comparing and studying multiple testing frameworks working for multiple languages

## About

The idea of this repository is to publish some testcase ported to multiple test frameworks.

It follows my work and the need to maintain legacy code written in multiple language. Languages are currently:

* bash - shell script
* ruby - command line scripts too
* php - legacy web code interacting with system
* perl - parser and command line scripts
* python - new code written from legacy code, need to prevent from regression

## History

First, I was looking for a way to test in multiple languages. I found [TAP](http://testanything.org/)

Then, I wanted to start testing and merging a common testing, for all those shell scripts I produce and maintain daily. I found [bats](https://github.com/sstephenson/bats) from reading the TAP Producers page.

My first, attempt was failing, because of a bug in bats. I fixed it. Thanks opensource.

Now I've found, [urchin](https://github.com/tlevine/urchin) from the bats issues. And the developer also produced a nice [blog post about testing for shell scripts](https://blog.scraperwiki.com/2012/12/how-to-test-shell-scripts/). Which opened some more possibilities. 

So I decided to start working on those testing tools:

* bats
* urchin
* tap related tools - may be related to CI Continuous Integration
* [wvtest](https://github.com/apenwarr/wvtest)

## Measurement

Here is what I will evaluate:

* comfort - an arbitrary feeling about writing cross language test, less typing it better
* speed - fast runner will have better mark
* clarity - easy to teach and easy to install framework will have better mark
