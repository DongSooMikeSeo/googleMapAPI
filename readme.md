# Let's do some policy analyses using data gotten using Google Map API!

Last year, 2019, I began using Google Map API, mainly to caculate actual travel time between two spatial objects, via public transporation (subway, bus). For distance based spatial analysis for NYC, I always thouhgt typical simple buffer analysis (like 100m radius around target), or distance analysis based on actual road network does not make sense, because 1) NYC's non-grid street network is so complicated so simple unconditional buffer irrespect of the actual network would give zero to none insights, 2) not many people drive, most of us rely on MTA. Therefore, I expected my approach would give more real insight on what would be going on.  
 
The data mechanism is just simple, like you, as a non-tech person, put your origin address and destination address in Google map to figure out how long it will take and which train and bus you should take after walking how many minutes. However, thanks to API, I don't need to type in that pair of addresses, so I can easily obtain travel time data for multiple pairs.  

First, I will show some codes to run API and store the extracted data.

Then, I will do some data analyses taking advantage of that travel time data.

Below is a list of analyses (will be updated continuously)

- Which neighborhoods in BK would have benefitted the most from Amanzon HQ2?
- I have an idea but top secret


## Initial codes to run API

