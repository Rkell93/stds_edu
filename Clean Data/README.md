# Clean Data
This folder is for the clean data files and associated R code. R code associated with EDA should also be kept in this folder along with the code that creates the final cleansed dataset.  

## Data Sets
### Australian Bureau of Statistics
* **./ABS/Ancestry_SA2.csv** - Grouped observations by parent birth place OS or in Australia. Contains 2310 observations.
* **./ABS/Arrival_Year_SA2.csv** - Banded by arrival year of migrants. Contains 2310 observations. 
* **./ABS/Dwelling_Type_SA2.csv** - Counts and percentages for bandings of Dwelling Types. Only contains 2301 observations, missing 9 SA2's.
* **./ABS/Employed_SA2.csv** - The total number of unemployed, total number of people in the labour force and percent unemployed
* **./ABS/English_Proficiency_SA2.csv** -  Banded by English proficiency (English only, Very Well, Well, Not Well) and by English proficieny and Age band (Child, Working Age, Retiree). Contain 578 SA2's for NSW only.
* **./ABS/HouseHold_Composition_SA2.csv** - Banded by Household Size and Household Composition, Only contains 2301 observations, missing 9 SA2's
* **./ABS/Indigenous_Population_SA2.csv** - Removed non-indigenous and not stated values as well as the breakdown by male/female. Banded ages to be less than 15, 15-65 and over 65. Contains 2310 observations.
* **./ABS/Language_at_Home_SA2.csv** - Banded by high level groupings and English, contains 578 NSW SA2's
* **./ABS/Open_Space_SA2.csv** - Percent of SA2 allocated as "Parkland" by the ABS.
* **./ABS/Place_Of_Birth.csv** - Removed Not Stated, At Sea and Inadequately Described from calculations, captured totals and percentages by Australia/Overseas Born and Region of Birth. Contains 2310 observations.
* **./ABS/SEIFA_2016_Data.csv** - Only data cleaning required was to spread the data and filter out everything but the final score. Only 2191 observations - should be 2310 to cover all SA2's
