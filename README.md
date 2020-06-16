# wikidata-confederates
Data from Wikidata for Confederate generals, military officers and politicians, which you can use to see if there are any things near you named for them. The goal is to get those things renamed.

I'm compiling these from Wikidata, via the WDumper tool: https://tools.wmflabs.org/wdumps/dumps. Here is more info on the dumps: https://www.wikidata.org/wiki/Wikidata:Database_download

The raw data is kind of complicated so I am going to post that in case someone wants to parse it, as well as a parsed version 

The queries are as follows:

- P27: country of citizenship - Confederate States of America
- P241: military branch - Confederate States of America army
- P410: military rank - generals in the Confederate Army

confederates.csv is a parsed version of all of those files put together, for ease of use. There may be some duplicates.

How I think this could be used: download whatever list you'd like and compare it to your town or state's streets, schools, parks, and so on. See if any match up. However, make sure to do additional research for common names to see if it's another person by the same name. There may be some false positives too.

NOTE: Not all Confederate generals, officers and officials may be listed. I plan to add more.
