# nyc-taxi-fares
**Overview**: This project applies descriptive statistics and hypothesis testing to examine the relationship between payment type and fare amount in NYC taxi fare data. For example: discover if customers who pay using credit cards pay higher fare amounts than customers who use cash.

The dataset contains data about taxi & limousine trips in New York City (NYC). The dataset provides the following details for each trip: -
VendorID
tpep_pickup_datetime - pickup date & time
tpep_dropoff_datetime - dropoff date & time
passenger_count - number of passengers
trip_distance
RatecodeID
store_and_fwd_flag
PULocationID - pickup location ID
DOLocationID - dropoff location ID\
payment_type - Credit Card / Cash / No charge / Dispute / Unknown
fare_amount
extra mta_tax
tip_amount
tolls_amount
improvement_surcharge
total_amount

**Assumptions**:
The sample data comes from an experiment in which customers are randomly selected and divided into two groups: 1) customers who are required to pay with credit card, 2) customers who are required to pay with cash. Without this assumption, we cannot draw causal conclusions about how payment method affects fare amount.
