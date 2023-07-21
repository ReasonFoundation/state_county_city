# Subcategorize 3 level governements in General Purpose
## State Government
state_gov.Rmd
## County Governement
county_gov.Rmd
## City Government
city_gov.Rmd

<<<<<<< HEAD

=======
## Change in database:
>>>>>>> 2ffac07bdab1f77d7f3e49899d8f66955e6dd09b
Based on this method of subcategorization, Ron Hayden then added boolean values: 

is_city = models.BooleanField(default=False)
is_county = models.BooleanField(default=False)
is_intergovernmental = models.BooleanField(default=False)
is_special_district = models.BooleanField(default=False)
is_state = models.BooleanField(default=False)
is_tribal = models.BooleanField(default=False)

<<<<<<< HEAD
Next, query the data with these fields 
=======
Next, query the data with these fields.
>>>>>>> 2ffac07bdab1f77d7f3e49899d8f66955e6dd09b
