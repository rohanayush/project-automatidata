# Automatidata


## Dataset
> Dataset can be found [Yellow Taxi File](https://github.com/rohanayush/project-automatidata/blob/main/2017_Yellow_Taxi_Trip_Data.csv)

This project uses a dataset called 2017_Yellow_Taxi_Trip_Data.csv. It data gathered by the New York City Taxi & Limousine Commission and published by the city of New York as part of their NYC Open Data program. This is a sample ,drawn from the 113 million rows in the 2017 Yellow Taxi Trip Data table.

**The dataset contains**

**22699 rows – each row represents a different trip**

**18 columns**

#### Dataset Schema 
| Column Name               | Description                                                                                                                                                       |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ID                        | Trip identification number                                                                                                                                        |
| VendorID                  | A code indicating the TPEP provider that provided the record.<br>1= Creative Mobile Technologies, LLC;<br>2= VeriFone Inc.                                       |
| tpep_pickup_datetime      | The date and time when the meter was engaged.                                                                                                                    |
| tpep_dropoff_datetime     | The date and time when the meter was disengaged.                                                                                                                  |
| Passenger_count           | The number of passengers in the vehicle.<br>This is a driver-entered value.                                                                                      |
| Trip_distance             | The elapsed trip distance in miles reported by the taximeter.                                                                                                    |
| PULocationID              | TLC Taxi Zone in which the taximeter was engaged.                                                                                                                 |
| DOLocationID              | TLC Taxi Zone in which the taximeter was disengaged.                                                                                                              |
| RateCodeID                | The final rate code in effect at the end of the trip.<br>1= Standard rate;<br>2=JFK;<br>3=Newark;<br>4=Nassau or Westchester;<br>5=Negotiated fare;<br>6=Group ride |
| Store_and_fwd_flag        | This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server.<br>Y= store and forward trip<br>N= not a store and forward trip                                     |
| Payment_type              | A numeric code signifying how the passenger paid for the trip.<br>1= Credit card;<br>2= Cash;<br>3= No charge;<br>4= Dispute;<br>5= Unknown;<br>6= Voided trip      |
| Fare_amount               | The time-and-distance fare calculated by the meter.                                                                                                              |
| Extra                     | Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges.                                            |
| MTA_tax                   | $0.50 MTA tax that is automatically triggered based on the metered rate in use.                                                                                 |
| Improvement_surcharge     | $0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015.                                              |
| Tip_amount                | Tip amount – This field is automatically populated for credit card tips. Cash tips are not included.                                                            |
| Tolls_amount              | Total amount of all tolls paid in the trip.                                                                                                                       |
| Total_amount              | The total amount charged to passengers. Does not include cash tips.                                                                                                |

## Exploratory Data Analysis



