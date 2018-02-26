### Summary 
In the current implementation we use [ShEx](http://shex.io/) expression to represent the [FAIR Data Point](https://github.com/DTL-FAIRData/FAIRDataPoint) (FDP) data model. The ShEx expressions are generated according to the [FAIR Data Point software specification](https://github.com/DTL-FAIRData/FAIRDataPoint/wiki/FAIR-Data-Point-Specification) document.

#### How to use

The ShEx in this repository can be used to validate the metadata content of the FDP. The ShEx in this repository are based on ShEx2 specification. Right now there are very few validation tools available to validate the RDF against the ShEx2 expression. Shex-simple is one such a tool, it is a web based application and it can be accessed via this [link](https://rawgit.com/shexSpec/shex.js/master/doc/shex-simple.html#)   
* FDP metadata schema can be found [here](https://github.com/DTL-FAIRData/MetadataValidation/tree/master/schema) 
* Example FDP metadata RDF files can be found [here](https://github.com/DTL-FAIRData/MetadataValidation/tree/master/example-data)     
