[introduction](01_introduction.md) | [on the theory of text](02_theory_of_text.md) | [text genres](03_letter.md) | [record vs text](04_records_vs_text.md) | [filtering vs searching](05_filtering_vs_searching.md) | [discussion](06_discussion.md) | [references](07_references.md)

# 4. Records vs Text

a record like object is structured like field: value, field: value
where the values can have predefined datatypes, but usually not
structure

a text like object is a node structured like node, node, node, node,
where each node can have structure and different semantics and
datatypes

Searching text inside a play: [genre_ssi:play and speaker_tesim:adda and text_tesim:"jeg har kun ventet paa dig"](http://public-index.kb.dk/solr/adl-core/select/?q=genre_ssi%3Aplay+and+speaker_tesim%3Aadda+and%0D%0Atext_tesim%3A%22jeg+har+kun+ventet+paa+dig%22%0D%0A%09++++&wt=json&start=0&rows=10&defType=edismax&indent=on)

Searching verses inside collection of poetry: [genre_ssi:poetry AND text_tesim:"no whispering trees"](http://public-index.kb.dk/solr/adl-core/select/?q=genre_ssi%3Apoetry+AND%0D%0Atext_tesim%3Ano+whispering+trees&wt=json&start=0&rows=10&defType=edismax&indent=on)

[<<](03_prose.md) [>>](05_filtering_vs_searching.md)

