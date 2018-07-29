# Restaurant-Reviews-project-6

## __Paul Standley__

![Paul Standley](http://res.cloudinary.com/pieol2/image/upload/v1516543296/profile-small.png)

## Mobile Web Specialist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

### _How to run app_

clone [githubRepo](https://github.com/udacity/mws-restaurant-stage-1)

open index.html

### citation

[P6: Restaurant Reviews with Mohammed](https://www.youtube.com/watch?v=jsGs9z7TuyY)

[mwd](https://developers.google.com/web/ilt/pwa/caching-files-with-service-worker)

[bitsofcode](https://www.youtube.com/watch?v=BfL3pprhnms)

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality. 

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write. 

## Steps to complete the project

~~__Fork and clone the starter repository. The code in this repository will serve as your baseline to begin development.
You will need a MapBox API key. Replace the text <your MAPBOX API KEY HERE>inside of main.js with your key. MapBox API is free to use, without providing any payment information.__~~

## Convert the provided site to use a responsive design.

### Bootstrap and other CSS frameworks should not be used; all responsiveness should be done with CSS.

* ~~Use appropriate document type declaration and viewport tags~~
* ~~Create a responsive grid-based layout using CSS~~
* ~~Use media queries that provide fluid breakpoints across different screen sizes~~
* ~~Use responsive images that adjust for the dimensions and resolution of any mobile device~~
* ~~Implement accessibility features in the site HTML (most of this HTML is generated by JavaScript functions).~~

### ~~Add a ServiceWorker script to cache requests to all of the site’s assets so that any page that has been visited by a user will be accessible when the user is offline. Only caching needs to be implemented, no other ServiceWorker features.~~

## Review from Udacity

[Udacity Review](https://review.udacity.com/#!/reviews/1364365)

* ~~The restaurant's name on both the HTML page is enclosed in <h1> tag, but <h1> tag is already being used in the navbar title. This is semantically incorrect so you need to enclose the restaurant name in a heading tag with lower semantic value like <h2> or <h3>.~~

* ~~The map on both the HTML pages needs an appropriate role as it is an external application inside this app which does not have a semantic element.~~

* ~~The <ul> breadcrumb needs an appropriate role as its purpose is navigation but it is not enclosed inside a <nav> tag.~~
