README

This data file is published by the Movebank Data Repository (www.datarepository.movebank.org). As of the time of publication, a version of this published animal tracking dataset can be viewed on Movebank (www.movebank.org) in the study "Blue and fin whales Southern California 2014-2015 - Fastloc GPS data" (Movebank Study ID 943824007). Individual attributes in the data files are defined below, in the NERC Vocabulary Server at http://vocab.nerc.ac.uk/collection/MVB and in the Movebank Attribute Dictionary at www.movebank.org/node/2381. Metadata describing this data package are maintained at https://datacite.org.

This data package includes the following data files:
Blue and fin whales Southern California  2014-2015 - Fastloc GPS data.csv
Blue and fin whales Southern California  2014-2015 - Fastloc GPS data-reference-data.csv
Blue-Fin California Bouts Data.csv
Blue-Fin California Dives Data.csv

Data package citation:
Irvine LM, Palacios DM, Lagerquist BA, Mate BR, Follett TM (2019) Data from: Scales of blue and fin whale feeding behavior off California, USA, with implications for prey patchiness. Movebank Data Repository. https://doi.org/10.5441/001/1.47h576f2

These data are described in the following written publication:
Irvine LM, Palacios DM, Lagerquist BA, Mate BR (2019) Scales of blue and fin whale feeding behavior off California, USA, with implications for prey patchiness. Frontiers in Ecology and Evolution 7: 338. https://doi.org/10.3389/fevo.2019.00338

-----------

Terms of Use
This data file is licensed by the Creative Commons Zero (CC0 1.0) license. The intent of this license is to facilitate the re-use of works. The Creative Commons Zero license is a "no rights reserved" license that allows copyright holders to opt out of copyright protections automatically extended by copyright and other laws, thus placing works in the public domain with as little legal restriction as possible. However, works published with this license must still be appropriately cited following professional and ethical standards for academic citation.

We highly recommend that you contact the data creator if possible if you will be re-using or re-analyzing data in this file. Researchers will likely be interested in learning about new uses of their data, might also have important insights about how to properly analyze and interpret their data, and/or might have additional data they would be willing to contribute to your project. Feel free to contact us at support@movebank.org if you need assistance contacting data owners.

See here for the full description of this license
http://creativecommons.org/publicdomain/zero/1.0

-----------

Data Attributes
These definitions come from the Movebank Attribute Dictionary, available at http://vocab.nerc.ac.uk/collection/MVB and www.movebank.org/node/2381.

animal ID: An individual identifier for the animal, provided by the data owner. If the data owner does not provide an Animal ID, an internal Movebank animal identifier is sometimes shown. 
example: 91876A, Gary
units: none
entity described: individual
same as: individual local identifier

animal life stage: The age class or life stage of the animal at the beginning of the deployment. Can be years or months of age or terms such as 'adult', 'subadult' and 'juvenile'. Best practice is to define units in the values if needed (e.g. '2 years').
example: juvenile, adult
units: not defined
entity described: deployment

animal sex: The sex of the animal. Allowed values are 
m = male
f = female
format: controlled list
entity described: individual

animal taxon: The scientific name of the species on which the tag was deployed, as defined by the Integrated Taxonomic Information System (ITIS, www.itis.gov). If the species name can not be provided, this should be the lowest level taxonomic rank that can be determined and that is used in the ITIS taxonomy. Additional information can be provided using the term 'taxon detail'. 
example: Buteo swainsoni
format: controlled list
entity described: individual
same as: individual taxon canonical name

attachment type: The way a tag is attached to an animal. Values are chosen from a controlled list: 
collar = The tag is attached by a collar around the animal's neck
glue = The tag is attached to the animal using glue
harness = The tag is attached to the animal using a harness
implant = The tag is placed under the skin of the animal
tape = The tag is attached to the animal using tape
other = user specified 
format: controlled list
entity described: deployment

deploy off timestamp: The timestamp when the tag deployment ended. 
example: 2009-10-01 12:00:00.000
format: yyyy-MM-dd HH:mm:ss.SSS
units: UTC or GPS time
entity described: deployment
same as: deploy off date

deploy on latitude: The geographic latitude of the location where the animal was released (intended primarily for instances in which the animal release and tag retrieval locations have higher accuracy than those derived from sensor data). 
example: 27.3516
units: decimal degrees, WGS84 reference system
entity described: deployment

deploy on longitude: The geographic longitude of the location where the animal was released (intended primarily for instances in which the animal release and tag retrieval locations have higher accuracy than those derived from sensor data).
example: -97.3321
units: decimal degrees, WGS84 reference system
entity described: deployment

deploy on timestamp: The timestamp when the tag deployment started. 
example: 2008-08-30 18:00:00.000 
format: yyyy-MM-dd HH:mm:ss.SSS 
units: UTC or GPS time
entity described: deployment
same as: deploy on date

