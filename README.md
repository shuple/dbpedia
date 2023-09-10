# Query DBpedia
As I go through a SPARQL text, I've been adapting the example queries to focus on 'DBpedia,' making the learning process even more engaging, at least for me.

## Installation
Clone the repository.
```bash
git clone https://github.com/shuple/query-dbpedia
```

## Usage
Copy and paste the query in <a href="https://github.com/shuple/query-dbpedia/tree/master/sparql">sample</a>/ to https://dbpedia.org/sparql.
If you prefer a command line, there is a Python CLI companion for effortless SPARQL endpoint and RDF file interactions.

```bash
git clone https://github.com/shuple/sparqly
python3 sparqly/sparqly_query.py query-dbpedia/sparql/object.sparql
```
<pre>
------------------------
 dbr:Noodles_(musician)
 dbr:Dexter_Holland
</pre>

## Changelog
##### 0.1a (2023-09-04)
- Initial Alpha Release.
