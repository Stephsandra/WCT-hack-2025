# Datasets for the Women ConnecTech x Reboot Power Up hackathon

## BigQuery Public datasets
### Google's Diversity Annual Report Data
Dataset ID:`bigquery-public-data.google_dei`

This dataset contains current and historical demographic data on Google's workforce since the company began publishing diversity data in 2014. It includes data collected for government reporting and voluntary employee self-identification globally relating to hiring, retention, and representation categorized by race, gender, sexual orientation, gender identity, disability status, and military status. In some instances, the data is limited due to various government policies around the world and the desire to protect Googler confidentiality.

### International Census Data
Dataset ID: `bigquery-public-data.census_bureau_international`

The United States Census Bureau’s international dataset provides estimates of country populations since 1950 and projections through 2050. Specifically, the dataset includes midyear population figures broken down by age and gender assignment at birth. Additionally, time-series data is provided for attributes including fertility rates, birth rates, death rates, and migration rates.
_Note: The U.S. Census Bureau provides estimates and projections for countries and areas that are recognized by the U.S. Department of State that have a population of at least 5,000._

### Quarterly Census of Employment and Wages
Dataset ID: `bigquery-public-data.bls_qcew`
The Quarterly Census of Employment and Wages (QCEW) program publishes a quarterly count of employment and wages reported by employers covering more than 95 percent of U.S. jobs, available at the county, MSA, state and national levels by industry.

The dataset, hosted as part of the Cloud Public Datasets Program , gives county-level information on jobs and wages each quarter starting in 1990. The counties are identified by geoid which can easily be joined with both all FIPS codes or US county boundaries  to unlock new insights within the data. Both of these datasets are available in BigQuery through the Cloud Public Datasets

### International Education
Dataset ID: `bigquery-public-data.world_bank_intl_education`
This dataset combines key education statistics from a variety of sources to provide a look at global literacy, spending, and access.

## GitHub Activity Data
Dataset ID: `bigquery-public-data.github_repos`
GitHub is how people build software and is home to the largest community of open source developers in the world, with over 12 million people contributing to 31 million projects on GitHub since 2008.

This 3TB+ dataset comprises the largest released source of GitHub activity to date. It contains a full snapshot of the content of more than 2.8 million open source GitHub repositories including more than 145 million unique commits, over 2 billion different file paths, and the contents of the latest revision for 163 million files, all of which are searchable with regular expressions.

## American Community Survey (ACS)
Dataset ID: `bigquery-public-data.census_bureau_acs`
The American Community Survey (ACS) is an ongoing survey that provides vital information on a yearly basis about our nation and its people by contacting over 3.5 million households across the country. The resulting data provides incredibly detailed demographic information across the US aggregated at various geographic levels which helps determine how more than $675 billion in federal and state funding are distributed each year.

Businesses use ACS data to inform strategic decision-making. ACS data can be used as a component of market research, provide information about concentrations of potential employees with a specific education or occupation, and which communities could be good places to build offices or facilities. For example, someone scouting a new location for an assisted-living center might look for an area with a large proportion of seniors and a large proportion of people employed in nursing occupations.

Through the ACS, we know more about jobs and occupations, educational attainment, veterans, whether people own or rent their homes, and other topics. Public officials, planners, and entrepreneurs use this information to assess the past and plan the future.

## Google Trends - International
Dataset ID: `bigquery-public-data.google_trends`
The International Google Trends dataset will provide critical signals that individual users and businesses alike can leverage to make better data-driven decisions. This dataset simplifies the manual interaction with the existing Google Trends UI by automating and exposing anonymized, aggregated, and indexed search data in BigQuery.

This dataset includes the Top 25 stories and Top 25 Rising queries from Google Trends. It will be made available as two separate BigQuery tables, with a set of new top terms appended daily. Each set of Top 25 and Top 25 rising expires after 30 days, and will be accompanied by a rolling five-year window of historical data for each country and region across the globe, where data is available.

## Stack Overflow
Dataset ID: `bigquery-public-data.stackoverflow`
Stack Overflow is the largest online community for programmers to learn, share their knowledge, and advance their careers. Updated on a quarterly basis, this BigQuery dataset includes an archive of Stack Overflow content, including posts, votes, tags, and badges. This dataset is updated to mirror the Stack Overflow content on the Internet Archive, and is also available through the Stack Exchange Data Explorer.

