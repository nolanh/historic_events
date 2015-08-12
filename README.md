# historic_events
This repository contains a large, open data set of historic events. Most of the events contained herein come from a Wikipedia corpus, and many additional events were inputted manually. Significant effort was put into verifying the accuracy of the events, but due to the small contributor base, the amount of verification likely does not exceed 10% of the overall data set. Pull requests with updates/edits are welcome and highly appreciated.

# Attribution Line
When reusing the historic events data set, please use the following attribution line:

Historic Events Data Set © Nolan Hemmatazad / Wikimedia Commons / [CC-BY-SA-3.0](http://creativecommons.org/licenses/by-sa/3.0/)

## Attribution Placement
Generally, I don't care where you place the attribution line, so long as it's accessible from wherever your usage of the data set occurs. Inside of a README file, an "acknowledgments" page, etc. is perfectly fine.

# Formatting Details
The historic_events.tsv file contains all data set events. Each event is presented as a line of its own, and in 4 distinct pieces (tab-separated values):

1.  The year of the event

2.  The type of event it was (where 1 = a general event, 2 = birth of a historic figure, and 3 = death of a historic figure)

3.  The month and day of the event (e.g., January 1) or _circa_, if a precise date is not known

4.  The event text, which may lead with a date range such as (February 1 - February 10) for an entry that begins an event spanning multiple days. The event text may also contain italicized items, represented like [i]this[/i]

# License
This work is being released under a Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0), as this is the same license that Wikipedia, the source of a significant portion of the data set's contents, implements.

The full text of the license can be reviewed here: [https://creativecommons.org/licenses/by-sa/3.0/](https://creativecommons.org/licenses/by-sa/3.0/)
