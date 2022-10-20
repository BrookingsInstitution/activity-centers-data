The two CSV files Activity_Center_Qualification_by_Metro.csv and Primary_Center_Qualification_by_Metro.csv contain data on how activity centers qualified for activity center status in each metro.  Both files have one line for each of the 110 metro areas analyzed.

***
Activity_Center_Qualification_by_Metro.csv lists the fraction of each center type that qualified in each category.  After the CBSAFIPS, CBSANAME, CBSAPOP (2020 Census population), and CBSARANK (population rank) columns that identify each MSA, there are five sets of columns:

ALL_98 -- fraction of all centers that reached 98th percentile in each category
ALL_95 -- fraction of all centers that reached 95th percentile in each category
PRIMARY -- fraction of primary centers that reached 98th percentile in each category
SECONDARY -- fraction of secondary centers that reached 95th percentile in each category
MONO -- fraction of monocenters that reached 98th percentile in each category.

For each group, the categories are "COMMUNITY", "TOURISM", "CONSUMPTION", "INSTITUTIONAL", and "ECONOMIC".  In addition, a "COUNT" is given for the number of centers of each type in a metro area.

***
Primary_Center_Qualification_by_Metro.csv lists the fraction of primary centers that qualified based on each of the 25 possible combinations of the five categories.  (To qualify, a center must score above 98th percentile in at least two of the categories.)  After the CBSAFIPS, CBSANAME, CBSAPOP (2020 Census population), and CBSARANK (population rank) columns that identify each MSA, the PRIMARY_COUNT column is the number of primary centers in a metro area and the remaining columns are named to indicate which categories a center qualified in, using the following four-letter abbreviations:

COMM -- community
TOUR -- tourism
CONS -- consumption
INST -- institutional
ECON -- economic