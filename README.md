# Tanzania_waterFall_Predictions

![pumping](https://thumbs.dreamstime.com/z/young-african-boy-drinking-water-community-borehole-hand-pump-young-african-boy-drinking-water-community-172697689.jpg?w=992)

# Overview#

Tanzania is the largest country in East Africa with a population of approximately 59 million. However, the country faces challenges in providing clean water to its large population and about 47% of the population lack access to clean drinking water. Many existing water points need repairs or have failed completely. The purpose of the project is to build a classifier for two potential audiences;
 -The Government of Tanzania who might be interested in identifying patterns in non-functional wells and understand  factors influencing their failure. This knowledge can be used to improve how new wells are built to ensure their longevity and functionality.
 -NGOs-Identifying non-functional and in-need-of-repair wells to optimize resource allocation and maximize their impact in providing clean water access.

# Objective#

The goal is to build a classifier using data points like pump type, installation date, pump status etc to predict the functionality of water pumps found throughout the country.

# Data Understanding#

Data was obtained from the Taarifa waterpoints dashboard which aggregates data from the Tanzania Ministry of Water. The data collected contains features related to water pumps such as geographic location, water quality, organizations that build and manage them and population among others. The target feature is 'status group'with three possible values of functional, non-functional and functional-need-repairs.


# Modeling#

Three models were run on the data; XGBoost, LinearSVC and RandomForest.

# Evaluation#

# Conclusion#
