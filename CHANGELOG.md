
#Change log for osm-flink-tools


##Version 0.1 - May 2016

- Improve the OSMProcess by 1/3 in reading each elements (Nodes/Ways/Rels) in a separate stream instead of a single input stream.
- Bug fixes for NPE, especially for data inconsistency
- Integrate Planet on a M4.Large AWS EC2 instance (bench could be also done on a hadoop cluster)
- Switch to 1.0.3 flink version

## Before 0.1 - October 2015 - 2016

- Setting up the project using elements implemented on [OSMMImport](https://github.com/frett27/OSMImport)

#Credits

- Crosby for the pbf specification implementation in Java and wrappers (protobuf)
	- Decoding is not currently used (for splitting the reading in several Blocks / Splits)

#RoadMap