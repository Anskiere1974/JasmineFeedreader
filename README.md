# Project Overview

In this Udacity project you help a "fictional" company with a new project and Jasmine testing. Their coders left the company in a hurry and now they need help with Jasmine testing a new feed reader project. You can find the original project at [https://github.com/udacity/frontend-nanodegree-feedreader](https://github.com/udacity/frontend-nanodegree-feedreader). This project is part of Udacity's [Front-End Web Developer Nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001). 

## Viewing the project

You can find a demo of my project at

## Download the project

* You can clone the repository at or
* Click the `Download Zip`Button
* After downloading open `index.html` to view the project.

Note: I implemented _Jasmine JQuery_ in index.html

## Testing, testing, testing

According to the Project Rubric I wrote the following tests:

* Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
* Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
* Wrote a new test suite named `"The menu"`.
* Wrote a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
* Wrote a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
* Wrote a test suite named `"Initial Entries"`.
* Wrote a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
* Wrote a test suite named `"New Feed Selection"`.
* Wrote a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
* No test is dependent on the results of another
* Callbacks are used to ensure that feeds are loaded before they are tested.

## Resources

- [JavaScript Testing Course (Udacity.com)](https://www.udacity.com/course/javascript-testing--ud549) 

- [Jasmine Documentation](https://jasmine.github.io/2.1/introduction)

- [jasmine-jquery (GitHub)](https://github.com/velesin/jasmine-jquery)

  ​

