# SQL Query with PySpark
 

The data in this database is from the Bureau of Transportation Statistics, covering the years 2005–2015. The database consists of four tables:

• Flights (fid, year, month_id, day_of_month, day_of_week_id, carrier_id, flight_num, origin_city, origin_state, dest_city, dest_state, departure_delay, taxi_out, arrival_delay, canceled, actual_time, distance) 
• Carriers (cid, name) 
• Months (mid, month) 
• Weekdays (did, day_of_week)


1. Find the distinct flight numbers of all flights from Seattle to Boston by Alaska Airlines Inc. on Mondays. Also notice that, in the database, the city names include the state. So Seattle appears as Seattle WA. [3 rows] 

2. Find the day of the week with the longest average arrival delay. Return the name of the day and the average delay. [1 row] 

3. Find the names of all airlines that ever flew more than 1000 flights in one day. Return only the names. Do not return any duplicates. [11 rows] 

4. Find all airlines that had more than 0.5 percent of their flights out of Seattle be canceled. Return the name of the airline and the percentage of canceled flight out of Seattle. Order the results by the percentage of canceled flights in ascending order. [6 rows]
