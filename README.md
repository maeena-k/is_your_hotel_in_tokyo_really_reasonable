## Where to Stay in Tokyo ~ Is Your Hotel REALLY Reasonably Priced ? ~

### Objective
To find reasonable hotels to stay in Tokyo by using a machine learning model

### Problem
* There are so many hotels in booking web services that it is difficult to choose actual one to stay.
* Also complicated filters and tags makes things worse in terms of searching reasonable venues.

### Resolving Scheme
1. Scraping a booking web service to get the dataset of hotels
2. Process the dataset
3. Create a ML model to predict the price of hotel
4. Use the model to see if hotel is reasonably priced

### Data Resource
* <a href="https://bit.ly/2UrfBf2" target="_blank">hotels.com</a> -> hotel dataset (location, price, tags, filters, and so on)
* <a href="https://4sq.com/30rrjdk" target="_blank">foursquare</a> -> location data (API)

## Problem Background
* I've got asked for a hotel recommendation quite often whenever some friends of mine planed to come to Japan for travel.
* What they wanted to know was in short "which hotel/area is cheap to stay?".
* I think most of exisiting booking services don't suitably provide a nice UI for an answer to this question.
* I hope this project to be a solution to the more satisfying and convincing choice of hotel.
