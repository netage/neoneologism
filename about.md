## About NeoNeologism

NeoNeologism is a web-based RDF Schema vocabulary editor and publishing system. 
With NeoNeologism, you can define vocabularies, consisting of classes and properties. 
These are the building blocks that enable a growing number of web sites to share not just documents, images, videos and applications, 
but also linked data on the web.
The main goal of NeoNeologism is to dramatically reduce the time required to create, publish and modify vocabularies for the web of data.

Quick feature list

* Support for subclasses, subproperties, domains, ranges, inverses, disjointness, functional and inverse functional properties
* Support for XSD datatypes
* Turtle and JSON-LD output
* Vocabularies are served with content negotiation
* Import from file or from the Web
* Mapping to external vocabularies
* Follows the W3C's Best Practice for publishing RDF vocabularies and Cool URIs for the Semantic Web guidelines

What NeoNeologism is not
* NeoNeologism is no ontology editor. If you want to build large and complex domain ontologies, 
if you need the full power of OWL, or if you need sophisticated reasoning services, 
consider applications such as TopBraid Composer, Protégé, or the NeOn Toolkit. 
NeoNeologism is designed for the simpler space of RDF vocabularies. OWL ontologies tend to be about modelling a domain with the formal language of logics; RDF vocabularies thend to be about exchanging and integrating data between systems and on the Web.
* NeoNeologism is no hosted service. To use NeoNeologism, you need to install it on your own web server. 
We do not run a hosted service where you could just sign up for an account and start creating vocabularies.
* NeoNeologism is **NOT YET** a SKOS editor. The Simple Knowledge Organization Scheme (SKOS) is an RDF-based format for 
expressing and exchanging taxonomies, thesauri, and controlled vocabularies. 
NeoNeologism does not support SKOS yet. It only supports RDF Schema, plus selected constructs from OWL.
Limitations

The current version of Neologism has some limitations that you should be aware of before deciding wether it is the right tool for you.

* No permission system. If you create an account for another user on your system, then that user has access to all vocabularies. There is no way of restricting access to certain vocabularies, or to separate groups of users from each other. You should use Neologism only for groups of users where everyone trusts each other.
* No versioning. Changes to a vocabulary cannot be undone and no revision log is kept.
* This version only supports Monolingual vocabularies. There is no support for adding labels/comments in more than one language.

We hope to address these limitations in future versions.

Minimum requirements

* Java 8

---

This text is copied from the original website ( dead link ) http://neologism.deri.ie
