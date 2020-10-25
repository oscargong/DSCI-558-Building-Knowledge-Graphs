# DSCI-558
The assignments I finished and the material used in USC [DSCI-558 Building Knowledge Graphs](https://classes.usc.edu/term-20203/course/dsci-558) course, which brought by [USC Knowledge Graph Center](https://usc-isi-i2.github.io/home/).

## Summaries

|      | Subject                                                      | Library                                                      | Technique                                                    | Description                                                  |
| :--- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1    | Web Scraping                                                 | [Scrapy](https://scrapy.org/)                                |                                                              | Using Scrapy, crawl 10k pages form IMDB, extract attributes from each pages, store the outcome into Json-lines file. |
| 2    | Information Extraction                                       | [spaCy](https://spacy.io)                                    | NLP                                                          | Using spaCy, form actor's biography text, for each attribut, build one Lexical extractor and one Syntactic extractor. |
| 3    | Entity Resolution, Blocking & Knowledge Representation       | [The Record Linkage ToolKit (RLTK)](https://github.com/usc-isi-i2/rltk)<br />[RDFLib](https://rdflib.readthedocs.io/en/stable/) |                                                              | Given two datasets of IMDB and AFI, and a dev dataset. <br />Match records from these 2 datasets (record linkage). Use Blocking to reduce number of paris need to compare. <br />Design a model in [RDF Schema](https://www.w3.org/TR/rdf-schema/), store the result in a [turtle](https://www.w3.org/TR/turtle/) using the designed model. |
| 4    | RDF query                                                    | [ Apache Jena](https://jena.apache.org/tutorials/sparql.html) | [SPARQL](https://www.w3.org/TR/sparql11-query/), [WikiData Query](https://query.wikidata.org/) | Write SPARQL queries to solve several intricate requests.    |
| 5    | IE - Revisit<br />with Weak Supervision and Distant Supervision | [Snorkel](https://www.snorkel.org/)                          | [Weak Supervision](https://dawn.cs.stanford.edu/2017/07/16/weak-supervision/),  [Distant Supervision](http://www.semantic-web-journal.net/system/files/swj742.pdf) |                                                              |
| 6    | PSL and OWL                                                  | [Protégé](https://protege.stanford.edu/)                     |                                                              |                                                              |

## Documents

The W3C documents are hard to read: poorly typography and impossible to mark up. I put my organized version of W3C documents here