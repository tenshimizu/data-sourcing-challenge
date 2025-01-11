This repo is for the submission of the Week 6 Challenge for AI Bootcamp. 
### Background

You've been tasked to prepare a dataset for a prediction system that will help the [NOOA Space Weather Prediction CenterLinks to an external site.](https://www.swpc.noaa.gov/about-space-weather) predict Geomagnetic Storms (GSTs).

These storms are caused by so-called Coronal Mass Ejections (CMEs), which are a massive bursts of plasma emitted from the Sun in irregular intervals, that Earth's magnetic shield fortunately renders harmless to us. However, this interaction with the magnetic shield can still create so-called Geomagnetic Storms (which also cause the Northern and Southern Lights) that can be harmful to electronic devices such as satellites, GPS systems, and essential parts of our powergrids.

NASA and the Space Weather Prediction Center operate a number of measuring satellites that collect data on CMEs. This data is then used to warn powergrid operators and GPS system operators ahead of time, so that they can make necessary adjustments.

For this purpose, you'll extract data from the NASA API, specifically from two sources---its GST data and its CME data---then merge the data together and compute the average time it takes for a CME to cause a GST. Later, this data can be used with Machine Learning models to create predictions.

This Challenge has three parts, and must be completed in order:

-   Part 1: Request CME data from the NASA API.

-   Part 2: Request GST data from the NASA API.

-   Part 3: Merge and Clean the Data for Export.
