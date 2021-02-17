Entity: SMCollection  
====================





- No required properties  






  "id": "urn:ngsi-ld:SMCollection:001",
  "type": "SMCollection",
  "description": "this is a collection of posts",
  "location": {
    "type": "Point",
    "coordinates": 
	 [
	  40.3,
	  25.5
	 ]
	},
  "hasPosts": ["urn:ngsi-ld:SMPost:125","urn:ngsi-ld:SMPost:124"],
  "isAnalyzedBy": "urn:ngsi-ld:Analysis:331"
}
```  






  "id": "urn:ngsi-ld:SMCollection:001",
  "type": "SMCollection",
  "description": {
    "type": "Property",
    "value": "this is a collection of posts"
  },
  "location": {
    "type": "GeoProperty",
	"value": {
	 "type": "Point",
	 "coordinates": 
	 [
	  40.3,
	  25.5
	 ]
	}
  },
  "hasPosts": [
  {
   "type": "Relationship",
   "object": "urn:ngsi-ld:SMPost:125",
   "datasetId": "urn:ngsi-ld:Dataset:01"
  },
  {
   "type": "Relationship",
   "object": "urn:ngsi-ld:SMPost:124",
   "datasetId": "urn:ngsi-ld:Dataset:camera:01"
  }
  ],
   "isAnalyzedBy": {
   "type": "Relationship",
   "object": "urn:ngsi-ld:Analysis:331"
   },
  "@context": [
    "https://schema.lab.fiware.org/ld/context"
  ]
}
```  