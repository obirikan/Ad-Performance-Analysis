# Ad Performance Analysis

This project Compares Ad Effectiveness Using A/B Tests; analyzes ad performance  using user interaction data, advertisement metadata, and device data. The goal is to evaluate click-through rates (CTR) across various ad versions, platforms, and devices.

## Dataset Overview

* `users.csv`: Contains user interaction data including user IDs, timestamps, device IDs, and whether an ad was clicked.
* `advertisements.csv`: Contains metadata about advertisements shown to users.
* `devices.csv`: Contains information about the device types used by users.

## Project Structure

The analysis is divided into five major task groups:

###  Import, Inspect, and Merge

* Load CSV files using pandas.
* Inspect dataframes.
* Merge user and advertisement datasets on `user_id` and `timestamp`.

### Aggregations to Calculate Click-Through Rate

* Count ad views.
* Calculate unique users per ad version.
* Compute click-through rate (CTR) as a percentage.

### Comparing Ad Performances by Social Media Platform

* Analyze CTR across ad sources and versions using groupby and pivot tables.

### Comparing Ad Performances by Tech Device

* Merge in device data.
* Compare CTRs by device type and ad version.

### Weekday and Weekend Performance by Device Type

* Extract day of the week from timestamps.
* Compare performance metrics for weekdays vs. weekends.

## How to Run

1. Ensure the following dependencies are installed:

   ```bash
   pip install pandas numpy
   ```
2. Place the `users.csv`, `advertisements.csv`, and `devices.csv` files in the working directory.
3. Run the Python script or load the notebook to perform the analysis.

## Author

* Your Name

## License

This project is licensed under the MIT License.
# Ad-Performance-Analysis
