#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data

# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St
**Source:** https://data.seattle.gov/Transportation/Burke-Gilman-Trail-north-of-NE-70th-St-Bicycle-and/2z5v-ecg8  (pulled 2026-10-13)
**License / terms of use:** Public Domain

## Questions I asked
- When is the trail busiest, and when is it quietest?
  The trail is the busiest around 3-5pm as those have the highest 3 sums of bikes and peds, while it is the quietest around 1-3am as those have the lowest 3 sums of bikes and peds.
- Do cyclists and pedestrians use the trail at different times of day?
  They generally follow the same trend of more bikes/peds using the trail during the day and less during the night, though there are a few spots where, compared to the previous hour, one of the two gained more users while the other gained less users (mainly around 9am-2pm). This is around the usual class/lunch times, though I'm not really sure what causes the difference.
- Are cyclists and pedestrians using the trail for commuting or for recreation?
  A commuting pattern would show that more bikes and pedestrians show up on weekdays compared to weekends in the morning and evening. There are a lot more bikes and pedestrians on weekends between 9am and 4pm compared to on the weekdays. From 6am to 8am, as well as from 5pm to 8pm, there are more bikes and pedestrians on weekdays compared to on weekends. There are more people commuting during commuting hours on weekdays compared to weekends, while recreation is more focused towards the weekend.  Based on this, it seems that there is somewhat of a commuting pattern
- When cyclists and pedestrians use the trail, are there differences in the direction when looking at when they use it?
  Pedestrians are about the same each way no matter the hour, with the biggest difference being a difference of ~1000 peds going north compared to south at 9am, while the rest of the hours are pretty close. Bikes, on the other hand, see a lot more going north in the morning starting from 4am until 9am, when more bikes start going south, which stays that way until it equalizes around 9pm. More bikers are going north in the morning, while more bikers are going south later in the day, and pedestrians are about the same both ways.

## How to re-run
Open `A1.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).