# News Apps (iOS) Coding Challenge

## Introduction
You have been asked to kick off native iOS news app, initially consisting of two screens displaying recent news headlines (fetched from a server).

The first screen will simply display a list of the headlines and their last updated date. When the user selects an item the application then shows the second screen, containing more information.

The user can also trigger a reload of the data from the server. 

### API
The list of headlines is available at

https://raw.githubusercontent.com/fmtvp/recruit-test-data/master/data.json

Note: The returned timestamp is in epoch time but the design calls for this to be a human readable day, month and year. So, for example, "Thursday, 1 January 1970" for an epoch timestamp of 0.

### Analytics
The business analyst needs you to record interaction events as people use the app. This can be done by issuing “fire and forget” GET requests to

https://raw.githubusercontent.com/fmtvp/recruit-test-data/master/stats

Event specific query parameters should be appended to the URL as follows:

event=load – any network request
data=xxx - the time in ms for the complete request

event=display – whenever a screen is shown
data=xxx - the time (in ms) from when the user initiated a request that would show the screen to the point where the screen has been shown

https://raw.githubusercontent.com/fmtvp/recruit-test-data/master/stats?event=load&data=100

This is an opportunity to demonstrate your understanding of what modern iOS app development looks like. We believe that good contributors to achieving this are typically code readability, separation of concerns, the open/closed principle, error handling, unit testing, and an intuitive, responsive, user interface design.

You can write the app in either Swift or Objective C but you should not use any third party libraries. We would typically expect this to take you a few evenings maximum. Remember we are looking for a demonstration of your skills, not perfection. A comment about what you would do next might be better than squeezing in everything, but not doing anything to your usual standard.

To submit your code, please create a private [Bitbucket](https://bitbucket.org) repo (it’s free) and share your code repo with our user, `newsapps-ios`. 

_Please email your BBC Careers contact separately as well to confirm your submission._


