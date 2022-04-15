# Data602_finalproject
### Data Source :
https://data.cityofnewyork.us/Housing-Development/Housing-New-York-Units-by-Building/hg8x-zxpr

### Project Description :
This dataset represents Newyork housing datasets where each row indicates a project and its status based on the number of bed rooms(1-BR, 2-BR, 3_BR,...,6BR+ units) and location.
### Project Proposal :
Based on the multiple features like number of bed rooms, income levels, latitude, longitude, project completion date etc. predicting the total units that will be produced.
### Feature description :
- Project ID :The Project ID is a unique numeric identifier assigned to each project by HPD.
- Project Name : The Project Name is the name assigned to the project by HPD.
- Project Start Date : The Project Start Date is the date of the project loan or agreement closing.
- Project Completion Date : The Project Completion Date is the date that the last building in the project was completed. If the project has not yet completed, then the field is blank.
- Building ID : The Building ID is a unique numeric identifier assigned to each building by HPD.
- Number : The House Number is the street number in the building’s address. E.g., the house number is ‘100’ in ‘100 Gold Street.’
- Street : The Street Name is the name of the street in the building’s address. E.g., the street name is ‘Gold Street’ in ‘100 Gold Street.’
- Borough :The Borough is the borough where the building is located.
- Postcode : Zip code
- BBL : The BBL (Borough, Block, and Lot) is a unique identifier for each tax lot in the City.
- BIN :The BIN (Building Identification Number) is a unique identifier for each building in the City.
- Community Board : The Community Board field indicates the New York City Community District where the building is located.
- Council District : The Council District indicates the New York City Council District where the building is located.
- Census Tract : The Census Tract indicates the 2010 U.S. Census Tract where the building is located.
- NTA - Neighborhood Tabulation Area : The Neighborhood Tabulation Area indicates the New York City Neighborhood Tabulation Area where the building is located.
- Latitude : The Latitude and Longitude specify the location of the property on the earth’s surface. The coordinates provided are an estimate of the location based on the street segment and address range.
- Longitude : The Latitude (Internal) and Longitude (Internal) specify the location of the property on the earth’s surface. The coordinates provided are of the internal centroid derived from the tax lot.
- Building Completion Date : The Building Completion Date is the date the building was completed. The field is blank if the building has not completed.
- Reporting Construction Type : The Reporting Construction Type field indicates whether the building is categorized as ‘new construction’ or ‘preservation’ in Housing New York statistics. Note that some preservation projects included here may not actually involve construction, because they extend the project’s regulatory restrictions but do not require rehabilitation.
- Extended Affordability Only : The Extended Affordability Only field indicates whether the project is considered to be Extended Affordability. An extended affordability project involves no construction, but secures an extended or new regulatory agreement. All extended affordability projects have a ‘reporting construction type’ of ‘preservation.’
- Prevailing Wage Status : The Prevailing Wage Status field indicates whether the project is subject to prevailing wage requirements, such as Davis Bacon.
- Extremely Low Income Units : Extremely Low Income Units are units with rents that are affordable to households earning 0 to 30% of the area median income (AMI).
- Very Low Income Units : Very Low Income Units are units with rents that are affordable to households earning 31 to 50% of the area median income (AMI).
- Low Income Units : Low Income Units are units with rents that are affordable to households earning 51 to 80% of the area median income (AMI).
- Moderate Income Units : Moderate Income Units are units with rents that are affordable to households earning 81 to 120% of the area median income (AMI).
- Middle Income Units : Middle Income Units are units with rents that are affordable to households earning 121 to 165% of the area median income (AMI).
- Other Income Units : Other Units are units reserved for building superintendents.
- Studio Units : Studio Units are units with 0-bedrooms.
- 1-BR Units : 	1-BR Units are units with 1-bedroom
- 2-BR Units : 2-BR Units are units with 2-bedrooms.
- 3-BR Units : 3-BR Units are units with 3-bedrooms.
- 4-BR Units : 	4-BR Units are units with 4-bedrooms.
- 5-BR Units : 5-BR Units are units with 5-bedrooms.
- 6-BR+ Units : 6-BR+ Units are units with 6-bedrooms or more.
- Unknown-BR Units : Unknown-BR Units are units with an unknown number of bedrooms.
- Counted Rental Units : 	
Counted Rental Units are the units in the building, counted toward the Housing New York plan, where assistance has been provided to landlords in exchange for a requirement for affordable units.
- Counted Homeownership Units : Counted Homeownership Units are the units in the building, counted toward the Housing New York Plan, where assistance has been provided directly to homeowners.
- All Counted Units : The Counted Units field indicates the total number of affordable units, counted towards the Housing New York plan, that are in the building.
- Total Units : The Total Units field indicates the total number of units, affordable and market rate, in each building.
