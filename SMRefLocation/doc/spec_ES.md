Entidad: SMRefLocation  
======================





- No hay propiedades requeridas  






  "id": "urn:ngsi-ld:RefLocation:00",
  "type": "SMRefLocation",
  "locationName": "Thessaloniki",
  "location": {
    "type": "Point",
	"coordinates": 
	 [
	  40.3,
	  25.5
	 ]
	},
  "locationReferencedBy": "urn:ngsi-ld:SMPost:123"
}  
```  






  "id": "urn:ngsi-ld:RefLocation:00",
  "type": "SMRefLocation",
  "locationName": {
    "type": "Property",
    "value": "Thessaloniki"
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
  "locationReferencedBy": {
   "type": "Relationship",
   "object": "urn:ngsi-ld:SMPost:123"
   },
  "@context": [
    "https://schema.lab.fiware.org/ld/context"
  ]
}  
```  