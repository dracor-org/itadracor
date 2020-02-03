# ItaDraCor
## Corpus Description
The **Ita**lian **Dra**ma **Cor**pus contains 139 original Italian plays, retrieved from [Biblioteca Italiana](http://www.bibliotecaitaliana.it/). They were already encoded in [TEI](https://tei-c.org/).

Actually, 171 texts are categorised as "Letteratura teatrale" in Biblioteca Italiana's catalogue, but 32 were not imported, because:

- they were not in Italian, but Latin (like ["Chrysis"](http://www.bibliotecaitaliana.it/testo/bibit000078), the comedy written by Pope Pius II)
- or they had no ```<speaker>``` tags
- or they were not plays in the narrower sense (like a smaller collection of Tasso's ["Dialoghi"](http://www.bibliotecaitaliana.it/testo/bibit000646))

The ```<availability>``` information given in each file reads: "Questa risorsa digitale è liberamente accessibile per uso personale o scientifico." ("This digital resource is freely accessible for personal or scientific use.")

ItaDraCor is maintained by Frank Fischer and Carsten Milling. – Thanks go to Fabio Ciotti, who provided us with helpful advice.

## Changelog
* 03.02.2020: Import of 139 plays. Filenames were adjusted (e.g., "bibit001163.xml" → "alfieri-oreste.xml").
