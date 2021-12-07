# Implementation Guide


## Preparation for package building 
1. Install JDK
2. Install Ruby <https://rubyinstaller.org>
3. Install Jekyll (tool to build static html pages based on Ruby) <https://jekyllrb.com/docs/installation>
4. Download the latest publisher from <https://github.com/HL7/fhir-ig-publisher/releases> into `package`


## Build Implementation
1. Run `java -jar publisher.jar -ig ig.ini` from `package` working directory


## Clean Up
1. Delete following folders
   1. `package/output`
   2. `package/temp`
   3. `package/template`
