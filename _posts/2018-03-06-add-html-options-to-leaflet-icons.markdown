---
title: add-html-options-to-leaflet-icons
date: 2018-03-06T21:43:35-05:00
---
## Add HTML Options to Leaflet.js Icons

Early on in our work on [Cash Flow PA](http://www.cashflowpa.org/), we landed on using the [Leaflet](http://leafletjs.com/) JavaScript plugin for displaying data on maps. Leaflet is nice to work with out of the box and easy to configure for some applicaitons, but can be difficult to work with if you expecting the library to anticipate your every move.

The HTML icon is a case in point. Out of the box, Leaflet allows you configure certain parts of the icon object, but it doesn't easily allow users to add something like a optional HTML elements to an icon. This StackOverflow offers on
