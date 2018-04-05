# Final Project Proposal

Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas.

## Problem / Question

Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question?


When doing the Cobbs Creek Community Plan in my planning workshop, I realize that as a neighborhood with comparatively lower income and higher poverty rate, Cobbs Creek residents do not have good access to healthy food options. The obesity and diabete rates in Cobbs Creek are higher than city average, which lead to my idea for this application - it is harder for poor people to access and afford a healthy lifestyle, so what about building a website that tells users where they can find affordable healthy food?

The purposes of this application are:
a. Provide healthy food options for users - locations, types, size, price, etc. (depends on what kind of data I can get)
b. Provide information for planning - which areas lack of healthy food options (groceries, healthy corner stores, etc.), where the city should promote or invest in more healthy food.

## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?
(If it is too large for a javascript application, using a backend might
be necessary)


There are two existing datasets that can be used directly:
a. Walkable access for healthy food - blockgroup level
b. Inspection of business licenses - can filter the license types of "food preparing and serving" and business names with "grocery" in them

A existing dataset that may be used:
Locations of farmers markets

There is also an Yelp API on OpenDataPhilly that may be useful, but I don't know how to deal with API, yet - probably will use it if I learn how to use API

## Technologies used

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?

Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users?
- What do they gain from your application' use?
- Are there any website/application examples in the wild to which you can compare your final?

#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.

## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get our help interpreting a technology's
purpose/usage).
