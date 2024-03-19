# qualifier-dictionary
Qualifier dictionary of qualifier for the Asset Administration Shell (AAS)

Id of the dictionary = urn:aas-connect:qualifierdictionary

There is currently no standardized (from IDTA specified) dictionary for Qualifier. 
This repository lists known Qualifier for the Asset Administration Shell that can be used.   
<b>Please open an issue in order to propose further Qualifier.</b>

The format of the semanticId for the Qualifier is:   
semanticId=urn:aas-connect:qfr:[type]:[revision]  


| type (status)                 | kind - valueType - value(s) or valueId / description / semanticId / isCaseOf                           | 
| ----------------------------- | ------------------------------------------------------------------------------------------------------ | 
| SMT/Cardinality *active*      | TemplateQualifier - xs:string - "ZeroToOne", "One", "OneToMany", "ZeroToMany"      
|                               | Cardinality of AAS submodel elements used in Submodel Templates (SMT). Cardinality (or multiplicity) defining the lower and upper bound of the number of associated elements to the submodel element that is above in the hierarchy. "ZeroToOne" means optional. "One" means exactly one submodel element is associated. "OneToMany" means at least one submodel element is associated. "ZeroToMany" denotes no or an arbitrary number of submodel elements is associated.
|                               | urn:aas-connect:qfr:smt-cardinality/0 |
|                               | https://admin-shell.io/SubmodelTemplates/Cardinality/1/0 |   
| life cycle qual *active*      | ConceptQualifier - xs:string - "BUILT", "INQ", "OFF", "OP", "SPEC", "SUP", "CON", "DECOM", "OTHERS"      
|                               | Qualifier that specifies a product lifecycle stage or phase in which the assigned value is applicable.
|                               | urn:aas-connect:qfr:life-cycle/0 |
|                               | 0112/2///61360_7#CBA004 | 
