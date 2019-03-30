Team Raksha

SRMIST MOZOHACK 19

Nirbhaya App - Push 01

Tasks Covered: Data Pre-processing

- imported COBRA crime datasets ranging from 2008-2019.

- removed redundant features/columns

- removed null/missing entries

- removed outlier values with low frequencies

- split 24 hours into 12 slots (12:00 AM - 2:00 AM, 2:00 AM - 4:00 AM, and so on...)

- labelled each record with a day of year (1-365)

- suitably labelled each record for the above changes

Next Task : create hierarchy of time block, day, neighbourhood respectively, with count attribute.
	: pass to a k-means classifier to get 3 distinct labelled categories of crime.
	: will use categories obtained to gauge whether an area is dangerous or not.