deployment ID: A unique identifier for the deployment of a tag on animal, provided by the data owner. If the data owner does not provide a Deployment ID, an internal Movebank deployment identifier may sometimes be shown. 
example: Jane-Tag42 
units: none 
entity described: deployment

event ID: An identifier for the set of values associated with each event, i.e. sensor measurement. A unique event ID is assigned to every time-location or other time-measurement record in Movebank. If multiple measurements are included within a single row of a data file, they will share an event ID. If users import the same sensor measurement to Movebank multiple times, a separate event ID will be assigned to each. 
example: 6340565
units: none
entity described: event

GPS satellite count
The number of GPS satellites used to estimate the location. 
example: 8
units: none
entity described: event

location error numerical: An estimate of the horizontal error of the location including only numbers. (If the error estimates include non-numerical characters such as '>' use 'location error text'.) These values can be described using 'location error percentile' and 'location accuracy comments'.
example: 50
units: m
entity described: event

location lat: The geographic longitude of the location as estimated by the sensor. Positive values are east of the Greenwich Meridian, negative values are west of it. example: -41.0982423 
units: decimal degrees, WGS84 reference system 
entity described: event

location long: The geographic longitude of the location as estimated by the sensor. Positive values are east of the Greenwich Meridian, negative values are west of it. 
example: -121.1761111 
units: decimal degrees, WGS84 reference system 
entity described: event

manipulation type: The way in which the animal was manipulated during the deployment. Values are chosen from a controlled list: 
confined = The animal's movement was restricted to within a defined area
none = The animal received no treatment other than the tag attachment
relocated = The animal was released from a site other than the one at which it was captured
manipulated other = The animal was manipulated in some other way, such as a physiological manipulation. 
format: controlled list 
entity described: deployment

manually marked outlier: Identifies events flagged manually as outliers, typically using the Event Editor in Movebank, and may also include outliers identified using other methods. Outliers have the value TRUE. 
units: none
entity described: event

sensor type: The type of sensor with which data were collected. All sensors are associated with a tag id, and tags can contain multiple sensor types. Each event record in Movebank is assigned one sensor type. If values from multiple sensors are reported in a single event, the primary sensor is used. Values are chosen from a controlled list: 
acceleration = The sensor collects acceleration data
accessory measurements = The sensor collects accessory measurements, such as battery voltage
Argos Doppler shift = The sensor uses Argos Doppler shift to determine position
barometer = The sensor records air or water pressure
bird ring = The animal is identified by a band or ring that has a unique identifier
GPS = The sensor uses GPS to determine location
magnetometer = The sensor records the magnetic field
natural mark = The animal is identified by a unique natural marking
orientation = Quaternion components describing the orientation of the tag are derived from accelerometer and gyroscope measurements
radio transmitter = The sensor is a classical radio transmitter
solar geolocator = The sensor collects light levels, which are used to determine position (for processed locations)
solar geolocator raw = The sensor collects light levels, which are used to determine position (for raw light-level measurements)
solar geolocator twilight = The sensor collects light levels, which are used to determine position (for twilights calculated from light-level measurements). 
format: controlled list
entity described: event

study name: The name of the study in Movebank. 
example: Coyotes, Kays and Bogan, Albany NY
units: none
entity described: study, event

tag ID: A unique identifier for the tag, provided by the data owner. If the data owner does not provide a tag ID, an internal Movebank tag identifier may sometimes be shown. example: 2342 
units: none 
entity described: tag
same as: tag local identifier

tag manufacturer name: The company or person that produced the tag. 
example: Holohil
units: none
entity described: tag

tag model: The model of the tag. 
example: T61 
units: none 
entity described: tag

tag readout method: The way the data are received from the tag. Values are chosen from a controlled list: 
satellite = Data are transferred via satellite 
phone network = Data are transferred via a phone network, such as GSM or AMPS
other wireless = Data are transferred via another form of wireless data transfer, such as a VHF transmitter/receiver
tag retrieval = The tag must be physically retrieved in order to obtain the data.
format: controlled list
entity described: deployment

timestamp: The date and time corresponding to a sensor measurement or an estimate derived from sensor measurements. 
example: 2008-08-14 18:31:00.000 
format: yyyy-MM-dd HH:mm:ss.SSS 
units: UTC or GPS time 
entity described: event

visible: Determines whether an event is visible on the Movebank map. Values are calculated automatically, with TRUE indicating the event has not been flagged as an outlier by 'algorithm marked outlier', 'import marked outlier' or 'manually marked outlier', or that the user has overridden the results of these outlier attributes using 'manually marked valid' = TRUE. Allowed values are TRUE or FALSE. 
units: none 
entity described: event

-----------

File Blue-Fin California Bouts Data.csv

This file contains summaries of dive behavior that occurred during feeding bouts, as defined in the Methods of Irvine et al. (2019). Dives were grouped into feeding bouts if  no more than 60 minutes elapsed between feeding dives (dives with at least one lunge). 

Note: Only bouts with at least three Fastloc GPS locations are summarized.

