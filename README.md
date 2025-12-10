**Data Resources**
* US percentage population of age groups over time dataset:
Description: Persons in selected age groups as a percentage of the total U.S. population and children ages 0–17 as a percentage of the dependent population, 1950–2022 and projected 2023–2050.

Website: github

Link: https://www.childstats.gov/americaschildren/tables/pop2.asp

* Aging congress dataset:
Description: This directory contains various demographic data about the United States Senate and House of Representatives over time. It’s been used in the following FiveThirtyEight articles: Congress Today Is Older Than It’s Ever Been, by Geoffrey Skelley (April 3, 2023). The dataet contains information about the age of every member of the U.S. Senate and House from the 66th Congress (1919-1921) to the 118th Congress (2023-2025). Data is as of March 29, 2023, and is based on all voting members who served in either the Senate or House in each Congress. The data excludes delegates or resident commissioners from non-states. Any member who served in both chambers in the same Congress was assigned to the chamber in which they cast more votes. We began with the 66th Congress because it was the first Congress in which all senators had been directly elected, rather than elected by state legislatures, following the ratification of the 17th Amendment in 1913.

Website: Childstats

Link: https://github.com/fivethirtyeight/data/blob/master/congress-demographics/data_aging_congress.csv

* State Label
Description: It contains name of USA states and its abbreviation.

website: github

Link: https://github.com/jasonong/List-of-US-States/blob/master/states.csv

**Variable Description of datasets**
* US percentage population of age groups over time dataset:
congress: The number of the Congress that this member’s row refers to.

start_date: First day of a Congress.

chamber: The chamber a member of Congress sat in: Senate or House.

state_abbrev: The two-letter postal abbreviation for the state a member represented.

party_code: A code that indicates a member’s party, based on the system used by the Inter-university Consortium for Political and Social Research. The most common values will be 100 for Democrats, 200 for Republicans.

bioname: Full name of member of Congress.

bioguide_id: Code used by the Biographical Directory of the United States Congress to uniquely identify each member.

birthday: Date of birth for a member.

cmltv_cong: The cumulative number of Congresses a member has or had served in (inclusive of listed congress), regardless of whether the member was in the Senate or House.

cmltv_chamber: The cumulative number of Congresses a member has or had served in a chamber (inclusive of listed congress).

age_days: Age in days, calculated as start_date minus birthday.

age_years: Age in years, calculated by dividing age_days by 365.25.

generation: Generation the member belonged to, based on the year of birth.

* New variables I added:

age_group: Convert the Generations in the data to the defined year range

party: Convert the party code to the name of the party which the code represent.

* Aging congress dataset:
Age group as a percentage of total population:

ages 0-17

ages 18-64

ages 65 and older

Age group as a percentage of the dependent population:

ages 0-17

* State Label
State
Abbreviation

**Research Questions**
What is the trend of the age of the Congress representative change over time?

Does the changing of age of Congress representative related with the age of population?

Which state with the oldest Congress representative on average?
