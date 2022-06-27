## Semantic similarity and machine learning with ontologies
___

### Citation

Maxat Kulmanov, Fatima Zohra Smaili, Xin Gao, Robert Hoehndorf, Semantic similarity and machine learning with ontologies, Briefings in Bioinformatics, Volume 22, Issue 4, July 2021, bbaa199, https://doi.org/10.1093/bib/bbaa199

___

### Ontologies

What:

Ontologies are used to provide background knowledge in similarity-based analysis and machine learning models.

How:

This article outline how semantic similarity measures and ontology embeddings can exploit the background knowledge in ontologies and how ontologies can provide constraints that improve machine learning models. 


Why:

In the life sciences, domain-specific knowledge is often encoded in ontologies and in the database and knowledge base that use ontologies for annotation. Hundreds of ontologies have been developed, spanning almost all domains of biological and biomedical research.
The main features biomedical ontologies provide are controlled vocabularies for characterizing biological phenomena and as formalized knowledge bases that formally describe the phenomena within a domain and link them to other related domains
___

### Additional Resources

[Code](https://github.com/bio-ontology-research-group/machine-learning-with-ontologies)

___

### Web Ontology Language (OWL)

[CreateOntology](https://www.cs.man.ac.uk/~horrocks/ISWC2003/Tutorial/examples.pdf)

[OWL-Biomedical-Ontology-Tutorial](http://www.cs.man.ac.uk/~rector/modules/cds/OWL%20Biomedical%20Ontology%20Tutorial-v1.pdf)

The majority of biomedical ontologies are formalized using the Web Ontology Language (OWL), a language based on Description Logic (a decidable fragment of first order predicate logic). 

Example:
The paraphrase for the new information is: Pneumonia “isKindOf Pneumonia”
∃ hasCause Bacterium “hasCause SOME Bacterium”
What it means:
“All bacterial pneumonias are pneumonias”
“All bacterial pneumonia is caused by some bacteria” Represented in simple logic notation as:
BacterialPneumonia → Pneumonia
BacterialPneumonia → causedBy some Bacterium

| Attributes| Description | Example|
| --- | --- | ---|
|Class| Object, Thing| Person, Animal| Class(pp:man complete intersectionOf(pp:person pp:male pp:adult))|
|Properties|describing a kind of relationship between individuals|ObjectProperty(pp:is_pet_of inverseOf(pp:has_pet))||
|Individual|objects in the world,belong to classes,re related to other objects and to data values via properties|Individual(pp:Rex type(pp:dog) value(pp:is_pet_of pp:Mick))|