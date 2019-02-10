# ebpa_all_los_origin_dest_201902.csv

## Description

This dataset shows Census Block to park connections based on network analysis at 0.5, 1, 2, and 4 mile increments.

## Fields

- origin_id
  - string
  - Census Block GEOID
- origin_x
  - float
  - Census Block WGS 84 longitude coordinate value
- origin_y
  - float
  - Census Block WGS 84 latitude coordinate value
- parkid
  - integer
  - Park ID number
- destination_id
  - string
  - Park name
- destination_x
  - float
  - WGS 84 longitude coordinate value at park center
- destination_y
  - float
  - WGS 84 latitude coordinate value at park center
- analysis_class
  - float
  - Network distance class
- total_length
  - float
  - Total length of network route from Census Block to park access point
