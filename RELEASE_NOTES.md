### 0.9.0 - 8th May 2014
* Fixed nuget package deployment
* Sorted namespacing
* Refactored lots of code
* Introduced F# scaffold project structure

### 0.9.1 - 16th May 2014
* Fixed namespace clash between Type Provider and parent provider type class
* Added ability to retrieve the name of a blob and table programmatically
* Removed EntityId from the LightweightTableEntity and replaced with separate PartitionKey and RowKey properties
* LightweightTableEntity made public and changed to a class rather than a record

### 0.9.2 - Unreleased
* Fixed a bug whereby provided type constructors sometimes mixed up field names and their values.