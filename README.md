# Analysis of taxi traffic in New York using PySpark

The implementation as well as the explanations are presented in the notebook **taxi_analysis.ipynb**.

## Data

The data can be accessed with the following [link](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page). However, in this case it is employed the two uploaded csv:

* Truncated dataset of picked taxis in January 2017, **tripdata_2017-01.csv**.
* List of taxi zones, **taxi+_zone_lookup.csv**.

## Study Cases

In every case, it is measured the computational time as well as the data processed and the velocity. Mention the initial time is obtained in the moment one action is executed, in order to be more accurate. Three study cases are carried out:

* Speed per hour: show how the averaged velocity of the taxis evolves per hour during a day.
* Most common taxi trips: the most common taxi trips in January 2017.
* Classifier: knowing some of the attributes provided in the dataset, it predicts if the corresponing person/people left some tip or not, without taking care of the amount.
