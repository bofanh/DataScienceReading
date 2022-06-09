## [Automatically disambiguating medical acronyms with ontology-aware deep learning](https://www.nature.com/articles/s41467-021-25578-4#Abs1)


### Issue
___
Using machine learning to train clinical and research workflow requires entensive manually labeled datasets. Due to the fact that many abbreviations and acronyms are ambiguous with respect to their sense, complete and accurate text analysis is impossible without identification of the sense that was intended for a given abbreviation or acronym.[[1]](#reference) In this paper research team, they uses the novel data augmentation techniques[[2]](#reference) to improve the accurancy of abbreviation disambiguation.

### Introduction
___





### Data Source
___
1. Clinical Data 
	* [MIMIC III](https://physionet.org/content/mimiciii/1.4/)
		**Clinical Database**

		MIMIC-III is a large, freely-available database comprising deidentified health-related data associated with over forty thousand patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012. The database includes **information such as demographics, vital sign measurements made at the bedside (~1 data point per hour), laboratory test results, procedures, medications, caregiver notes, imaging reports, and mortality (including post-hospital discharge).**

		MIMIC supports a diverse range of analytic studies spanning epidemiology, clinical decision-rule improvement, and electronic tool development. It is notable for three factors: it is freely available to researchers worldwide; it encompasses a diverse and very large population of ICU patients; and it contains highly granular data, including vital signs, laboratory results, and medications.
	
	* [i2b2](https://www.i2b2.org/NLP/DataSets/Main.php)
		**Infomatics for Integrating Biology & the Bedside**
	
		The Shared Tasks for Challenges in NLP for Clinical Data previously conducted through i2b2 are now are now housed in the Department of Biomedical Informatics (DBMI) at Harvard Medical School as n2c2: National NLP Clinical Challenges. The name n2c2 pays tribute to the program's i2b2 origins while recognizing its entry into a new era and organizational home.

		**All annotated and unannotated, deidentified patient discharge summaries** previously made available to the community for research purposes through i2b2.org will now be accessed as n2c2 data sets through the DBMI Data Portal. Previous challenge participants will also access any challenge-specific documents in the Data Portal.

___
2. Clinical Vocabulary Dictionary
	* [CASI](https://conservancy.umn.edu/handle/11299/137703)
		**Clinical Abbreviation Sense Inventory**

		A sense inventory is a **collection of abbreviations and acronyms (short forms) with their possible senses (long forms)**, along with other corresponding information about these terms. For our comprehensive sense inventory for clinical abbreviations and acronyms, a total of 440 most frequently used abbreviations and acronyms were selected from 352,267 dictated clinical notes. 949 senses of each abbreviation and acronym were manually annotated from 500 random instances within clinical notes and lexically aligned with 17,359 long forms of the Unified Medical Language System (UMLS), 5,233 long forms of Another Database of Abbreviations in Medline (ADAM), and 4,879 long forms in Stedman’s Medical Abbreviations, Acronyms & Symbols (4th edition).


	* [UMLS](https://uts.nlm.nih.gov/uts/umls/home) 
		**Search the UMLS by term, code, or UMLS CUI**

		The UMLS Metathesaurus is a large **biomedical thesaurus** that is organized by concept, or meaning. It links synonymous names from over 200 different source vocabularies. The Metathesaurus also identifies useful relationships between concepts and preserves the meanings, concept names, and relationships from each vocabulary.
		
		The UMLS has been used in natural language processing applications such as information retrieval and information extraction systems.[[3]](#reference)

	* [AllAcronyms](https://www.allacronyms.com/_medical)
		**Medical Abbreviations Dictionary**



### Results

### Disscussion

### Methods

### Other
1. 
2. 
### Reference
___
[1. Abbreviation and Acronym Disambiguation in Clinical Discourse](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1560669/)
___
[2. what is novel data augmentation techniques?](https://www.google.com)
___
[3. Automatic Resolution of Ambiguous Terms Based on Machine Learning and Conceptual Relations in the UMLS](https://doi.org/10.1197/jamia.M1101)
