# Cities of the World
[![Creative Commons License](https://i.creativecommons.org/l/by/3.0/80x15.png)](http://creativecommons.org/licenses/by/3.0/)

This cities comes from GeoNames Gazetteer:
http://www.geonames.org

Here is the description of the original dataset:
> all cities with a population > 1000 or seats of adm div (ca 150.000) [...]

This Json version is an array of object of the following shape:
- ISO 3166-1 alpha-2 country code
- name
- Latitude
- Longitude
```
[
  {
    "country": "FR",
    "name": "Lyon",
    "lat": "45.75",
    "lng": "4.583333"
  },
  ...
]
```

> These cities can pretty easily be matched with countries by code using the following dataset:
> https://github.com/annexare/Countries
