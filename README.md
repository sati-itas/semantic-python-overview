# Semantic Python Overview

This repository aims to collect and curate a list of projects which are related both to python and semantic technologies (RDF, OWL, Reasoning, ...). It is inspired by collections like [awesome lists](https://github.com/sindresorhus/awesome#readme). The list might be incomplete and biased, due to the limited knowledge of its author(s).  Improvements are very welcome. Feel free to file an issue or a pull request. Every section is alphabetically sorted.


## Established Projects

- [Cooking with Python and KBpedia](https://www.mkbergman.com/cooking-with-python-and-kbpedia/)
    - Tutorial series on "how to pick tools and then use Python for using and manipulating the KBpedia knowledge graph"
    - [Material in form of Jupyter Notebooks](https://github.com/Cognonto/CWPK),
    - accompanying python package [cowpoke](https://github.com/Cognonto/cowpoke),
- [FunOwl](https://github.com/hsolbrig/funowl) – functional OWL syntax for Python
  - features:
    - provide a pythonic API that follows the OWL functional model for constructing OWL
- [gizmos](https://github.com/ontodev/gizmos) – Utilities for ontology development
    - features:
        - modules for "export", "extract", "tree"-rendering
- [Jabberwocky](https://github.com/sap218/jabberwocky) – a toolkit for ontologies
    - features:
        - associated text mining using an ontology terms & synonyms
        - tf-idf for synonym curation then adding those synonyms into an ontology
- [OntoPilot](https://github.com/stuckyb/ontopilot) – software for ontology development and deployment
  - docs: https://github.com/stuckyb/ontopilot/wiki
  - features:
    - support end users in ontology development, documentation and maintainance
    - convert spreadsheet data (one entity per row) to owl files
    - call a reasoner before triple-store insertion
- [ontospy](https://github.com/lambdamusic/Ontospy) – Python library and command-line interface for inspecting and visualizing RDF models
  - docs: http://lambdamusic.github.io/Ontospy/
  - features:
    - extract and print out any ontology-related information
    - convert different OWL syntax variants
    - generate html documentation for an ontology
- [owlready2](https://bitbucket.org/jibalamy/owlready2/src/master/README.rst) – ontology oriented programming in Python
  - docs: https://owlready2.readthedocs.io/en/latest/index.html
  - features:
    - parse owl files (RDF/XML or OWL/XML)
    - parse SWRL rules
    - call reasoner (via java)
  - literature references:
    - [*Lamy, JB: Owlready: **Ontology-oriented programming in Python with automatic classification and high level constructs for biomedical ontologies**. Artificial Intelligence In Medicine 2017;80:11-28*](http://www.lesfleursdunormal.fr/_downloads/article_owlready_aim_2017.pdf)
    - [*Lamy, JB: **Ontologies with Python**, Apress, 2020*](https://www.apress.com/fr/book/9781484265512)
        - accompanying material: <https://github.com/Apress/ontologies-w-python>
- [rdflib](https://github.com/RDFLib/rdflib) – Python package for working with RDF
  - docs: https://rdflib.readthedocs.io/
  - graphical package overview: https://rdflib.dev/
  - features:
    - parsers and serializers for RDF/XML, NTriples, Turtle and more
    - a graph interface which can be backed by any one of a number of store implementations
    - store implementations for in-memory storage and persistent storage
    - a SPARQL 1.1 implementation – supporting SPARQL 1.1 Queries and Update statements


## Probably Stalled or Outdated Projects

- [Athene](https://github.com/dityas/Athene) DL reasoner in pure python
    - "[C]urrent version is a beta and only supports ALC. But it can easily be extended by adding tableau rules."
    - Last update: 2017
- [cwm](https://en.wikipedia.org/wiki/Cwm_(software))
    - Self description: "\[cwm is a\] forward chaining semantic reasoner that can be used for querying, checking, transforming and filtering information".
    - Created in 2000 by Tim Berners-Lee and Dan Connolly, see [w3.org](https://www.w3.org/2000/10/swap/doc/cwm)
- [air-reasoner](https://github.com/mit-dig/air-reasoner)
    - Self description: "Reasoner for the AIR policy language, based on cwm"
    - based on cwm
    - Last update: 2013
- [FuXi](https://pypi.org/project/FuXi/)
    - Self description: "An OWL / N3-based in-memory, logic reasoning system for RDF"
    - based on cwm
    - Last update: 2013
    - see also <http://code.google.com/p/python-dlp/wiki/FuXi> <http://code.google.com/p/fuxi/source/browse/> (hg-repo)


## Further Projects / Links

- [github-semantic-web-python](https://github.com/topics/semantic-web?l=python) – github project search with `topic=semantic-web` and `language=python`
- [Pywikibot](https://github.com/wikimedia/pywikibot)
    - Library to interact with Wikidata and Wikimedia API
    - see also: https://www.wikidata.org/wiki/Wikidata:Creating_a_bot#Pywikibot
- [semantic](https://github.com/crm416/semantic) – Python library for extracting semantic information from text, such as dates and numbers
- [Solving Einstein Puzzle](https://github.com/cknoll/demo-material/blob/main/expertise_system/einstein-zebra-puzzle-owlready-solution1.ipynb) – jupyter notebook demonstrating how to use owlready2 to solve a logic puzzle
- [W3C-Link-List1](https://www.w3.org/2001/sw/wiki/SemanticWebTools#Python_Developers) – link list "SemanticWebTools", section "Python_Developers" (wiki page)
  - might be outdated
- [W3C-Link-List2](https://www.w3.org/2001/sw/wiki/Python) – list of tools usable from, or with, Python (wiki page)
- [wikidata-mayors](https://github.com/njanakiev/wikidata-mayors)
    - Python code to ask wikidata for european mayors and where they where born
    - Article: https://towardsdatascience.com/where-do-mayors-come-from-querying-wikidata-with-python-and-sparql-91f3c0af22e2
- [yamlpyowl](https://github.com/cknoll/yamlpyowl) – read an yaml-specified ontology into python by means of owlready2 (experimental)
