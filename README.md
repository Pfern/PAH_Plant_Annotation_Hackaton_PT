# Plant Annotation Training Material - ELIXIR PT
Annotating field and laboratory datasets for plant data. 
This is a cooperative exercise initiated by Pedro Fernandes and Mario Silva, an initiative of the portuguese participation in EXCELERATE WP7, "Integrating Genomic and Phenotypic Data for Crop and Forest Plants". 

The overall challenge of this use case is to pick exemplar datasets and add phenotypic data in a standardised way, aiming at enhanced interoperability and discoverability.

Our aim is to get acquainted with alternative methods of adding annotation to existing plant datasets of several types and share the results. 

# Resources #

- data (list, mock, reduced datasets, selected for this exercise): 
 * Casuarina (ITQB, Ana Ribeiro)
 * Pinus Pinaster embryo development (ITQB, Célia Miguel e Inês Chaves)
 * Quercus pyrenaica dendrochronology (IBET, Sofia Leal)

- ontologies (list)
  Semantics for experimentation and ecosystems 
    
  * Crop Ontology for field phenotyping data and traits Agronomy ontology and fieldbook (Celine Aubert) 
    
  The idea is to develop an "intelligent" notebook with the defined terms to annotate field experiments that should make use of the traits defined by the trait dictionary or the crop ontology PEAO ENVO Planteome (data query, image annotation):
 
  * Planteome is being developed by Oregon University in collaboration with French groups. 
 
  This ontology is in fact a large ontology that integrates PO, ENVO, CO, TO, GO, PATO, by mapping these ontologies to each other. Unlike the crop ontology it is a species agnostic ontology. Some effort is being done to make the species specific crop ontologies easily mappable by using similar terms and also a similar architecture.
 
- tools (list)

- literature (list)



# Methods #

We develop a Plant Annotation Guide (https://github.com/Pfern/PAH_Plant_Annotation_Hackaton_PT/blob/master/Plant%20Annotation%20Guide) describing how plants can be annotated, including: 
- using Google spreadsheets and possibly add-ons like OntoMaton
- using drop down lists
- how to export the speadsheets to other formats (CSV? TSV?)
- how to maniupulate tables in standardise formats (ISA-tab)
- how to build repositories and maintain them (ISA-bii)
- how to manipulate and merge repositories

The Plant Annotation Guide will be drive an hackaton to train the commuity that will have the following learning outcomes:
- user accessible annotated datasets incorporating phenotypic data and metadata, together with genotypic data.
- data repositories resulting from these datasets
- descriptions of the methods used in the above processes
- simple written instructions for general use of the type "How to..."
- reports with hints on ways to maintain and explore the new repositories
