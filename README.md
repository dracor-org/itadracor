# ItaDraCor
## Corpus Description
The **Ita**lian **Dra**ma **Cor**pus contains 139 original Italian plays, retrieved from [Biblioteca Italiana](http://www.bibliotecaitaliana.it/). They were originally encoded in [TEI P4](https://www.tei-c.org/Vault/P4/) and updated by us to [TEI P5](https://tei-c.org/guidelines/p5/). We did some other minor adjustments so they can be connected to the DraCor portal, where they are now ready to be used by researchers (https://dracor.org/ita). Adjustments are documented in the changelog below.

Actually, 171 items are categorised as "Letteratura teatrale" in Biblioteca Italiana's catalogue, but 32 were not imported, because:

- they were not in Italian, but Latin (like ["Chrysis"](http://www.bibliotecaitaliana.it/testo/bibit000078), the comedy written by Pope Pius II)
- or they had no ```<speaker>``` tags
- or they were not plays in the narrower sense (like a smaller collection of Tasso's ["Dialoghi"](http://www.bibliotecaitaliana.it/testo/bibit000646))
- or they were not TEI-encoded files, but scans (like [this edition of plays by Grazzini](http://www.bibliotecaitaliana.it/testo/si140))

The ```<availability>``` information given in each file reads: "Questa risorsa digitale è liberamente accessibile per uso personale o scientifico." ("This digital resource is freely accessible for personal or scientific use.")

ItaDraCor is maintained by [Frank Fischer](https://lehkost.github.io/) and Carsten Milling. – Thanks go to Fabio Ciotti for helpful advice.

## Changelog
### 03.02.2020
* Import of 139 plays.
* Adjust filenames (e.g., "bibit001163" → "alfieri-oreste.xml").
* Add Wikidata IDs for plays.

### 08.02.2020
* Convert TEI P4 to P5.
* Add ```xml:lang="ita"``` to root element.
* Add DraCor ID to ```publicationStmt```.
* Add ```bibl[@type="digitalSource"]``` with link to original source.
* Many minor markup fixes, see commit history for details.

### 16.02.2020
* Identify speakers and reference them in ```who``` attribute.
* Add ```particDesc``` with list of all speakers per play.

### 20.02.2020
* Add Wikidata IDs for authors where applicable.

### 24.–27.02.2020
* Fix some speaker IDs and dissolve ```#tutti```/```#tutte```.
