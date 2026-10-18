*Almaty vs. San Francisco: classifying days from hourly step counts*

CS156 Assignment 1. Can a model tell which city I was in from the 24 hourly step counts of a single day? Data: my own Apple Health export. City labels come from my own travel dates.

Files
- 01_build_daily_table.ipynb: parses export.xml, converts timestamps to local time, labels days by city, saves data/daily_hourly.csv.
- 02_modeling.ipynb: builds features, compares six models under two splits, makes the figures.
- data/daily_hourly.csv: one row per day (city, period, 24 hourly step counts).
- data/export.xml: the raw Apple Health export
