# CS513
Using NYPD Arrest Data (Year to Date)
https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc/about_data

## Notes
- 

| Feature | Description | Values |
| --- | --- | --- |
| `ARREST_KEY` | Randomly generated persistent ID for each arrest | Unique Vals |
| `ARREST_DATE` | Exact date | ex. 03/14/2024 | 
| `PD_CD` | Three digit internal classification code (more detailed than arrest_key) | ex. 101.0, 
| `PD_DESC` | Description of internal classification corresponding with PD code (more detailed than Offense Description) | ex. ASSAULT, LARCENY |
| `KY_CD` | Three digit internal classification code (more general category than PD code) | ex. 344.0, 341.0, 106.0|
| `OFNS_DESC` | Description of internal classification corresponding with KY code (more general category than PD description) | ex. FELONY, MISDEMEANOR |
| `LAW_CODE` | Law code charges corresponding to the NYS Penal Law, VTL and other various local laws | ex. PL 1200001, VTL0511001, PL 215510B|
| `LAW_CAT_CD` | Level of offense: felony, misdemeanor, violation |
| `ARREST_BORO` | Borough of arrest. B(Bronx), S(Staten Island), K(Brooklyn), M(Manhattan), Q(Queens) |
| `ARREST_PRECINCT` | Precinct where the arrest occurred |
| `JURISDICTION_CODE` | Jurisdiction responsible for arrest. Jurisdiction codes 0(Patrol), 1(Transit) and 2(Housing) represent NYPD whilst codes 3 and more represent non NYPD jurisdictions |
| `AGE_GROUP` | Perpetrator’s age in groups |
| `PERP_SEX` | Perpetrator’s sex |e. F, M |
| `PERP_RACE` | Perpetrator’s race |
| `X_COORD_CD` | X-coordinate for New York State Plane Coordinate System. Units: feet. |
| `Y_COORD_CD` | Y-coordinate for New York State Plane Coordinate System. Units: feet.|
| `Latitude` | Latitude coordinate for Global Coordinate System. |
| `Longitude` | Longitude coordinate for Global Coordinate System. |
| `New Georeferenced Column` | A geographical point of the form (longitude, latitude) |


