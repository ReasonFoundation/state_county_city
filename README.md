# Subcategorize 3 level governements in General Purpose
## State Government
state_gov.Rmd
## County Governement
county_gov.Rmd
## City Government
city_gov.Rmd


Based on this method of subcategorization, Ron Hayden then added boolean values: 

is_city = models.BooleanField(default=False)
is_county = models.BooleanField(default=False)
is_intergovernmental = models.BooleanField(default=False)
is_special_district = models.BooleanField(default=False)
is_state = models.BooleanField(default=False)
is_tribal = models.BooleanField(default=False)

Next, query the data with these fields.
