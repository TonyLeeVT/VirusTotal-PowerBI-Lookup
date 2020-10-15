# VirusTotal-PowerBI-Lookup
A Power BI Report that accepts your VT API Key and a resource (ex:  hash) to query

## Background
This Power BI Template is based on the following blog article:  
Coming soon...


## Prerequisites
1. VirusTotal API key (can be the free account key as well, so go create that account if you don't have one!) 
2. Microsoft Power BI Desktop
3. Microsoft Power BI Service (Online) to share report and schedule updates


## How to use
1. Download the Power BI template (.pbit)
2. Open the template
3. Enter your VT API Key and the hash you want to query
4. Wait for data to load
5. Ensure reports are populated and working properly
6. To update the hash:  Home > Transform Data > Edit parameters


## Possible limitations
1. Unable to modify hash parameter from report / dashboard to refresh data feed with new data natively from Power BI
2. Drill through lookup using hash from previous report may be limited due to parameter update issue
3. Potential for AV column rename to fail due to hard coded AV vendor names in power query
4. Error handling could be improved for instances where VirusTotal does not have the data
   Ex:  "response_code": 0 vs. "response_code": 1

## Screenshots
![Dashboard](https://github.com/TonyLeeVT/)
