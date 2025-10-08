# Jiahang Luo

## Description

I will primarily use the V-Dem country-year dataset (1995–2024) to map and compare global patterns of democratic quality, then examine how plausible facilitators—internet access, education, income, inequality, and urbanization—are associated with both higher democratic levels and resilience to its backsliding. This will be visualization rather than proof of causality : I’ll highlight correlations, regional contrasts, and outliers. The sequence is a global overview , trend views and slopegraphs to show change, followed by faceted scatterplots linking democracy to facilitators, and simple resilience metrics (2010–2024 deltas and rolling slopes) to flag countries whose trajectories defy expectations.


## Data Sources

### Data Source 1: {V-Dem}

URL: {https://v-dem.net/data/the-v-dem-dataset/}

Size: {27913} rows, {4607} columns

The V-Dem dataset is a global country–year panel containing multiple headline democracy indices (for example, v2x_libdem for liberal democracy and v2x_polyarchy for electoral democracy) plus dozens of component indicators such as participation, civil liberties, and judicial constraints. I downloaded the CSV, examined the headers and a random sample of rows to verify the expected variables and check for missing values. To maintain a temporally consistent panel and avoid country name changes and reduce irregular gaps, I restricted the project to the 1995–2024 slice, which yields a complete and stable dataset for the visualization. 


### Data Source 1: {World Bank Economics growth}

URL: {https://data.worldbank.org/indicator/NY.GDP.MKTP.KD.ZG?end=2024&start=2024&view=map}

Size: {266} rows, {70} columns

{The World Bank GDP growth indicator reports the annual percent change in GDP at market prices (constant prices); I checked the number of missing observations and inspected their corresponding time ranges to assess the series’ coverage for the country–year analysis.}
