# Traffic Accidents: The where and the why.
### Kapilan Mahalingam, Business Project MVP, August 2022
---
As we're required to do this in excel, I'm using only the first week of 2021 (the full dataset has ~3 million observations; the restricted one has ~18,000). I am using python to get the first week of data (since I cannot open the full csv in Excel due to memory), but only for that.

A quick sample:

<p align="center">
<img src="mvp_table.png" alt="" width="400"/>
</p>

This is the cities with over 20 accidents in the week of January 1st, 2021, sorted from most to least accidents, with population and per capita figures. *Note that the 'Accidents per capita' is the inverse of the true accidents per capita, to avoid floating point issues.*

Larger cities like Dallas, Houston, and LA, are unsurprisingly high. Highlighted entries are those which fell into the highest 10% of accidents per capita, which merit a closer look.

<p align="center">
<img src="mvp_chart.png" alt="" width="800"/>
</p>

This gives us states which had the highest accidents per capita, and SC seems to stand out particularly. Even in the above table, 50% of highlighted cities are in SC, with York and Lancaster particularly standing out as accident hotspots. These merit a closer look.
