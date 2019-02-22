# New York Taxi

### Question: which company performs better in the dataset?

### Steps: 

1. Clean data:
     - Drop zeros in Trip distance and Total amount.
     - Drop outliers in features used in the work.
     - Use the pickup_datetime & dropoff_datetime, generate trip_time for each trip.

3. Define Matrix as Price per mile and Price per minute to evaluate the performance.

4. Use T-test to test the difference between Company 1 and Company 2

5. Use linear regressions to identify whether Company 2 is significantly from Company 1 in the defined features.

6. Conclusions & Concerns
