# Nerd Notes: Using Historical Spill Data To Estimate How Frequently Spills Might Occur For Dakota Access


Here’s the methodology and analysis behind our crude oil pipeline spill post. Buckle up, we’re going to throw a lot of numbers at you. If you have further questions – or ideas about how to do this analysis differently – contact jordanwb at inside energy dot org.


## What data did you use?
We used the hazardous liquid pipeline inventory and the hazardous liquids spills databases from the Pipeline and Hazardous Materials Safety Administration (PHMSA). For this analysis, we focused on pipelines and spills from 2010 to the present. Why? Because the data was collected and reported differently prior to 2010.


* [Spills and accidents download, hazardous liquids, 2010 to present](http://phmsa.dot.gov/portal/site/PHMSA/menuitem.6f23687cf7b00b0f22e4c6962d9c8789/?vgnextoid=fdd2dfa122a1d110VgnVCM1000009ed07898RCRD&vgnextchannel=3430fb649a2dc110VgnVCM1000009ed07898RCRD&vgnextfmt=print)
* [Pipeline inventory download, hazardous liquids, 2010 to present](http://phmsa.dot.gov/portal/site/PHMSA/menuitem.6f23687cf7b00b0f22e4c6962d9c8789/?vgnextoid=a872dfa122a1d110VgnVCM1000009ed07898RCRD&vgnextchannel=3430fb649a2dc110VgnVCM1000009ed07898RCRD&vgnextfmt=print)


Note that PHMSA updates the pipeline and spills database frequently. Inside Energy downloaded this data in November, 2016.


## Hazardous liquids...but I thought we were talking crude oil here?
We are. So to determine the number of crude oil pipeline spills, we filtered the spills and accidents database by commodity (selecting for crude). Here’s what we know about the spills that have happened in the U.S. since 2010, according to reports to PHMSA.
There have been 2,694 hazardous liquids pipeline accidents or spills. This includes crude oil, liquefied natural gas and refined petroleum products, such as jet fuel.
Of those, roughly half, or 1,345, involved crude oil. That averages to 198 crude oil spills a year.
Most of these, 99 percent, were onshore. 


## And how much is spilled?
* Combined, 202,794 barrels of crude oil have been spilled onshore since 2010. That works out to 30,724 barrels a year, or 3.5 barrels an hour.
* Looking at spill size, 60 percent were 5 barrels or less; five percent were 500 barrels or more.
The important takeaway here is that most of that spillage comes from a small fraction of the incidents.


We’ve uploaded a shortened version of the spills and accidents file from 2010 to the present (where we have 10 fields, instead of hundreds) into this repository as crude-pipeline-spills-2010-2016.csv.


## And what about waterways?
* Onshore, 14 spills, or about one percent, occurred at a water crossing; and 106 resulted in water contamination.
* Those 14 spills released 3,259 barrels of crude oil into waterways.
* 70 percent of that water contamination happened from the two largest spills, which were both in Montana’s Yellowstone River, in 2015 and 2011.
Bottom line: Waterway spills are infrequent. Most are small, but large waterway spills do occur.


## And what about miles of pipeline?
We got the mileage of crude oil pipeline, by year, from PHMSA’s summary page, which you can [access here](http://opsweb.phmsa.dot.gov/primis_pdm/pipeline_miles_facilities_2010up.asp).

To get crude oil pipeline miles, by year, we selected “Hazardous Liquids,” then selected each state. We also unselected the “OCS” values (to filter out the offshore miles of pipeline).

We’ve uploaded a table of the mileage to this repository, as crude-pipeline-miles-2010-2015.csv.

## But what about risk? Let’s talk spill rates.
Knowing the number of spills is a good start, but to really understand how risky a pipeline is, we need to understand how large the pipeline network is, how much crude is moved and how far it goes.

As [Inside Energy reported](http://insideenergy.org/2016/11/18/protesters-say-pipelines-are-dangerous-are-they/), there are 2.7 million miles of pipeline of all types – natural gas, hazardous liquids – currently operating in the U.S. (Or thereabouts; the number changes constantly as new pipelines are built and old ones are decommissioned.) As of 2015, 69,436 miles (or 2.6 percent) carry crude onshore. In terms of spills per mile of pipeline, if we divide the number of spills by the number of pipeline miles,
* Roughly 3.3 spills happen each year for every 1,000 miles of onshore crude oil pipeline.
* Roughly half a barrel is spilled each year per mile of onshore crude oil pipeline.

But we’re not done yet! Looking at spills per mile only tells part of the story; we also need to know how much oil is flowing through that pipeline. For this, we’ll use a concept called barrel-miles. It’s kind of like how if we are looking at traffic safety, we can’t just look at how many cars are on the road. We also need to know how far they travel. 

Applying this concept to oil pipelines, consider a 10,000 mile long pipeline with a flow rate of one barrel per second, compared with a one mile long pipeline carrying 10,000 barrels per second. Over the course of a day, they will transport the same amount of oil – the 864 million barrel-miles – even though the length and flow of each pipe varies greatly.

In 2015, 2.7 trillion barrel-miles moved through the U.S. crude oil pipeline network. This mind-boggling number has been increasing over the past few years, up 50 percent since 2010. In the past few years,
* Each year, there’s an average of about 1 spill per 10 billion barrel-miles of crude moved
* And each year, an average of half a barrel is spilled per million barrel-miles of crude moved
Phew! But what the heck does that mean for Dakota Access? Let’s take a look.

## What does this look like if we apply it to the Dakota Access pipeline, specifically?
The entire Dakota Access pipeline covers 1,172 miles, with a planned initial flow rate of 470,000 barrels per day, and an eventual capacity of 570,000 barrels per day, according to a [fact sheet from Energy Transfer Partners.](http://www.daplpipelinefacts.com/docs-dapl/08092016/DAPL_FactSheet33-8_09_16.pdf)


Applying what we know about spill rates, if we extrapolate the average spill rates per mile, we can expect about 3.9 spills per year, leaking an estimated 640 barrels of crude. (We got this by averaging the annual number of spills and barrels per mile from 2010 to 2015 by 1,172.)


However, if we extrapolate based on the average spill rates per barrel-mile, we can expect roughly 19 spills per year at the initial flow rate, rising to 23 spills per year at the eventual flow rate. In terms of barrels leaked, initially the average would be 3,145 barrels per year, rising to 3,184 barrels per year.


As we said before, this is a back of the napkin calculation. No one can’t predict the future, and analyses like these still have to be evaluated against the question: What risk is acceptable?
