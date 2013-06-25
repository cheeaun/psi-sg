PSI SG
======

A super duper quick and simple web app that displays the PSI and PM2.5 readings in Singapore. Data is scraped from the [National Environment Agency](http://app2.nea.gov.sg/) web site.

Web site: <http://cheeaun.github.io/psi-sg/>

Tips and tricks
---------------

- Double-click to switch between night and day modes.
- On touch devices (tested on iOS), pinch with two fingers to switch between the modes.

Technical details
-----------------

- [YQL](http://developer.yahoo.com/yql/) for scraping data.
- [CSS to XPath](http://css2xpath.appspot.com/) for converting CSS selectors to XPath.
- `localStorage` for storing the night mode.
- `CORS` for cross-domain AJAX.
- CSS Transform for resizing the PSI number based on viewport dimension.

License
-------

This app is licensed under the [MIT license](http://cheeaun.mit-license.org/). The data is copyrighted by the [National Environment Agency](http://app2.nea.gov.sg/).

Other similar apps
------------------

- [Singapore PSI](http://dashsell.com/sgpsi)
- [Singapore Air Polution: Real-time Air Quality Index](http://aqicn.org/city/singapore/north/)