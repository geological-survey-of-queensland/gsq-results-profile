# GSQ Results Profile
This profile describes the `Results` concept.

<p align="center">
<img src="model/profile-Results.svg" width="700px"><br>
Figure 1: Survey profile</p>

Figure 1. shows the template Results profile used by GSQ.

## Profile resources

1. [model/](model/) - the *model* folder contains this profile's models in both graphical (SVG) and machine-readable, textual, form ( [RDF](https://www.w3.org/RDF/) turtle).
2. [shapes/](shapes/) - folder containing SHACL shapes files used to validate data's conformance to this profile's model.
3. [profile.ttl](profile.ttl) - the profile declaration. A description of all of the items in this profile (the formal model, validating resources, documentation etc.) according to the W3C's [Profiles Ontology](https://www.w3.org/TR/dx-prof/) which describes how all the parts related to one another, the roles they play (to give *guidance* for use, to *validate* data etc.) and how this profile *profiles* the various standards listed above.

## GSQ classes
Classes used in this profile:

1. [GSQ Geological property](https://github.com/geological-survey-of-queensland/geofeatures-ont)
2. [GSQ Observation](https://github.com/geological-survey-of-queensland/gsq-dataset-profile)
3. [GSQ Dataset](https://github.com/geological-survey-of-queensland/gsq-dataset-profile)

## OWL classes
1. [dct:identifier](https://w3c.github.io/dxwg/dcat/#Property:resource_identifier)
2. [dct:created](https://w3c.github.io/dxwg/dcat/)
3. [dct:modified](https://w3c.github.io/dxwg/dcat/#Property:resource_update_date)
4. [rdfs:seeAlso](https://www.w3.org/TR/rdf-schema/#ch_seealso) - refers to secondary metadata
5. [FOAF document](http://xmlns.com/foaf/spec/#term_Document) - a document with secondary metadata

## [Distribution](https://w3c.github.io/dxwg/dcat/#Class:Distribution) properties not shown in the diagram:
No distribution properties for Results template

## Vocabularies
1. [Results type](https://vocabs.gsq.digital/vocabulary/result-type)

## License
The content of this repository is licensed for use with the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/). See the [license deed](LICENSE) for details.

## Contacts 
*owner*:  
**Mark Gordon**  
*Director - Geoscience Information*  
Geological Survey of Queensland  
<mark.gordon@dnrme.qld.gov.au>   

*author*:  
**Your Name**  
*Your Role Title - Your Unit*  
Geological Survey of Queensland  
<your.email@dnrme.qld.gov.au>
