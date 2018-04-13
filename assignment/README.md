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


What I can think of for now: use leaflet, jQuery and underscore to filter (based on the users input) and plot the data. I may also need to do some spatial analysis and try to explore turf, but I will probably use ArcGIS and R to do the analysis jobs and export and transform the data to GeoJson format - ArcGIS and R are the tools that are more familiar to me, and I think doing spatial analysis in GIS is more powerful than those online applications (probably? I don't know exactly... but I will see what I want in the future)

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users?
a. Residents in Philadelphia that want to find healthy food options
b. Planners or communities that are concerned about the health issues

- What do they gain from your application' use?
a. A map showing the accessibility to healthy food options for each blockgroup in Philadelphia
b. Locations (points) for all the groceries and corner stores
c. (probably) A map showing the number of corner stores and groceries for each blockgroup
d. Users can search for specific groceries and corner stores based on their input (depends on what data&the fields in that dataset I can get)
e. Generate a route from users' locations to a store using mapbox (the store can be the one that the users search for, or generate a route to the nearest location that provide healthy food - I am not so sure if I can find the "nearest location" from users' locations in javascript, yet)
Also, it is possible to provide rountes for differnt transit types - walking, cycling, by car, etc., and if possible, the time to get there (not so sure how to do it yet)

- Are there any website/application examples in the wild to which you can compare your final?
Yelp. But I will be providing "healthy food options" in my application, instead of all the resteraunts like Yelp.

#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

a. A top bar for title and input boxes for searches
b. A side bar for detailed information
c. A legend on the map
d. Live demo in Bootstrap is fun, I may use it (don't know how to use it yet, though)

## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.

Things that I am not so sure how to do it yet (listed above)

## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get our help interpreting a technology's
purpose/usage).

I am just going to list something that I may not do in this application but interesting (just to remind me in case I forget these ideas):
a. Corner stores&Groceries rating - is it possible to give a score for each corner stores&groceries? (According to the products they provide, their sizes, environment, cleaness conditions, etc.)
......
