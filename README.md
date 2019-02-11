# Accidents_Barcelona

This is a project made for the department of accidents of the City Council of Barcelona.

# situation

They were using an old version of Cognos Report Studio without any dashboard and deploying static reports mainly composed by tables and pie charts. Analyst were wasting time with long loading times and hard report developments whilst clients received reports with non-valuable information.
Therefore, users and clients were not satisffied with the results.

They had three different Star-schemas to analyze accidents in Barcelona:
- Accidents.
- Vehicles.
- People involved.

Because of this, users could not study some measures from all the possible perspectives, for instance, they could not analyze the measure "Number of accidents" by the dimension "Gender" directly from their BI Tool because data was in different schemas, one information was on the Accidents schema and Gender was a dimension of the People-involved schema.

# task

I was in charge of design a new BI environment to improve the performance of the department.

# action

I choosed Microsoft Power BI to:
- Create a single cube joining the data from the existing three schemas.
- Apply Data Quality.
- Create a Key Dashboards for Analysts.
- Create reports.
- Set up the Premium environment for share and collaborate within the organization.

# results

- Check out the repository!