Column descriptions:

animal-id: Same as "animal ID" above. 

BoutIndicator: Identifier of the unique feeding bout being summarized. 

NumDives: Number of dives > 10 m depth that occurred during the bout. 

AveLocTimeDiff: Average time difference (minutes) between each dive in the bout and the temporally closest Fastloc GPS location. This is the average of the 'TimeDifference' values from the 'Blue-Fin California Dives Data.csv' file for all dives that occurred during the bout. 

maxLocTimeDiff: Maximum time difference (minutes) between a dive in the bout and the temporally closest Fastloc GPS location. 

numLocs10minFromADive: Number of dives within the bout that had a FastLoc GPS location within 10 min. 

divesNoLunges: Number of non-feeding dives within the bout (dives that did not record a feeding lunge). 

boutStart: Date and time (GMT) of the start of the first dive in the bout. 

boutEnd: Date and time (GMT) of the end of the last dive in the bout. 

BoutDuration_h: Duration of the bout (hours). 

AveMaxDepthAllDives: Mean maximum dive depth (meters) of all dives that occurred in the bout. 

sdMaxDepth: Standard deviation of the maximum dive depth of all dives that occurred in the bout. 

aveDuration: Mean duration (minutes) of all dives that occurred in the bout. 

sdDuration: Standard deviation of dive durations of all dives that occurred in the bout. 

aveLungesAllDives: Mean number of lunges per dive for all dives that occurred in the bout. 

MeanLat: Mean latitude of all dives that occurred in the bout. 

MeanLon: Mean longitude of all dives that occurred in the bout. 

areaOfBout_km_sq: Area of the bout (square kilometers) calculated by generating a minimum convex ploygon around locations of all dives that occurred in the bout. 

distToClosestBout_km: Distance (kilometers) between the next closest bout and the current bout. Calculated by finding the minimum geographic distance between the the current bout area polygon and all other bout area polygons (i.e., the closest point of the current polygon to the closest point of another polygon), then selecting the smallest value. A value of 0 means some part of the bout area polygons are overlapping. 

closestBout: The 'BoutIndicator' identifier of the closest feeding bout to the bout being summarized. 

numOverlappingBout: Number of other bout area polygons which overlap the feeding bout being summarized. 

distToNextBout_km: Distance (kilometers) from the feeding bout being summarized to the next feeding bout. Note: this differs from 'distToClosestBout' because it looks at the feeding bouts in the temporal sequence in which they occurred, while 'distToClosestBout' looks at the closest bout of all bouts regardless of when they occurred. 

timeToNextBout_hr: The elapsed time (hours) between the end of the bout being summarized and the start of the next feeding bout. 

DistFromShore_km: Distance (kilometers) of the feeding bout from the closest point of land. Calculated similar to 'distanceToClosestBout' where the minimum geographic distance between the feeding bout area polygon and the land polygon was used. 

BottomDepth_m: Water depth (meters) at the average location of each feeding bout (MeanLon, MeanLat) using  the Global Multi-Resolution Topography Synthesis (GMRT) data set. (Ref: Ryan WBF, Carbotte SM, Coplan JO, O'Hara S, Melkonian A, Arko R, Weissel RA, Ferrini V,  Goodwillie A, Nitsche F, Bonczkowski J, Zemsky R (2009) Global Multi-Resolution Topography (GMRT) synthesis data set. Geochemistry, Geophysics, Geosystems 10(3): Q03014. https://doi.org/10.1029/2008GC002332)

-----------

File Blue-Fin California Dives Data.csv

Contains per-dive summaries of dive and feeding behavior metrics for all dives > 10 m depth. Data are derived from the tag's onboard pressure sensor and accelerometer archives, which were sampled at 1 Hz. (see manuscript Methods for further detail)

Column descriptions:

animal-id: Same as "animal ID" above. 

DiveDateStart: Date and time (GMT) when a dive > 10 m started. 

DiveDateEnd: Date and time (GMT) when a dive > 10 m ended. 

LocationDate: Date and time (GMT) of the temporally closest location to the dive. 

TimeDifference: The difference in time (minutes) between the dive and the temporally closest Fastloc GPS location. 

Lat: Latitude of the location assigned to the dive. 

Lon: Longitude of the location assigned to the dive. 

DiveDuration: Duration of the dive (minutes). 

MaxDiveDepth: Maximum depth (meters) reached during the dive. 

NumLunges: Number of feeding lunges detected during the dive using the lunge detection algorithm described in the manuscript and associated supplementary material. 

BoutIndicator: Unique identifier of the dive's associated feeding bout. 
NOTE: Sequences > 60 min with no feeding dives were marked '0'. Not all BoutsIndicator values here are reported in the bout summary file, as only bouts with at least 3 Fastloc GPS locations were summarized. 

-----------

More Information
For more information about this repository, see www.movebank.org/node/15294, the FAQ at www.movebank.org/node/2220, or contact us at support@movebank.org.