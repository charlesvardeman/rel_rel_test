Simple example SPARQL queries for the Relative Relationship ODP.

To execute from Apache Jena ARQ command line:
```bash
arq --data WOP_Poster_Triples.ttl --query WOP_Poster_Triples_q1.rq
```

To produce a pdf graph file using raptor and a graphviz.
```bash
rapper -i turtle -o dot WOP_Poster_Triples.ttl > junk.dot
 dot junk.dot -Ktwopi -Tpdf >junk.pdf
 ```
