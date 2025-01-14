## mapsapi 0.1.0 (2017-09-27)

* Added 'Directions' API interface
* Added 'Distance Matrix' API interface

## mapsapi 0.2.0 (2017-11-02)

* Added 'Geocode' API interface
* Added input checks
* Added arrival & departure time parameters

## mapsapi 0.3.0 (2018-01-11)

* Added delay in 'mp_geocode' to avoid rate limit
* Fixed index issue in 'mp_geocode'
* Fixed 'mp_get_points' issue with multiple points

## mapsapi 0.3.5 (2018-03-12)

* Added 'bounds' parameter for 'mp_geocode'
* Added argument validation in 'mp_geocode'
* Corrected typo when creating geometry column in 'mp_get_routes' and 'mp_get_segments'

## mapsapi 0.3.7 (2018-07-23)

* Minor updates in documentation
* Added 'duration_in_traffic' option in 'mp_get_matrix'
* 'mp_matrix' now returns 'NA' when there are zero results

## mapsapi 0.3.9 (2019-01-19)

* Support for "waypoints" parameter in 'mp_directions' and 'ms_get_segments'
* 'mp_get_routes' now returns empty LINESTRING when 'doc' contains no route alternatives ('ZERO_RESULTS')
* Added 'quiet' parameter to 'mp_directions' and 'mp_matrix' to hide API from text key when necessary

## mapsapi 0.4.0 (2019-04-06)

* Added 'address_type' (geocode accuracy) field for 'mp_get_points'
* Added 'departure_time' and 'arrival_time' fields for 'mp_get_routes' and 'mp_get_segments'

## mapsapi 0.4.1

* 'mp_get_points' now returns empty POINT when 'doc' contains geocode results ('ZERO_RESULTS')

## To add

* Get static map images (?)


