#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data

# A1 - Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St  
**Source:** Seattle Open Data, dataset ID `2z5v-ecg8`  
**Pulled:** October 7, 2026  
**License / terms of use:** Public Domain

## Questions I asked

- When is the trail busiest and quietest?
- Do cyclists and pedestrians use the trail at different times of day?
- Is there evidence that people use the trail for commuting?
- Does the direction of bike traffic change between the morning and evening?

## How to re-run

Open `A1.ipynb` and run all cells in order. The notebook requires `requests`, `pandas`, and `matplotlib`.

The notebook downloads the 2019 Burke-Gilman Trail counter data from Seattle Open Data, cleans the data, and analyzes patterns in bike and pedestrian traffic by time of day, day type, and direction of travel.