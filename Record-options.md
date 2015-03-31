#Record Options
_This file sets out the record options and matches the elements in the **[Content Template](/Entry%20Content%20Template.md)** to specific ontologies. The goal is to then create a Jeykell instance which will work off of the content of the output._

##Vocabularies
_There are four vocabularies we are working with these are:
* [OLAC](http://www.language-archives.org/documents.html) - A vocabulary for describing resources about linguistic works
* [Dublin Core Metadata Element Set, Version 1.1](http://dublincore.org/documents/dces/#DCTERMS) - This is a general metadata description set that other descriptors build upon.
* [DOAP](https://github.com/edumbill/doap/wiki) - This vocabulary is used for describing software projects.
* [FOAF](http://xmlns.com/foaf/spec/) - This is a vocabulary for describing people.

###Additional ontologies infered
* OLAC and Doublin Core both refeence the ISO 639-3 as a vocabulary.
* OLAC References the [MARC Code List for Relators](http://www.loc.gov/marc/relators/relaterm.html).
* DCMI Terms can be found here: http://dublincore.org/documents/dcmi-terms/
* DCMI use the DCMI Type Vocabulary http://dublincore.org/documents/dcmi-type-vocabulary/ 


##Expression
_Expressions are basically Key:Value pairs where the key is the declaration of the vocabulary and the ontology. And the value is one of the apporoved items for that key._

Vocabulary.ontology:value

olac.linguistic-subject:lexicgraphy
olac.language-extension:eng
olac.language-extension:deu

doap.
dc.
foaf.



[olac.linguistic-subject](http://www.language-archives.org/REC/field.html): options: 

* anthropological_linguistics
* applied_linguistics
* cognitive_science
* computational_linguistics
* discourse_analysis
* forensic_linguistics
* general_linguistics
* historical_linguistics
* history_of_linguistics
* language_acquisition
* language_documentation
* lexicography
* linguistics_and_literature
* linguistic_theories
* mathematical_linguistics
* morphology
* neurolinguistics
* philosophy_of_language
* phonetics
* phonology
* pragmatics
* psycholinguistics
* semantics
* sociolinguistics
* syntax
* text_and_corpus_linguistics
* translating_and_interpreting
* typology
* writing_systems

[olac.language-extension](http://www.language-archives.org/REC/language.html): options 

[olac.role](http://www.language-archives.org/REC/role.html): options