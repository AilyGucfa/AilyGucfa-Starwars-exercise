#This is my code from https://app.quickdatabasediagrams.com/#/d/NFw7LC
## User
----------
id int PK
email string
username string
password string


Characters
----------
id int PK
name string
height string
mass string
hair_color string
eye_color string
skin_color string
gender string
homeworld string
planet_id string FK - Planets.id
vehicles_id string Fk >- Vehicles.id

Planets
-----------
id int PK
diameter string
rotation_period string
orbital_period string
gravity string
population string
climate string
terrain string
description string
