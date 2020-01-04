# NYC-Taxi-Trips

This is an data analysis project of NYC taxi trips from 2009 to 2012. Here you have instructions to reproduce the results.

[TOCM]

## Getting the data

To reproduce the results, first of all you have to get the dataset and create a folder named "data" in the principal folder (NYC-Taxi-Trips). The links to the datasets can be found below.

|         Dataset        |                  Description                  |
|:----------------------:|:---------------------------------------------:|
| [2009](https://s3.amazonaws.com/data-sprints-eng-test/data-sample_data-nyctaxi-trips-2009-json_corrigido.json), [2010](https://s3.amazonaws.com/data-sprints-eng-test/data-sample_data-nyctaxi-trips-2010-json_corrigido.json), [2011](https://s3.amazonaws.com/data-sprints-eng-test/data-sample_data-nyctaxi-trips-2011-json_corrigido.json), [2012](https://s3.amazonaws.com/data-sprints-eng-test/data-sample_data-nyctaxi-trips-2012-json_corrigido.json) |       Taxi Trips data in New York City.       |
|         [Vendor](https://s3.amazonaws.com/data-sprints-eng-test/data-vendor_lookup-csv.csv)         |           Taxi Service Company Data           |
|         [Payment](https://s3.amazonaws.com/data-sprints-eng-test/data-payment_lookup-csv.csv)        | Map between prefixes and actual payment types |

## Dependencies

The analysis was made using some python libraries. Install the dependencies from "requirements.txt" to get the correct versions.

```sh
$ pip install -r requirements.txt
```
