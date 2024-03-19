# qualifier-dictionary
Qualifier dictionary of qualifier for the Asset Administration Shell (AAS)

Id of the dictionary = urn:aas-connect:qualifierdictionary

There is currently no standardized (from IDTA specified) dictionary for Qualifier. 
This repository lists known Qualifier for the Asset Administration Shell that can be used.   
<b>Please open an issue in order to propose further Qualifier.</b>

The format of the semanticId for the Qualifier is:   
semanticId=urn:aas-connect:qfr:[type]:[revision]  


| assetClassName (status)     | assetClassId / description                                                  | 
| --------------------------- | --------------------------------------------------------------------------- | 
| workStation *active*        | urn:aas-connect:assetclass:workstation:1:0:bffba008-3087-4eee-881a-d6000031f7be     |
|                             |single work station that is fully automated or where manual work is been done by one or more employees    
| serviceRequest *active*     | urn:aas-connect:assetclass:servicerequest:1:0:bffba008-3087-4eee-881a-d6000031f7be  |
|                             |request to perform a service task on an asset    
| material *active*           | urn:aas-connect:assetclass:material:1:0:bffba008-3087-4eee-881a-d6000031f7be  |
|                             |material, component or part that is part of a physical product that can be sold 
