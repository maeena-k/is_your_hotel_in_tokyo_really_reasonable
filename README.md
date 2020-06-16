## Where to Stay in Tokyo ~ Is Your Hotel REALLY Reasonably Priced ? ~

### Objective
To find reasonable hotels to stay in Tokyo

### Problem
* There are so many hotels in booking web services that it is difficult to choose actual one to stay
* Also complicated filters and tags makes things worse in terms of searching reasonable venues

### Resolving Scheme
1. Scraping a booking web service to get the dataset of hotels
2. Explore the dataset and build a hypothesis 
3. Create a machine learning model to predict the price of hotel
4. Use the model to see if hotel is reasonably priced

### Data Resource
* <a href="https://bit.ly/2UrfBf2" target="_blank">hotels.com</a> -> hotel dataset (location, price, tags, and so on)
* <a href="https://4sq.com/30rrjdk" target="_blank">foursquare</a> -> location dataset (to see which areas are popular and if its relevant to hotels' price there)

## Problem Background
* I've got asked for a hotel recommendation quite often when some friends of mine planed to come to Tokyo for travel.
* What they wanted was in short "which hotel/area is cheap to stay?".
* It feels that most of exisiting booking services don't suitably provide an answer to this question (assumingly because of too much information on their websites).
* I hope this project could be a solution to the more satisfying and convincing choice of your hotel in Tokyo as well.
