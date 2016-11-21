### Why open registers are different

An open register has [distinct characteristics](https://gds.blog.gov.uk/2015/10/13/the-characteristics-of-a-register/) that make it different from a traditional database, for example.

An open register:  
* is canonical - the only place where government holds that data
* only contains the data it was created to record and is append-only
* is a live list and can be read by an API
* uses standard names
* can prove the integrity of the data within it
* only contains raw, not derived, data
* must have a custodian - someone responsible for its maintenance

Open registers are append-only. Some open registers use an `end-date` field to note when an entry ceases to be valid. For example, in the country register, the end-date contains the date when a country was dissolved or changed its name.