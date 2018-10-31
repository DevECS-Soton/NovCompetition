# Challenge
Your only challenge is to do something interesting with the dataset provided, though it would be nice if the work had a visual component.

You could for example:

* Produce a heatmap of pickup and destination points for a certain time of day
* Detect price discrepancy based on similiar journey distances and routes
* Determine statistics about an individual driver such as kilometers travelled, or hours worked
    * Services such as OSRM can be installed and used to estimate optimal route distances and paths

## Data
The taxi data is supplied as a CSV, and is augmented from the popular NYC taxi dataset(we cannot use Cab My Ride data directly due to GDPR and our responsibility as a data processor) to match the Cab My Ride data schema.

You may find working over the complete range of the data is impractical, due to the number of rows, so feel to partition the data however you feel.

* medallion  - This can be used to uniquely identify a taxi
* hack_license - This can be used to uniquely identify a driver
* payment_type - CSH(cash) or CRD(card)
* total_amount - USD
* pickup_datetime
* dropoff_datetime
* passenger_count
* trip_time_in_secs
* trip_distance - kilometers
* pickup_longitude,pickup_latitude
* dropoff_longitude,dropoff_latitude

### Technologies you could use

* [OSRM: An open source routing engine](http://project-osrm.org)
* [Google Maps SDK](https://developers.google.com/maps/documentation/javascript/tutorial)
* [Orange Labs](https://orange.biolab.si/download/)
    * This product is great for exploritory data analysis, and the Geo plotting capabilities are great for beginners
* [D3.js for Interactive Data Visualisations](https://d3js.org)
* or Microsoft Excel if you feel like it!

### Challenge Submissions

Feel free to share your submissions via git repositorys, slideshows or hosted web pages.

We would be happy to spent some time with you exploring your challenge responses, or answering any questions you may have.