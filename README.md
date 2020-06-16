# wikidata-confederates

## What is this
Data from [Wikidata](https://www.wikidata.org) for Confederate generals, military officers and politicians, which you can use to see if there are any things near you named for them. The goal is to get those things renamed. Wikidata is related to Wikipedia, it's a database of various kinds of things, like people, places, and so on.

## How to use it
Download **[list_of_confederates.csv](https://raw.githubusercontent.com/aawiseman/wikidata-confederates/master/list_of_confederates.csv)**  and compare it to whatever other data you are interested in, such as your town or state's streets, schools, parks, and so on. See if any match up. However, make sure to do additional research for common names to see if it's another person by the same name. 

You can open **list_of_confederates.csv** with any spreadsheet application. It's a big, simple list of all the data I've gathered from Wikidata with the names of Confederates and the source of that person's name. There may be some duplicates or false positives because it is based on Wikidata which may not be perfect.

There are also raw data files if you want them in the *Raw data from Wikidata* folder, but they are pretty complicated and may be hard to parse.

NOTE: Not all Confederate generals, officers and officials may be listed. I plan to add more.

## Source of data
I'm compiling these from Wikidata, via the WDumper tool: https://tools.wmflabs.org/wdumps/dumps. Here is more info on the dumps: https://www.wikidata.org/wiki/Wikidata:Database_download

The queries I ran are as follows. More to come.

- P27: country of citizenship - Confederate States of America
- P241: military branch - Confederate States of America army
- P410: military rank - generals in the Confederate Army


