# ebpa_scores_201902.geojson

## Description

This dataset depicts dummy park level of service scores for Raleigh Census Blocks generated in February 2019

## Fields

- geoid10
  - string
  - Census Block ID
- los_dist_score
  - integer
  - Level of Service distance score
- los_acre_score
  - integer
  - Level of Service acreage score
- los_exp_score
  - integer
  - Level of Service experience score
- los_total_score
  - integer
  - Combined total of level of service distance, acre, and experience scores
- la_dist_score
  - integer
  - Land Acquisition Level of Service distance score
- la_acre_score
  - integer
  - Land Acquisition Level of Service acreage score
- la_exp_score
  - integer
  - Land Acquisition Level of Service experience score
- la_total_score
  - integer
  - Combined total of Land Acquisition Level of Service distance, acre, and experience scores
- gw_score_loop_contiguous
  - integer
  - Nearest greenway score only accounting for connections to loops or the contiguous greenway network
- los_gw_total_score
  - integer
  - los_total score + gw_score_loop_contiguous
- la_gw_total_score
  - integer
  - la_total_score + gw_score_loop_contiguous
- totpop
  - float
  - Total populations of Census Block
- area
  - float
  - Square mileage of Census Block
- popdensity_sqmi
  - float
  - Population density
