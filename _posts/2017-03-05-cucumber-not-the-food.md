---
layout: default
title: Cucumber (not the food)
excerpt: My 9 year old daughter saw me googling cucumber, and gave me an assignment to write a one page essay on what cucumber (not the food) is.
tags: tech work kids
image-url: '/images/2017/harshal-hirve-50029.jpg'
---

_My 9 year old daughter saw me googling cucumber (the testing framework), and gave me an assignment to write a one page essay on what cucumber (not the food) is._

When you make web sites, one hard part of the job is making sure that everything works. You can test it out yourself as you write the code by clicking around. You have to keep testing over and over again. If you don’t, you will make mistakes, and the web site won’t work.

Humans are not that good at testing. We get bored doing the same test over and over again. We are also very slow, so it takes up a lot of our time. That time could be spent doing other things, like writing more code.

[Cucumber](https://cucumber.io/) is the name of a testing tool. It allows you to write code so that a computer can do your tests for you. This is nice because you can run all the tests really fast, and as often as you want. If you make a mistake writing your web site, you learn about that mistake right away, and can fix it.

Cucumber is a bit different than other testing tools. Instead of writing code that looks like code, you write code that looks like normal writing. This makes it easier for a human, particularly one that doesn’t understand code well, to understand what the test does.

For example, instead of writing this...

`@page.title.must_equal "My Home Page"`

...you might write this...

`The page title should be "My Home Page"`

This allows people who write code to work together with people who don’t write code to describe how the web site should behave. When more different types of people work together on a thing, it generally makes the thing better.

_Cover Image Credit: <a href="https://unsplash.com/search/cucumber?photo=2GiRcLP_jkI">Harshal Hirve via unsplash</a>_
