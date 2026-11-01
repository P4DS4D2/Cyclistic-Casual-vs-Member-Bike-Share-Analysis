Cyclistic Bike-Share 2019: Summary Tables

Aggregated tables built from 3.8 million Divvy bike-share trips (2019) for the Google Data Analytics Capstone (Cyclistic case study). No ride-level rows are included.

Source: Divvy trip data, provided by Motivate International Inc. under the Divvy Data License Agreement (https://divvybikes.com/system-data). Cyclistic is a fictional company.
Author: Hazaimi Hamdani. Full pipeline: [add GitHub link]

Files
02_monthly_rides.csv: rides per month by rider type, and casual share of rides
03_weekday.csv: rides by weekday and rider type, share of each type's rides, median ride length
04_hourly_profile.csv: share of each rider type's rides by start hour, weekdays vs weekends
05_duration_summary.csv: median ride length and share of rides over 30 and 60 minutes
07_top_casual_start_stations.csv: top 15 start stations for casual riders
cleaning_log.csv: every cleaning step, rows affected and rows remaining

Notes: casual = single-ride or day-pass users; member = annual members. Rides over 24 hours, test-station rides and end-before-start rides were removed (see cleaning_log.csv). The data counts rides, not riders.
