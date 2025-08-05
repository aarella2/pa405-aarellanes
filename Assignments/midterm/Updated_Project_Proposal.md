# Updated Project Proposal

## Exploring the Spatial and Socioeconomic Factors that Influence Local Small Business Distribution in Los Angeles County

## Introduction / Research Question

Small businesses are a vital part of many communities in Los Angeles County, but the factors that influence where they’re located are not fully understood. This project explores how population density, daytime population, and County supported vendor programs relate to where local small businesses are distributed.

**Research Question:**  
What spatial and socioeconomic factors influence the distribution of local small businesses across census tracts in Los Angeles County?

## Why This Matters

Understanding where small businesses cluster and where they don’t can help guide more equitable development, improve access to services, and inform County outreach and procurement efforts. It also highlights whether County vendor programs are reaching all communities.

## Data Sources

1. **[Census Tract Data](https://github.com/aarella2/pa405-aarellanes/tree/main/Assignments/week03/data)**
   - Total Population
   - Area (square miles)
   - Population Density (calculated)
   - Daytime Population: Workers

2. **[ISD Vendor Preference Program Data](https://camisvr.co.la.ca.us/LACoBids/CertList/VendorCert)**
   - Geocoded vendor addresses

## Methodology

- **Geocoding and Spatial Join**
  - Mapped vendors to census tracts
  - Merged vendor and census data

- **Calculations**
  - Business Count per tract
  - Population Density = Total Population / Area
  - Business Density = Business Count / Area

- **Analysis**
  - Maps: Population Density, Daytime Population, Business Count, Business Density
  - Scatter plots:
    - Business Count vs. Population Density
    - Business Count vs. Daytime Population
    - Top 10 Census Tracts by Business Counts

## Initial Observations

- There was no clear correlation between business count and either total population or daytime worker population.
- Some tracts with high population or high daytime worker presence had few or no preference program businesses.
- This suggests that factors beyond population metrics may be influencing business distribution, possibly program participation rates, industry type, or historical contracting trends.


## Reflections & Next Steps

- Although population and daytime worker density don't explain vendor distribution, other factors may be influencing where preference program businesses are located.
- Next, I plan to break down the PPE vendor dataset by business type:
  - Local Small Business Enterprises (LSBE)
  - Social Enterprises
  - Veteran-Owned Businesses
- I also want to focus on the census tracts with the highest vendor counts to understand what they may have in common.
- This could help identify patterns or characteristics that support greater vendor participation.

## Conclusion

This analysis will provide insight into how Los Angeles County's vendor programs are reflected spatially and which areas may benefit from more support or outreach. It can help guide future economic development and equitable planning efforts.
