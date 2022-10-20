The file Buffer_All_Data.csv contains nine entries for each of the 110 MSAs studied.  This data is also broken down into nine separate files, with one entry for each of the 110 MSAs studied:

	Buffer_Metro_Totals.csv		 - total value for the MSA.
	Buffer_Activity_Centers_1mi.csv  - 1-mile buffer of all activity centers
	Buffer_Activity_Centers_3mi.csv  - 3-mile buffer of all activity centers
	Buffer_Primary_Centers_1mi.csv   - 1-mile buffer of primary centers
	Buffer_Primary_Centers_3mi.csv   - 3-mile buffer of primary centers
	Buffer_Secondary_Centers_1mi.csv - 1-mile buffer of secondary centers
	Buffer_Secondary_Centers_3mi.csv - 3-mile buffer of secondary centers
	Buffer_Mono_Centers_1mi.csv      - 1-mile buffer of monocenters
	Buffer_Mono_Centers_3mi.csv      - 3-mile buffer of monocenters

The columns are:

CBSA_FIPS - CBSA FIPS code.
CBSA_NAME - CBSA name.
CBSA_POP  - CBSA population as per 2020 Census.
CBSA_RANK - CBSA population rank.

CENTER_TYPE - Type of center and buffer size (1-mi versus 3-mi).
BG_TOTAL - Share of 2019 block groups in the buffer.

POP_TOTAL - Share of MSA population in the buffer.
POP_WHITE - Share of MSA non-Hispanic white population in the buffer.
POP_BLACK - Share of MSA non-Hispanic Black population in the buffer.
POP_LATIN - Share of MSA Latino/Hispanic population in the buffer.
POP_ASIAN - Share of MSA non-Hispanic Asian population in the buffer.

HOUSING_OCCUPIED - Share of occupied housing units in the buffer.
HOUSING_OWNED    - Share of owner-occupied housing units in the buffer.
HOUSING_RENTED   - Share of renter-occupied housing units in the buffer.

HOUSING_UNITS    - Share of housing units in the buffer.
HOUSING_DET_SFH  - Share of single-family detached housing units in the buffer.
HOUSING_MISS_MID - Share of attached and 2-9 unit building housing units in the buffer.
HOUSING_LARGE    - Share of housing units in buildings of 10+ units in the buffer.
HOUSING_MOBILE   - Share of mobile/vehicle housing units in the buffer.

HOUSEHOLDS_TOTAL - Share of households in the buffer.
HOUSEHOLDS_0_CAR - Share of 0-car households in the buffer.
HOUSEHOLDS_1_CAR - Share of 1-car households in the buffer.
HOUSEHOLDS_2_CAR - Share of 2+-car households in the buffer.

PER_CAPITA_INCOME_CBSA    - Average per-capita income in the MSA.
PER_CAPITA_INCOME_INSIDE  - Average per-capita income in the buffer as fraction of MSA value.
PER_CAPITA_INCOME_OUTSIDE - Average per-capita income outside the buffer as fraction of MSA value.

COMMUTERS_TOTAL   - Share of workers, excluding those working from home, in the buffer.
COMMUTERS_DRIVERS - Share of workers who drive to work alone in the buffer.


All data is from 2019 5-year ACS estimates.  Note that activity centers are defined as 2020 block groups, but data is supplied in 2019 block groups.  This is resolved by using the centroids of 2019 block groups for data and identifying those within 1- and 3-mile buffers of the centroids of 2020 activity centers.