# Hello!

We are a collective working to make a free and open source alert & reporting system for Air Quality called "SpikeAlerts".

## Background 

When Canadian wildfires blanketed US cities in the summer of 2023, air quality rose to the forefront of public concern across the country. In Minneapolis, the fight for the East Phillips Urban Farm also raised air quality as an environmental justice issue in the public consciousness. Asthma and other health issues are clearly higher in Minneapolis neighborhoods which were [redlined](https://legacy.yourwebedition.com/stories/a-city-divided-0) and have more polluting facilities, particularly in North Minneapolis, a majority black neighborhood, and the Phillips and Cedar-Riverside neighborhoods in south Minneapolis, which have high Indigenous and immigrant populations. 

Federal regulations that monitor air quality at a regional level leave large gaps in data in terms of knowing what people in a particular block or neighborhood are exposed to. [Community-Based Air Quality Monitoring](https://www.georgetownclimate.org/articles/community-based-air-quality-monitoring-equitable-climate-policy.htm) (CBAQM) projects address those gaps by monitoring air quality at a neighborhood level.

Community organizers concerned about air quality have also come up with a variety of ways of tracking data and using it to hold governments and industry accountable for the poison put into our air. In Pittsburgh, for example, [Smell PHG](https://smellpgh.org) crowdsources information about smells to track pollutants that pose health risks to residents. **This is a crucial intervention because it treats people’s lived experiences as valid data.** 

[The City of Minneapolis](https://www.minneapolismn.gov/government/programs-initiatives/environmental-programs/air-quality/) has engaged in CBAM by putting up and maintaining [PurpleAir](https://map.purpleair.com/1/mAQI/a10/p604800/cC0#11/44.9368/-93.2834) monitors, a system which provides real-time readings of PM 2.5 readings. This is a very important investment. However, there is a gap between simply making data available to the public and making an active effort to deliver it to people who need it. The Air Quality Alerts system sets out to close the gap, by providing an easy way to get updates about bad air quality only when there is a significant spike. 

Air quality monitoring initiatives usually emphasize long-term exposure. However, acute exposure at certain levels also presents significant health risks. Future iterations of this project could offer daily, weekly or monthly air quality reports, but this version chooses to focus on 'spikes', which represent possible acute (short-term) exposure events.

We believe clean air is a human right. We believe communities deserve to know exactly what we are breathing in, when, and what effects it might have on our health. This alert system is intended to be a tool to facilitate awareness and capacity to fight against those that would treat marginalized  communities as sacrifice zones. 

## Installation Instructions

 For development or personal use

+ Clone the [SpikeAlerts](https://github.com/SpikeAlerts/SpikeAlerts) repository and follow the Readme steps

## Estimated Costs:  
Funding and deployment: Long term use and deployment requires an organizational sponsor or community fundraising. 
+ Database: ~ $50/month for a committed database using a cloud server
+ App: ~ $7/month for a Virtual Machine (Heroku Dyno, Google Compute Engine, ...)
+ Texts via Twilio:  $.0079/text adds up quick! You may want to apply for a their [Impact Access Program](https://www.twilio.org/support-and-resources/impact-access-program)
    + Alternatively, alerts could also be sent out via email, a mobile app, or social media to keep costs down.
 
## Other Steps to get going:
+ Construct a Website, Sign-Up form, and Report/Observation form
+ Get the word out!
+ Health training: Folks should be educated on how to respond to alerts and messages. For instance, teachers and parents could sign up for alerts so they are aware when it is not safe to have students/children outside. 
+ Organizing: While protecting ourselves from dangerous air quality in the moment is useful, our ultimate goal is to shut down the facilities and infrastructure that creates these problems. We can imagine this tool being integrated with organizing efforts in a variety of ways –  ultimately this information is only as powerful as the communities that use it. 

## Authors of this Readme

Priya Dalal-Whelan

Rob Hendrickson

## Foundational Developers

Rob Hendrickson

Priya Dalal-Whelan

Dan Raskin

Mateo Frumholtz

Doug Carmody

## Other Contributors 
Thank you for organizing, discussion, feedback, research, sensor installation & maintenance...

Connor Stratton, Urszula Parfieniuk, Nazir Khan, Jenni Lansing, Lucy Shapiro, Alice Froehlich, Megan Greenberg, Mary Marek-Spartz, Kerry Wang, Daniel Furata, Eamonn Fetherston, Jake Ford

We also acknowledge the preliminary work of the [Quality Air, Quality Cities team](https://github.com/RTGS-Lab/QualityAirQualityCities).
