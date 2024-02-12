# Data-analysis-of-flight-delays-in-the-USA-in-July-2017.

## Description

The project involves conducting data analysis on flight delays in the USA in July 2017. The data along with the description is provided by the United States Department of Transportation at https://www.transtats.bts.gov/Homepage.asp (The imported data ready for analysis is located in the flights-data folder).

**The report should address the following questions:**
- What was the average arrival delay?
- What was the maximum arrival delay?
- Which flight had the longest arrival delay? [carrier, departure city, arrival city, flight date, delay]
- Which days of the week are the worst for traveling? [table containing the average delay time for each day of the week]
- Which airlines flying from San Francisco (SFO) have the smallest arrival delays? [table containing the carrier name and the average delay from all its flights]
- What percentage of airlines have regular delays, i.e., their flights are delayed on average at least 10 minutes? [only airlines appearing in the Flight_delays table]
- How do departure delays affect arrival delays? [Pearson correlation coefficient between departure delay time and arrival delay time]
- Which airline had the largest increase (difference) in average arrival delays in the last week of the month, i.e., between July 1-23 and July 24-31? [carrier name and increase]
- Which airlines fly both from SFO → PDX (Portland) and SFO → EUG (Eugene)?
- What is the fastest way to get from Chicago to Stanford, assuming departure after 2:00 PM local time? [table containing Midway (MDW) or O'Hare (ORD) as departure, San Francisco (SFO), San Jose (SJC), or Oakland (OAK) as arrival, and the average arrival delay time for departures after 2:00 PM local time (crs_dep_time attribute); results grouped by departure and arrival place, sorted in descending order]

The report has been prepared using the R language and Markdown.
For each of the points, appropriate SELECT commands have been prepared, which are then included in the R code.
The resulting PDF report has been generated using Markdown in Polish language. The PDF report includes:
- Formatted SQL queries
- Generated answers.
