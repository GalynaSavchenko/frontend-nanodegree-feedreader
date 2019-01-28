# Project Overview

This code is based on the starter project https://github.com/udacity/frontend-nanodegree-feedreader

The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite!

# Tests

* 'are defined". I need to make sure that the allFeeds variable has been defined and that it is not
empty. Experiment with this before you get started on the rest of this project. What happens when you change allFeeds in app.js to be an empty array and refresh the page?
* 'url defined'. Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined
and that the URL is not empty.
* 'name defined'. Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
* 'The menu'. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
* 'menu shows/hides'. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
* 'Initial Entries'. A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
* 'New Feed Selection'. A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development." This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!
