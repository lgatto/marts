# Listing of mart instances


```r
library("biomaRt")
```

### [Pancreatic Expression Database](http://www.pancreasexpression.org/biomart/martview/1825ad73c61a3b177bda7e4f52b28d94)

- [Barts Cancer Institute, UK](http://www.bci.qmul.ac.uk/): [Results from published pancreatic cancer papers](http://www.pancreasexpression.org/)


```r
host <- "pancreasexpression.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##            biomart                        version
## 1       Pancreas63 Pancreatic Expression Database
## 2         REACTOME             REACTOME (CSHL US)
## 3       CosmicMart             COSMIC (SANGER UK)
## 4          unimart               UNIPROT (EBI UK)
## 5 prod-intermart_1                       InterPro
## 6            pride                          PRIDE
```


### [Breast Cancer Campaign, UK and Ireland](http://www.breastcancercampaign.org/page.aspx?pid=383)
- [BCCTB Bioinformatics Portal](http://bioinformatics.breastcancertissuebank.org/biomart/martview/19e7e70c4304a66f8324d5396a2b3f09) - [Breast cancer tissue information](http://www.breastcancertissuebank.org/about-tissue-bank.php)


```r
host <- "bioinformatics.breastcancertissuebank.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##            biomart                       version
## 1   Breast_mart_69 Breast Cancer Now Tissue Bank
## 2        Ensembl69              Ensembl 69 Genes
## 3 prod-intermart_1                      InterPro
## 4            pride                         PRIDE
```

### [Center for Mathematical Modeling and Center for Genome Regulation (CMM), Chile](http://www.cmm.uchile.cl/index.php?option=detalle&CodigoNoticia=1604&lang=en)
- [SalmonDB](http://salmonmart.cmm.uchile.cl/biomart/martview) - [Genomic information for Atlantic salmon, rainbow trout, and related species](http://genomicasalmones.dim.uchile.cl)


```r
host <- "salmonmart.cmm.uchile.cl"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##           biomart                          version
## 1 salmosalar_mart         Salmo salar Unigene mart
## 2     trucha_mart Oncorhynchus mykiss Unigene mart
```


### [Centre National de la Recherche Scientifique (CNRS), France](http://www.cnrs.fr/)
- [Cildb](http://cildb.cgm.cnrs-gif.fr/v2/biomart/martview/71e0e9c5ea5f77b7dda54c6d00cc26a2) - [Database for eukaryotic cilia and centriolar structures, integrating orthology relationships for 33 species with high throughput studies and OMIM](http://cildb.cgm.cnrs-gif.fr/)


```r
host <- "cildb.cgm.cnrs-gif.fr"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## [1] biomart version
## <0 rows> (or 0-length row.names)
```

- [Paramecium DB](http://paramecium.cgm.cnrs-gif.fr/biomart/martview/3cfa14c55fe847423b606917fe7010a3) - [Paramecium genome database](http://paramecium.cgm.cnrs-gif.fr/)


```r
host <- "paramecium.cgm.cnrs-gif.fr"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##     biomart           version
## 1 biomartDB Paramecium Genome
## 2  biblioDB      Bibliography
```

### [Cold Spring Harbor Laboratory (CSHL), US](http://www.cshl.edu/)

- [Gramene](http://www.gramene.org/Multi/martview) - [Agriculturally important grass genomes](http://www.gramene.org)


```r
host <- "www.gramene.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##                  biomart                 version
## 1     ENSEMBL_MART_PLANT          Plant Genes 49
## 2 ENSEMBL_MART_PLANT_SNP Plant Variation Mart 49
```


- [WormBase](http://caprica.caltech.edu:9002/biomart/martview) = [C. elegans and related nematode genomic information](http://www.wormbase.org/)


```r
host <- "www.caprica.caltech.edu"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Request to BioMart web service failed. Verify if you are still connected to the internet.  Alternatively the BioMart web service is temporarily down.  Check http://www.biomart.org and verify if this website is available.
```

```
## Error: XML content does not seem to be XML:
```

### [Department of Genetics, University of Cambridge, Cambridge, UK](http://www.gen.cam.ac.uk/)

- [DAPPER](http://dapper.gen.cam.ac.uk/) - [Mass spec identified protein interaction networks in Drosophilacell cycle regulation](http://dapper.gen.cam.ac.uk/biomart/martview)


```r
host <- "dapper.gen.cam.ac.uk"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##        biomart                        version
## 1   cg_mart_02    PROTEOMICS (CAMBRIDGE - UK)
## 2 ensembl_mart ENSEMBL GENES 75 (SANGER - UK)
```

### [European Bioinformatics Institute (EBI), UK](http://www.ebi.ac.uk/)

- [Ensembl Genomes](http://fungi.ensembl.org/biomart/martview) - [Genome databases for fungi, metazoa, plants and protists](http://ensemblgenomes.org)


```r
host <- "fungi.ensembl.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##             biomart               version
## 1       fungal_mart           Fungal Mart
## 2 fungal_variations Fungal Variation Mart
```

- [HGNC](http://www.genenames.org/biomart/martview) - [Repository of human gene nomenclature and associated resources](http://www.genenames.org/)


```r
host <- "www.genenames.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Opening and ending tag mismatch: input line 58 and form
## Opening and ending tag mismatch: form line 44 and div
## Opening and ending tag mismatch: div line 33 and body
## Opening and ending tag mismatch: body line 31 and html
## Premature end of data in tag html line 2
```

```
## Error: 1: Opening and ending tag mismatch: input line 58 and form
## 2: Opening and ending tag mismatch: form line 44 and div
## 3: Opening and ending tag mismatch: div line 33 and body
## 4: Opening and ending tag mismatch: body line 31 and html
## 5: Premature end of data in tag html line 2
```

- [InterPro](http://www.ebi.ac.uk/interpro/biomart/martview) - [Integrated database of predictive protein "signatures" used for the classification and automatic annotation of proteins and genomes](http://www.ebi.ac.uk/interpro/)


```r
host <- "www.ebi.ac.uk"
path <- "/interpro/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## StartTag: invalid element name
## Extra content at the end of the document
```

```
## Error: 1: StartTag: invalid element name
## 2: Extra content at the end of the document
```

- [PRIDE](http://www.ebi.ac.uk/pride/prideMart.do) - [Repository for protein and peptide identifications](http://www.ebi.ac.uk/pride/)


```r
host <- "www.ebi.ac.uk"
path <- "/pride/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Error: XML content does not seem to be XML: '{"status":"NOT_FOUND","code":404,"message":"Please use the PRIDE Archive web service or contact the PRIDE support team.","developerMessage":"http://www.ebi.ac.uk/pride/ws/archive","moreInfoUrl":"The Biomart service has been discontinued","throwable":null}'
```

- [UniProt](http://www.ebi.ac.uk/uniprot/biomart/martview) - [Protein sequence and functional information](http://www.ebi.ac.uk/uniprot/)



```r
host <- "www.ebi.ac.ul"
path <- "/uniprot/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Request to BioMart web service failed. Verify if you are still connected to the internet.  Alternatively the BioMart web service is temporarily down.  Check http://www.biomart.org and verify if this website is available.
```

```
## Error: XML content does not seem to be XML:
```

- [WormBase ParaSite](http://parasite.wormbase.org/biomart/martview) - [Parasitic worms (helminths) are responsible for more than a billion human infections globally and have a devastating impact on livestock and agriculture](http://parasite.wormbase.org/index.html)



```r
host <- "parasite.wormbase.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##         biomart       version
## 1 parasite_mart ParaSite Mart
```

### [Harwell Science and Innovation Campus (MRC Harwell), UK](http://www.har.mrc.ac.uk/index.html)

- [EuroPhenome](http://www.europhenome.org/biomart.php) - [Mouse phenotyping data](http://www.europhenome.org/)



```r
host <- "www.europhenome.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Space required after the Public Identifier
## SystemLiteral " or ' expected
## SYSTEM or PUBLIC, the URI is missing
## Opening and ending tag mismatch: hr line 9 and body
## Opening and ending tag mismatch: body line 4 and html
## Premature end of data in tag html line 2
```

```
## Error: 1: Space required after the Public Identifier
## 2: SystemLiteral " or ' expected
## 3: SYSTEM or PUBLIC, the URI is missing
## 4: Opening and ending tag mismatch: hr line 9 and body
## 5: Opening and ending tag mismatch: body line 4 and html
## 6: Premature end of data in tag html line 2
```

### [Information Center for Bio-pharmacological Network (i-Pharm), South Korea](http://www.i-pharm.org/)

- [i-Pharm](http://biomart.i-pharm.org/) - [Pharmacological network database consisting of three kinds of nodes: human diseases, drugs, and proteins](http://www.i-pharm.org/")


```r
host <- "biomart.i-pharm.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## [1] biomart version
## <0 rows> (or 0-length row.names)
```

### [Institut national de la santé et de la recherche médicale (Inserm), France](http://www.inserm.fr/)

- [GermOnline](http://www.germonline.org/biomart/martview) - [Cross-species microarray expression database focusing on germline development, meiosis, and gametogenesis as well as the mitotic cell cycle](http://www.germonline.org/)



```r
host <- "www.germonline.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##      biomart    version
## 1 GermOnline GermOnline
```

### [Institut Nationale de Recherche Agronomique (INRA), Unité de Recherche en Génomique-Info (URGI), France](http://urgi.versailles.inra.fr)

- [GnpIS](http://urgi.versailles.inra.fr/biomart/martview/)	- [Genetic and Genomic Information System (GnpIS)](http://urgi.versailles.inra.fr/gnpis/)


```r
host <- "urgi.versailles.inra.fr"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##               biomart
## 1  Public_OBIOMARTPUB
## 2        Public_VITIS
## 3    Public_VITIS_12x
## 4          Prod_WHEAT
## 5      Public_TAIRV10
## 6        Public_MAIZE
## 7         Prod_TOMATO
## 8         Prod_POPLAR
## 9      Prod_POPLAR_V2
## 10  Prod_BOTRYTISEDIT
## 11         Prod_BOFUB
## 12    Prod_SCLEROEDIT
## 13 Prod_LMACULANSEDIT
##                                                                                            version
## 1  Multi-species: marker, QTL, SNP, gene, germplasm, phenotype, association, with Gene annotations
## 2                         Grapevine 8x, stuctural annotation with Genetic maps (genetic markers..)
## 3       Grapevine 12x.0, stuctural and functional annotation with Genetic maps (genetic markers..)
## 4                                Wheat, stuctural annotation with Genetic maps (genetic markers..)
## 5                                        Arabidopsis Thaliana TAIRV10, genes functional annotation
## 6                                                      Zea mays ZmB73, genes functional annotation
## 7                                                      Tomato, stuctural and functional annotation
## 8                                                 Populus trichocarpa, genes functional annotation
## 9                                            Populus trichocarpa, genes functional annotation V2.0
## 10                                               Botrytis cinerea T4, genes functional annotation 
## 11                                            Botrytis cinerea B0510, genes functional annotation 
## 12                                          Sclerotinia sclerotiorum, genes functional annotation 
## 13                                             Leptosphaeria maculans, genes functional annotation
```

- [UniProt](http://www.ebi.ac.uk/uniprot/biomart/martview) - [Protein sequence and functional information](http://www.ebi.ac.uk/uniprot/)



```r
host <- "www.ebi.ac.uk"
path <- "/uniprot/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## StartTag: invalid element name
## Extra content at the end of the document
```

```
## Error: 1: StartTag: invalid element name
## 2: Extra content at the end of the document
```

### [International Potato Center (CIP), Peru](http://www.cipotato.org)

- [Potato database](http://germplasmdb.cip.cgiar.org/) - [Potato and sweetpotato phenotypic and genomic information](http://www.cipotato.org/)


```r
host <- "germplasmdb.cip.cgiar.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Space required after the Public Identifier
## SystemLiteral " or ' expected
## SYSTEM or PUBLIC, the URI is missing
## Opening and ending tag mismatch: hr line 7 and body
## Opening and ending tag mismatch: body line 4 and html
## Premature end of data in tag html line 2
```

```
## Error: 1: Space required after the Public Identifier
## 2: SystemLiteral " or ' expected
## 3: SYSTEM or PUBLIC, the URI is missing
## 4: Opening and ending tag mismatch: hr line 7 and body
## 5: Opening and ending tag mismatch: body line 4 and html
## 6: Premature end of data in tag html line 2
```

### [Jackson Laboratory, US](http://www.jax.org/)

- [MGI](http://biomart.informatics.jax.org/biomart/martview) - [Mouse genome features, locations, alleles, and orthologs](http://informatics.jax.org/)


```r
host <- "biomart.informatics.jax.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Opening and ending tag mismatch: meta line 30 and head
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag img line 34
## Specification mandate value for attribute nowrap
## attributes construct error
## Couldn't find end of Start Tag td line 46
## Entity 'nbsp' not defined
## Entity 'nbsp' not defined
## Opening and ending tag mismatch: tr line 44 and td
## Entity 'nbsp' not defined
## Opening and ending tag mismatch: table line 43 and tr
## Opening and ending tag mismatch: td line 40 and table
## Opening and ending tag mismatch: tr line 39 and td
## Opening and ending tag mismatch: table line 38 and body
## Opening and ending tag mismatch: td line 37 and html
## Premature end of data in tag tr line 36
## Premature end of data in tag table line 35
## Premature end of data in tag div line 35
## Premature end of data in tag body line 33
## Premature end of data in tag link line 10
## Premature end of data in tag meta line 8
## Premature end of data in tag head line 2
## Premature end of data in tag html line 1
```

```
## Error: 1: Opening and ending tag mismatch: meta line 30 and head
## 2: AttValue: " or ' expected
## 3: attributes construct error
## 4: Couldn't find end of Start Tag img line 34
## 5: Specification mandate value for attribute nowrap
## 6: attributes construct error
## 7: Couldn't find end of Start Tag td line 46
## 8: Entity 'nbsp' not defined
## 9: Entity 'nbsp' not defined
## 10: Opening and ending tag mismatch: tr line 44 and td
## 11: Entity 'nbsp' not defined
## 12: Opening and ending tag mismatch: table line 43 and tr
## 13: Opening and ending tag mismatch: td line 40 and table
## 14: Opening and ending tag mismatch: tr line 39 and td
## 15: Opening and ending tag mismatch: table line 38 and body
## 16: Opening and ending tag mismatch: td line 37 and html
## 17: Premature end of data in tag tr line 36
## 18: Premature end of data in tag table line 35
## 19: Premature end of data in tag div line 35
## 20: Premature end of data in tag body line 33
## 21: Premature end of data in tag link line 10
## 22: Premature end of data in tag meta line 8
## 23: Premature end of data in tag head line 2
## 24: Premature end of data in tag html line 1
```

### [Joint Genome Institute (JGI)/Center for Integrative Genomics (CIG), US](http://www.jgi.doe.gov/)

- [Phytozome](http://www.phytozome.net/biomart/martview) - [Comparative genomics of green plants](http://www.phytozome.net/)


```r
host <- "www.phytozome.net"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Entity 'nbsp' not defined
## Entity 'nbsp' not defined
## Entity 'copy' not defined
## Opening and ending tag mismatch: li line 445 and ul
## Opening and ending tag mismatch: li line 443 and div
## Entity 'nbsp' not defined
## Opening and ending tag mismatch: li line 439 and div
## Opening and ending tag mismatch: ul line 438 and div
## Opening and ending tag mismatch: div line 437 and body
## Opening and ending tag mismatch: div line 436 and html
## Premature end of data in tag body line 14
## Premature end of data in tag html line 1
```

```
## Error: 1: Entity 'nbsp' not defined
## 2: Entity 'nbsp' not defined
## 3: Entity 'copy' not defined
## 4: Opening and ending tag mismatch: li line 445 and ul
## 5: Opening and ending tag mismatch: li line 443 and div
## 6: Entity 'nbsp' not defined
## 7: Opening and ending tag mismatch: li line 439 and div
## 8: Opening and ending tag mismatch: ul line 438 and div
## 9: Opening and ending tag mismatch: div line 437 and body
## 10: Opening and ending tag mismatch: div line 436 and html
## 11: Premature end of data in tag body line 14
## 12: Premature end of data in tag html line 1
```

### [Kazusa DNA Research Institute (Kazusa), Japan](http://www.kazusa.or.jp/e/)

- [KazusaMart](http://mart.kazusa.or.jp/biomart/martview) - [Cyanobase, rhizobia, and plant genome databases](http://mart.kazusa.or.jp/)


```r
host <- "mart.kazusa.or.jp"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Space required after the Public Identifier
## SystemLiteral " or ' expected
## SYSTEM or PUBLIC, the URI is missing
```

```
## Error: 1: Space required after the Public Identifier
## 2: SystemLiteral " or ' expected
## 3: SYSTEM or PUBLIC, the URI is missing
```

### [Medical Research Council, Human Genetics Unit (MRC HGU), UK](http://www.hgu.mrc.ac.uk/)

- [EMAGE](http://biomart.emouseatlas.org/) - [Anatomy ontology and in situ gene expression data in the mouse ontology](http://www.emouseatlas.org/emage/home.php)


```r
host <- "biomart.emouseatlas.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## StartTag: invalid element name
## Extra content at the end of the document
```

```
## Error: 1: StartTag: invalid element name
## 2: Extra content at the end of the document
```

- [Eurexpress](http://www.eurexpress.org/ee/databases/biomart.jsp) - [Transcriptome atlas database for mouse embryo](http://www.eurexpress.org/)


```r
host <- "www.eurexpress.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Space required after the Public Identifier
## SystemLiteral " or ' expected
## SYSTEM or PUBLIC, the URI is missing
```

```
## Error: 1: Space required after the Public Identifier
## 2: SystemLiteral " or ' expected
## 3: SYSTEM or PUBLIC, the URI is missing
```

### [National Center for Biotechnology Information (NCBI), US](http://www.ncbi.nlm.nih.gov/)

- [HapMap](http://hapmart.hapmap.org/BioMart/martview) - [Multi-country effort to identify and catalog genetic similarities and differences in human beings](http://hapmap.org/)


```r
host <- "www.hapmap.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##        biomart      version
## 1 HapMap_rel27 HapMap_rel27
```

### [Peking University, China](http://english.pku.edu.cn/)

- [Rice-Map](href="http://ricemart.cbi.edu.cn/biomart/martview) - [Rice (japonica and indica) genome annotation database](ttp://www.ricemap.org/)



```r
host <- "ricemart.cbi.edu.cn"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Request to BioMart web service failed. Verify if you are still connected to the internet.  Alternatively the BioMart web service is temporarily down.  Check http://www.biomart.org and verify if this website is available.
```

```
## Error: XML content does not seem to be XML:
```

- [RhesusBase](http://www.rhesusbase.org:9000) - [A knowledgebase for the monkey research community](http://www.rhesusbase.org)



```r
host <- "www.rhesusbase.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Opening and ending tag mismatch: HR line 1 and body
## Opening and ending tag mismatch: HR line 1 and html
## Premature end of data in tag body line 1
## Premature end of data in tag html line 1
```

```
## Error: 1: Opening and ending tag mismatch: HR line 1 and body
## 2: Opening and ending tag mismatch: HR line 1 and html
## 3: Premature end of data in tag body line 1
## 4: Premature end of data in tag html line 1
```

### [RIKEN Center for Life Science Technologies (CLST), Japan](http://www.riken.jp/en/research/labs/clst/)

- [FANTOM5](http://fantom.gsc.riken.jp) - [The FANTOM5 project mapped a promoter level expression atlas in human and mouse. The FANTOM5 BioMart instance provides the set of promoters along with annotation](http://fantom.gsc.riken.jp/5/biomart/martview/)



```r
host <- "fantom.gsc.riken.jp"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Opening and ending tag mismatch: meta line 20 and head
## Opening and ending tag mismatch: div line 96 and a
## Opening and ending tag mismatch: p line 117 and div
## Entity 'copy' not defined
## Opening and ending tag mismatch: meta line 15 and html
## Premature end of data in tag head line 9
## Premature end of data in tag html line 7
```

```
## Error: 1: Opening and ending tag mismatch: meta line 20 and head
## 2: Opening and ending tag mismatch: div line 96 and a
## 3: Opening and ending tag mismatch: p line 117 and div
## 4: Entity 'copy' not defined
## 5: Opening and ending tag mismatch: meta line 15 and html
## 6: Premature end of data in tag head line 9
## 7: Premature end of data in tag html line 7
```

### [University of Leicester, UK](http://www2.le.ac.uk/departments/genetics/research/bioinformatics)

- [GWAS Central](https://www.gwascentral.org/biomart/martview/) - [GWAS Central provides a centralized compilation of summary level findings from genetic association studies, both large and small](http://www.gwascentral.org/info/about/)


```r
host <- "www.gwascentral.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Entity 'nbsp' not defined
## Entity 'nbsp' not defined
## Entity 'nbsp' not defined
## Entity 'nbsp' not defined
## Entity 'nbsp' not defined
## Entity 'nbsp' not defined
## Entity 'nbsp' not defined
## EntityRef: expecting ';'
## Opening and ending tag mismatch: a line 207 and div
## Opening and ending tag mismatch: div line 207 and a
## Opening and ending tag mismatch: a line 212 and div
## Opening and ending tag mismatch: div line 212 and a
## Opening and ending tag mismatch: a line 217 and div
## Opening and ending tag mismatch: div line 217 and a
## Opening and ending tag mismatch: a line 222 and div
## Opening and ending tag mismatch: div line 222 and a
## Opening and ending tag mismatch: a line 227 and div
## Opening and ending tag mismatch: div line 227 and a
## Opening and ending tag mismatch: a line 232 and div
## Opening and ending tag mismatch: div line 232 and a
## Opening and ending tag mismatch: body line 125 and div
## Opening and ending tag mismatch: html line 3 and div
## Extra content at the end of the document
```

```
## Error: 1: Entity 'nbsp' not defined
## 2: Entity 'nbsp' not defined
## 3: Entity 'nbsp' not defined
## 4: Entity 'nbsp' not defined
## 5: Entity 'nbsp' not defined
## 6: Entity 'nbsp' not defined
## 7: Entity 'nbsp' not defined
## 8: EntityRef: expecting ';'
## 9: Opening and ending tag mismatch: a line 207 and div
## 10: Opening and ending tag mismatch: div line 207 and a
## 11: Opening and ending tag mismatch: a line 212 and div
## 12: Opening and ending tag mismatch: div line 212 and a
## 13: Opening and ending tag mismatch: a line 217 and div
## 14: Opening and ending tag mismatch: div line 217 and a
## 15: Opening and ending tag mismatch: a line 222 and div
## 16: Opening and ending tag mismatch: div line 222 and a
## 17: Opening and ending tag mismatch: a line 227 and div
## 18: Opening and ending tag mismatch: div line 227 and a
## 19: Opening and ending tag mismatch: a line 232 and div
## 20: Opening and ending tag mismatch: div line 232 and a
## 21: Opening and ending tag mismatch: body line 125 and div
## 22: Opening and ending tag mismatch: html line 3 and div
## 23: Extra content at the end of the document
```

### [INRA - French National Institute of Agricultural Research, France](http://www.inra.fr/)

- [sigReannot](http://sigreannot-mart.toulouse.inra.fr/) - [Aquaculture and farm animal species microarray probes re-annotation](http://www.sigenae.org/)


```r
host <- "sigreannot-mart.toulouse.inra.fr"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##                                 biomart
## 1   Sigenae_Oligo_Annotation_Ensembl_63
## 2   Sigenae_Oligo_Annotation_Ensembl_61
## 3 Sigenae Oligo Annotation (Ensembl 59)
## 4 Sigenae Oligo Annotation (Ensembl 56)
##                                 version
## 1 Sigenae Oligo Annotation (Ensembl 63)
## 2 Sigenae Oligo Annotation (Ensembl 61)
## 3 Sigenae Oligo Annotation (Ensembl 59)
## 4 Sigenae Oligo Annotation (Ensembl 56)
```

- [GnpIS](https://urgi.versailles.inra.fr/biomart/martview/) - [Genetic and Genomic Information System (GnpIS)](https://urgi.versailles.inra.fr/gnpis/)


```r
host <- "urgi.versailles.inra.fr"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##               biomart
## 1  Public_OBIOMARTPUB
## 2        Public_VITIS
## 3    Public_VITIS_12x
## 4          Prod_WHEAT
## 5      Public_TAIRV10
## 6        Public_MAIZE
## 7         Prod_TOMATO
## 8         Prod_POPLAR
## 9      Prod_POPLAR_V2
## 10  Prod_BOTRYTISEDIT
## 11         Prod_BOFUB
## 12    Prod_SCLEROEDIT
## 13 Prod_LMACULANSEDIT
##                                                                                            version
## 1  Multi-species: marker, QTL, SNP, gene, germplasm, phenotype, association, with Gene annotations
## 2                         Grapevine 8x, stuctural annotation with Genetic maps (genetic markers..)
## 3       Grapevine 12x.0, stuctural and functional annotation with Genetic maps (genetic markers..)
## 4                                Wheat, stuctural annotation with Genetic maps (genetic markers..)
## 5                                        Arabidopsis Thaliana TAIRV10, genes functional annotation
## 6                                                      Zea mays ZmB73, genes functional annotation
## 7                                                      Tomato, stuctural and functional annotation
## 8                                                 Populus trichocarpa, genes functional annotation
## 9                                            Populus trichocarpa, genes functional annotation V2.0
## 10                                               Botrytis cinerea T4, genes functional annotation 
## 11                                            Botrytis cinerea B0510, genes functional annotation 
## 12                                          Sclerotinia sclerotiorum, genes functional annotation 
## 13                                             Leptosphaeria maculans, genes functional annotation
```


### [Iowa State University, US](http://www.iastate.edu/)

- [Animal Genome database](http://www.animalgenome.org:8181/) - [Agriculturally important livestock genomes](http://www.animalgenome.org/)


```r
host <- "animalgenome.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Opening and ending tag mismatch: META line 6 and head
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag BODY line 15
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TABLE line 17
## Opening and ending tag mismatch: BR line 18 and TD
## Opening and ending tag mismatch: TD line 18 and TR
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag img line 21
## EntityRef: expecting ';'
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TABLE line 33
## Opening and ending tag mismatch: BR line 35 and TD
## Opening and ending tag mismatch: TD line 34 and TR
## Opening and ending tag mismatch: TR line 34 and TABLE
## Opening and ending tag mismatch: P line 32 and div
## Opening and ending tag mismatch: P line 28 and TD
## Opening and ending tag mismatch: P line 25 and TR
## Specification mandate value for attribute NOSHADE
## Opening and ending tag mismatch: META line 46 and head
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag BODY line 57
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TABLE line 60
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TD line 65
## Entity 'nbsp' not defined
## Opening and ending tag mismatch: TR line 64 and TD
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TD line 66
## Opening and ending tag mismatch: META line 45 and TD
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TD line 67
## Entity 'nbsp' not defined
## Opening and ending tag mismatch: head line 44 and TD
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TD line 68
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag table line 69
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag td line 70
## Opening and ending tag mismatch: tr line 70 and td
## Opening and ending tag mismatch: html line 43 and tr
## Opening and ending tag mismatch: HR line 42 and table
## Opening and ending tag mismatch: LI line 82 and UL
## Opening and ending tag mismatch: LI line 89 and UL
## Opening and ending tag mismatch: LI line 106 and UL
## Opening and ending tag mismatch: LI line 118 and UL
## Opening and ending tag mismatch: LI line 126 and UL
## Opening and ending tag mismatch: LI line 125 and UL
## Opening and ending tag mismatch: LI line 136 and UL
## Opening and ending tag mismatch: LI line 141 and UL
## Opening and ending tag mismatch: LI line 150 and UL
## Opening and ending tag mismatch: LI line 159 and UL
## Opening and ending tag mismatch: LI line 158 and UL
## Opening and ending tag mismatch: LI line 173 and UL
## StartTag: invalid element name
## Opening and ending tag mismatch: LI line 178 and a
## Opening and ending tag mismatch: LI line 177 and UL
## Opening and ending tag mismatch: LI line 181 and UL
## Opening and ending tag mismatch: LI line 188 and UL
## Opening and ending tag mismatch: LI line 192 and UL
## Opening and ending tag mismatch: LI line 199 and UL
## Opening and ending tag mismatch: LI line 201 and UL
## Opening and ending tag mismatch: LI line 208 and UL
## Opening and ending tag mismatch: LI line 217 and UL
## Opening and ending tag mismatch: LI line 222 and UL
## Opening and ending tag mismatch: LI line 228 and UL
## Opening and ending tag mismatch: LI line 233 and UL
## Opening and ending tag mismatch: LI line 240 and UL
## Opening and ending tag mismatch: LI line 239 and UL
## Opening and ending tag mismatch: LI line 252 and UL
## Opening and ending tag mismatch: LI line 251 and UL
## Opening and ending tag mismatch: LI line 270 and UL
## Opening and ending tag mismatch: LI line 269 and UL
## Opening and ending tag mismatch: LI line 268 and TD
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TD line 276
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag img line 280
## Opening and ending tag mismatch: BR line 279 and div
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag img line 285
## Opening and ending tag mismatch: BR line 284 and div
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag img line 290
## Opening and ending tag mismatch: BR line 289 and div
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag img line 295
## Opening and ending tag mismatch: BR line 294 and div
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag img line 300
## Opening and ending tag mismatch: BR line 299 and div
## Opening and ending tag mismatch: BR line 299 and TD
## Opening and ending tag mismatch: BR line 298 and TR
## Opening and ending tag mismatch: div line 297 and TABLE
## Opening and ending tag mismatch: BR line 294 and body
## Opening and ending tag mismatch: BR line 293 and html
## Opening and ending tag mismatch: div line 292 and TD
## Opening and ending tag mismatch: BR line 289 and TR
## Opening and ending tag mismatch: BR line 288 and TABLE
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TABLE line 312
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TD line 313
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag img line 314
## Opening and ending tag mismatch: a line 314 and A
## Opening and ending tag mismatch: TR line 313 and TD
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TD line 316
## CharRef: invalid decimal value
## xmlParseCharRef: invalid xmlChar value 0
## Opening and ending tag mismatch: BR line 318 and TD
## AttValue: " or ' expected
## attributes construct error
## Couldn't find end of Start Tag TD line 322
## Opening and ending tag mismatch: img line 324 and a
## Opening and ending tag mismatch: img line 324 and TD
## Opening and ending tag mismatch: a line 323 and TR
## Opening and ending tag mismatch: HR line 311 and TABLE
## Opening and ending tag mismatch: div line 287 and BODY
## Opening and ending tag mismatch: BR line 284 and HTML
## Premature end of data in tag BR line 283
## Premature end of data in tag div line 282
## Premature end of data in tag BR line 279
## Premature end of data in tag BR line 278
## Premature end of data in tag div line 277
## Premature end of data in tag LI line 267
## Premature end of data in tag LI line 266
## Premature end of data in tag LI line 265
## Premature end of data in tag LI line 264
## Premature end of data in tag LI line 263
## Premature end of data in tag LI line 262
## Premature end of data in tag LI line 261
## Premature end of data in tag LI line 260
## Premature end of data in tag LI line 259
## Premature end of data in tag LI line 258
## Premature end of data in tag UL line 257
## Premature end of data in tag LI line 256
## Premature end of data in tag UL line 255
## Premature end of data in tag LI line 250
## Premature end of data in tag LI line 249
## Premature end of data in tag LI line 248
## Premature end of data in tag LI line 247
## Premature end of data in tag UL line 246
## Premature end of data in tag LI line 245
## Premature end of data in tag P line 244
## Premature end of data in tag LI line 238
## Premature end of data in tag UL line 237
## Premature end of data in tag LI line 236
## Premature end of data in tag LI line 235
## Premature end of data in tag LI line 232
## Premature end of data in tag UL line 231
## Premature end of data in tag LI line 230
## Premature end of data in tag LI line 227
## Premature end of data in tag LI line 226
## Premature end of data in tag UL line 225
## Premature end of data in tag LI line 224
## Premature end of data in tag LI line 221
## Premature end of data in tag UL line 220
## Premature end of data in tag LI line 219
## Premature end of data in tag LI line 216
## Premature end of data in tag UL line 215
## Premature end of data in tag LI line 214
## Premature end of data in tag UL line 213
## Premature end of data in tag LI line 212
## Premature end of data in tag P line 211
## Premature end of data in tag LI line 207
## Premature end of data in tag UL line 206
## Premature end of data in tag LI line 205
## Premature end of data in tag P line 204
## Premature end of data in tag LI line 198
## Premature end of data in tag LI line 197
## Premature end of data in tag LI line 196
## Premature end of data in tag UL line 195
## Premature end of data in tag LI line 194
## Premature end of data in tag UL line 191
## Premature end of data in tag LI line 190
## Premature end of data in tag UL line 187
## Premature end of data in tag LI line 186
## Premature end of data in tag UL line 185
## Premature end of data in tag LI line 184
## Premature end of data in tag P line 183
## Premature end of data in tag LI line 180
## Premature end of data in tag UL line 176
## Premature end of data in tag LI line 175
## Premature end of data in tag LI line 172
## Premature end of data in tag LI line 171
## Premature end of data in tag LI line 170
## Premature end of data in tag UL line 169
## Premature end of data in tag LI line 168
## Premature end of data in tag LI line 167
## Premature end of data in tag LI line 166
## Premature end of data in tag LI line 165
## Premature end of data in tag UL line 164
## Premature end of data in tag LI line 163
## Premature end of data in tag P line 162
## Premature end of data in tag LI line 157
## Premature end of data in tag LI line 156
## Premature end of data in tag LI line 155
## Premature end of data in tag LI line 154
## Premature end of data in tag UL line 153
## Premature end of data in tag LI line 152
## Premature end of data in tag LI line 149
## Premature end of data in tag LI line 148
## Premature end of data in tag LI line 147
## Premature end of data in tag LI line 146
## Premature end of data in tag LI line 145
## Premature end of data in tag UL line 144
## Premature end of data in tag LI line 143
## Premature end of data in tag LI line 140
## Premature end of data in tag UL line 139
## Premature end of data in tag LI line 138
## Premature end of data in tag LI line 135
## Premature end of data in tag LI line 134
## Premature end of data in tag UL line 133
## Premature end of data in tag LI line 132
## Premature end of data in tag UL line 131
## Premature end of data in tag LI line 130
## Premature end of data in tag P line 129
## Premature end of data in tag LI line 124
## Premature end of data in tag LI line 123
## Premature end of data in tag LI line 122
## Premature end of data in tag UL line 121
## Premature end of data in tag LI line 120
## Premature end of data in tag LI line 117
## Premature end of data in tag LI line 116
## Premature end of data in tag LI line 115
## Premature end of data in tag LI line 114
## Premature end of data in tag LI line 113
## Premature end of data in tag LI line 112
## Premature end of data in tag LI line 111
## Premature end of data in tag UL line 110
## Premature end of data in tag LI line 109
## Premature end of data in tag LI line 108
## Premature end of data in tag LI line 105
## Premature end of data in tag LI line 104
## Premature end of data in tag LI line 103
## Premature end of data in tag LI line 102
## Premature end of data in tag LI line 101
## Premature end of data in tag LI line 100
## Premature end of data in tag LI line 99
## Premature end of data in tag LI line 98
## Premature end of data in tag UL line 97
## Premature end of data in tag LI line 96
## Premature end of data in tag LI line 91
## Premature end of data in tag LI line 88
## Premature end of data in tag LI line 87
## Premature end of data in tag LI line 86
## Premature end of data in tag UL line 85
## Premature end of data in tag LI line 84
## Premature end of data in tag LI line 81
## Premature end of data in tag LI line 80
## Premature end of data in tag UL line 79
## Premature end of data in tag LI line 78
## Premature end of data in tag UL line 77
## Premature end of data in tag LI line 76
## Premature end of data in tag UL line 75
## Premature end of data in tag TD line 41
## Premature end of data in tag TR line 41
## Premature end of data in tag div line 24
## Premature end of data in tag TD line 23
## Premature end of data in tag TR line 23
## Premature end of data in tag TR line 18
## Premature end of data in tag META line 5
## Premature end of data in tag META line 4
## Premature end of data in tag META line 3
## Premature end of data in tag head line 2
## Premature end of data in tag html line 1
```

```
## Error: 1: Opening and ending tag mismatch: META line 6 and head
## 2: AttValue: " or ' expected
## 3: attributes construct error
## 4: Couldn't find end of Start Tag BODY line 15
## 5: AttValue: " or ' expected
## 6: attributes construct error
## 7: Couldn't find end of Start Tag TABLE line 17
## 8: Opening and ending tag mismatch: BR line 18 and TD
## 9: Opening and ending tag mismatch: TD line 18 and TR
## 10: AttValue: " or ' expected
## 11: attributes construct error
## 12: Couldn't find end of Start Tag img line 21
## 13: EntityRef: expecting ';'
## 14: AttValue: " or ' expected
## 15: attributes construct error
## 16: Couldn't find end of Start Tag TABLE line 33
## 17: Opening and ending tag mismatch: BR line 35 and TD
## 18: Opening and ending tag mismatch: TD line 34 and TR
## 19: Opening and ending tag mismatch: TR line 34 and TABLE
## 20: Opening and ending tag mismatch: P line 32 and div
## 21: Opening and ending tag mismatch: P line 28 and TD
## 22: Opening and ending tag mismatch: P line 25 and TR
## 23: Specification mandate value for attribute NOSHADE
## 24: Opening and ending tag mismatch: META line 46 and head
## 25: AttValue: " or ' expected
## 26: attributes construct error
## 27: Couldn't find end of Start Tag BODY line 57
## 28: AttValue: " or ' expected
## 29: attributes construct error
## 30: Couldn't find end of Start Tag TABLE line 60
## 31: AttValue: " or ' expected
## 32: attributes construct error
## 33: Couldn't find end of Start Tag TD line 65
## 34: Entity 'nbsp' not defined
## 35: Opening and ending tag mismatch: TR line 64 and TD
## 36: AttValue: " or ' expected
## 37: attributes construct error
## 38: Couldn't find end of Start Tag TD line 66
## 39: Opening and ending tag mismatch: META line 45 and TD
## 40: AttValue: " or ' expected
## 41: attributes construct error
## 42: Couldn't find end of Start Tag TD line 67
## 43: Entity 'nbsp' not defined
## 44: Opening and ending tag mismatch: head line 44 and TD
## 45: AttValue: " or ' expected
## 46: attributes construct error
## 47: Couldn't find end of Start Tag TD line 68
## 48: AttValue: " or ' expected
## 49: attributes construct error
## 50: Couldn't find end of Start Tag table line 69
## 51: AttValue: " or ' expected
## 52: attributes construct error
## 53: Couldn't find end of Start Tag td line 70
## 54: Opening and ending tag mismatch: tr line 70 and td
## 55: Opening and ending tag mismatch: html line 43 and tr
## 56: Opening and ending tag mismatch: HR line 42 and table
## 57: Opening and ending tag mismatch: LI line 82 and UL
## 58: Opening and ending tag mismatch: LI line 89 and UL
## 59: Opening and ending tag mismatch: LI line 106 and UL
## 60: Opening and ending tag mismatch: LI line 118 and UL
## 61: Opening and ending tag mismatch: LI line 126 and UL
## 62: Opening and ending tag mismatch: LI line 125 and UL
## 63: Opening and ending tag mismatch: LI line 136 and UL
## 64: Opening and ending tag mismatch: LI line 141 and UL
## 65: Opening and ending tag mismatch: LI line 150 and UL
## 66: Opening and ending tag mismatch: LI line 159 and UL
## 67: Opening and ending tag mismatch: LI line 158 and UL
## 68: Opening and ending tag mismatch: LI line 173 and UL
## 69: StartTag: invalid element name
## 70: Opening and ending tag mismatch: LI line 178 and a
## 71: Opening and ending tag mismatch: LI line 177 and UL
## 72: Opening and ending tag mismatch: LI line 181 and UL
## 73: Opening and ending tag mismatch: LI line 188 and UL
## 74: Opening and ending tag mismatch: LI line 192 and UL
## 75: Opening and ending tag mismatch: LI line 199 and UL
## 76: Opening and ending tag mismatch: LI line 201 and UL
## 77: Opening and ending tag mismatch: LI line 208 and UL
## 78: Opening and ending tag mismatch: LI line 217 and UL
## 79: Opening and ending tag mismatch: LI line 222 and UL
## 80: Opening and ending tag mismatch: LI line 228 and UL
## 81: Opening and ending tag mismatch: LI line 233 and UL
## 82: Opening and ending tag mismatch: LI line 240 and UL
## 83: Opening and ending tag mismatch: LI line 239 and UL
## 84: Opening and ending tag mismatch: LI line 252 and UL
## 85: Opening and ending tag mismatch: LI line 251 and UL
## 86: Opening and ending tag mismatch: LI line 270 and UL
## 87: Opening and ending tag mismatch: LI line 269 and UL
## 88: Opening and ending tag mismatch: LI line 268 and TD
## 89: AttValue: " or ' expected
## 90: attributes construct error
## 91: Couldn't find end of Start Tag TD line 276
## 92: AttValue: " or ' expected
## 93: attributes construct error
## 94: Couldn't find end of Start Tag img line 280
## 95: Opening and ending tag mismatch: BR line 279 and div
## 96: AttValue: " or ' expected
## 97: attributes construct error
## 98: Couldn't find end of Start Tag img line 285
## 99: Opening and ending tag mismatch: BR line 284 and div
## 100: AttValue: " or ' expected
## 101: attributes construct error
## 102: Couldn't find end of Start Tag img line 290
## 103: Opening and ending tag mismatch: BR line 289 and div
## 104: AttValue: " or ' expected
## 105: attributes construct error
## 106: Couldn't find end of Start Tag img line 295
## 107: Opening and ending tag mismatch: BR line 294 and div
## 108: AttValue: " or ' expected
## 109: attributes construct error
## 110: Couldn't find end of Start Tag img line 300
## 111: Opening and ending tag mismatch: BR line 299 and div
## 112: Opening and ending tag mismatch: BR line 299 and TD
## 113: Opening and ending tag mismatch: BR line 298 and TR
## 114: Opening and ending tag mismatch: div line 297 and TABLE
## 115: Opening and ending tag mismatch: BR line 294 and body
## 116: Opening and ending tag mismatch: BR line 293 and html
## 117: Opening and ending tag mismatch: div line 292 and TD
## 118: Opening and ending tag mismatch: BR line 289 and TR
## 119: Opening and ending tag mismatch: BR line 288 and TABLE
## 120: AttValue: " or ' expected
## 121: attributes construct error
## 122: Couldn't find end of Start Tag TABLE line 312
## 123: AttValue: " or ' expected
## 124: attributes construct error
## 125: Couldn't find end of Start Tag TD line 313
## 126: AttValue: " or ' expected
## 127: attributes construct error
## 128: Couldn't find end of Start Tag img line 314
## 129: Opening and ending tag mismatch: a line 314 and A
## 130: Opening and ending tag mismatch: TR line 313 and TD
## 131: AttValue: " or ' expected
## 132: attributes construct error
## 133: Couldn't find end of Start Tag TD line 316
## 134: CharRef: invalid decimal value
## 135: xmlParseCharRef: invalid xmlChar value 0
## 136: Opening and ending tag mismatch: BR line 318 and TD
## 137: AttValue: " or ' expected
## 138: attributes construct error
## 139: Couldn't find end of Start Tag TD line 322
## 140: Opening and ending tag mismatch: img line 324 and a
## 141: Opening and ending tag mismatch: img line 324 and TD
## 142: Opening and ending tag mismatch: a line 323 and TR
## 143: Opening and ending tag mismatch: HR line 311 and TABLE
## 144: Opening and ending tag mismatch: div line 287 and BODY
## 145: Opening and ending tag mismatch: BR line 284 and HTML
## 146: Premature end of data in tag BR line 283
## 147: Premature end of data in tag div line 282
## 148: Premature end of data in tag BR line 279
## 149: Premature end of data in tag BR line 278
## 150: Premature end of data in tag div line 277
## 151: Premature end of data in tag LI line 267
## 152: Premature end of data in tag LI line 266
## 153: Premature end of data in tag LI line 265
## 154: Premature end of data in tag LI line 264
## 155: Premature end of data in tag LI line 263
## 156: Premature end of data in tag LI line 262
## 157: Premature end of data in tag LI line 261
## 158: Premature end of data in tag LI line 260
## 159: Premature end of data in tag LI line 259
## 160: Premature end of data in tag LI line 258
## 161: Premature end of data in tag UL line 257
## 162: Premature end of data in tag LI line 256
## 163: Premature end of data in tag UL line 255
## 164: Premature end of data in tag LI line 250
## 165: Premature end of data in tag LI line 249
## 166: Premature end of data in tag LI line 248
## 167: Premature end of data in tag LI line 247
## 168: Premature end of data in tag UL line 246
## 169: Premature end of data in tag LI line 245
## 170: Premature end of data in tag P line 244
## 171: Premature end of data in tag LI line 238
## 172: Premature end of data in tag UL line 237
## 173: Premature end of data in tag LI line 236
## 174: Premature end of data in tag LI line 235
## 175: Premature end of data in tag LI line 232
## 176: Premature end of data in tag UL line 231
## 177: Premature end of data in tag LI line 230
## 178: Premature end of data in tag LI line 227
## 179: Premature end of data in tag LI line 226
## 180: Premature end of data in tag UL line 225
## 181: Premature end of data in tag LI line 224
## 182: Premature end of data in tag LI line 221
## 183: Premature end of data in tag UL line 220
## 184: Premature end of data in tag LI line 219
## 185: Premature end of data in tag LI line 216
## 186: Premature end of data in tag UL line 215
## 187: Premature end of data in tag LI line 214
## 188: Premature end of data in tag UL line 213
## 189: Premature end of data in tag LI line 212
## 190: Premature end of data in tag P line 211
## 191: Premature end of data in tag LI line 207
## 192: Premature end of data in tag UL line 206
## 193: Premature end of data in tag LI line 205
## 194: Premature end of data in tag P line 204
## 195: Premature end of data in tag LI line 198
## 196: Premature end of data in tag LI line 197
## 197: Premature end of data in tag LI line 196
## 198: Premature end of data in tag UL line 195
## 199: Premature end of data in tag LI line 194
## 200: Premature end of data in tag UL line 191
## 201: Premature end of data in tag LI line 190
## 202: Premature end of data in tag UL line 187
## 203: Premature end of data in tag LI line 186
## 204: Premature end of data in tag UL line 185
## 205: Premature end of data in tag LI line 184
## 206: Premature end of data in tag P line 183
## 207: Premature end of data in tag LI line 180
## 208: Premature end of data in tag UL line 176
## 209: Premature end of data in tag LI line 175
## 210: Premature end of data in tag LI line 172
## 211: Premature end of data in tag LI line 171
## 212: Premature end of data in tag LI line 170
## 213: Premature end of data in tag UL line 169
## 214: Premature end of data in tag LI line 168
## 215: Premature end of data in tag LI line 167
## 216: Premature end of data in tag LI line 166
## 217: Premature end of data in tag LI line 165
## 218: Premature end of data in tag UL line 164
## 219: Premature end of data in tag LI line 163
## 220: Premature end of data in tag P line 162
## 221: Premature end of data in tag LI line 157
## 222: Premature end of data in tag LI line 156
## 223: Premature end of data in tag LI line 155
## 224: Premature end of data in tag LI line 154
## 225: Premature end of data in tag UL line 153
## 226: Premature end of data in tag LI line 152
## 227: Premature end of data in tag LI line 149
## 228: Premature end of data in tag LI line 148
## 229: Premature end of data in tag LI line 147
## 230: Premature end of data in tag LI line 146
## 231: Premature end of data in tag LI line 145
## 232: Premature end of data in tag UL line 144
## 233: Premature end of data in tag LI line 143
## 234: Premature end of data in tag LI line 140
## 235: Premature end of data in tag UL line 139
## 236: Premature end of data in tag LI line 138
## 237: Premature end of data in tag LI line 135
## 238: Premature end of data in tag LI line 134
## 239: Premature end of data in tag UL line 133
## 240: Premature end of data in tag LI line 132
## 241: Premature end of data in tag UL line 131
## 242: Premature end of data in tag LI line 130
## 243: Premature end of data in tag P line 129
## 244: Premature end of data in tag LI line 124
## 245: Premature end of data in tag LI line 123
## 246: Premature end of data in tag LI line 122
## 247: Premature end of data in tag UL line 121
## 248: Premature end of data in tag LI line 120
## 249: Premature end of data in tag LI line 117
## 250: Premature end of data in tag LI line 116
## 251: Premature end of data in tag LI line 115
## 252: Premature end of data in tag LI line 114
## 253: Premature end of data in tag LI line 113
## 254: Premature end of data in tag LI line 112
## 255: Premature end of data in tag LI line 111
## 256: Premature end of data in tag UL line 110
## 257: Premature end of data in tag LI line 109
## 258: Premature end of data in tag LI line 108
## 259: Premature end of data in tag LI line 105
## 260: Premature end of data in tag LI line 104
## 261: Premature end of data in tag LI line 103
## 262: Premature end of data in tag LI line 102
## 263: Premature end of data in tag LI line 101
## 264: Premature end of data in tag LI line 100
## 265: Premature end of data in tag LI line 99
## 266: Premature end of data in tag LI line 98
## 267: Premature end of data in tag UL line 97
## 268: Premature end of data in tag LI line 96
## 269: Premature end of data in tag LI line 91
## 270: Premature end of data in tag LI line 88
## 271: Premature end of data in tag LI line 87
## 272: Premature end of data in tag LI line 86
## 273: Premature end of data in tag UL line 85
## 274: Premature end of data in tag LI line 84
## 275: Premature end of data in tag LI line 81
## 276: Premature end of data in tag LI line 80
## 277: Premature end of data in tag UL line 79
## 278: Premature end of data in tag LI line 78
## 279: Premature end of data in tag UL line 77
## 280: Premature end of data in tag LI line 76
## 281: Premature end of data in tag UL line 75
## 282: Premature end of data in tag TD line 41
## 283: Premature end of data in tag TR line 41
## 284: Premature end of data in tag div line 24
## 285: Premature end of data in tag TD line 23
## 286: Premature end of data in tag TR line 23
## 287: Premature end of data in tag TR line 18
## 288: Premature end of data in tag META line 5
## 289: Premature end of data in tag META line 4
## 290: Premature end of data in tag META line 3
## 291: Premature end of data in tag head line 2
## 292: Premature end of data in tag html line 1
```

###  [University of Notre Dame, US](http://nd.edu/)

- [VectorBase](http://biomart.vectorbase.org/biomart/martview) - [Genome information for invertebrate vectors of human pathogens](http://vectorbase.org/)


```r
host <- "biomart.vectorbase.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##             biomart               version
## 1 vb_gene_mart_1512      VectorBase Genes
## 2  vb_snp_mart_1512  VectorBase Variation
## 3        expression VectorBase Expression
```

### [Universitat Pompeu Fabra (UPF), Spain](http://www.upf.edu/en/)

- [Regulatory Genomics Group](http://archimedes.imim.es:9009/biomart/martview/36e00ae657f7efc9f276fcddf155c8ce) - [Predictive Models of Gene Regulation from High-Throughput Epigenomics Data](http://regulatorygenomics.upf.edu/group/)


```r
host <- "archimedes.imim.es0"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Request to BioMart web service failed. Verify if you are still connected to the internet.  Alternatively the BioMart web service is temporarily down.  Check http://www.biomart.org and verify if this website is available.
```

```
## Error: XML content does not seem to be XML:
```


### [University of Trento, Italy](http://www.unitn.it/en)

- [http://aura.science.unitn.it/biomart/martview/](http://aura.science.unitn.it/biomart/martview/) - [Atlas of UTR Regulatory Activity (AURA)](http://www.unitn.it/en)


```r
host <- "aura.science.unitn.it"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## [1] biomart version
## <0 rows> (or 0-length row.names)
```

### [Wellcome Trust Sanger Institute (WTSI), UK](http://www.sanger.ac.uk/)

- [COSMIC](http://www.sanger.ac.uk/genetics/CGP/cosmic/biomart/martview) - [Somatic mutation information relating to human cancers](http://www.sanger.ac.uk/genetics/CGP/cosmic/)


```r
host <- "www.sanger.ac.uk"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## Opening and ending tag mismatch: p line 30 and div
## Opening and ending tag mismatch: p line 42 and div
## Opening and ending tag mismatch: div line 39 and script
## Opening and ending tag mismatch: div line 27 and head
## Specification mandate value for attribute data-offcanvas
## attributes construct error
## Couldn't find end of Start Tag div line 60
## Opening and ending tag mismatch: section line 66 and p
## Opening and ending tag mismatch: div line 71 and p
## Opening and ending tag mismatch: p line 74 and div
## Opening and ending tag mismatch: p line 76 and div
## Opening and ending tag mismatch: div line 70 and section
## Opening and ending tag mismatch: input line 90 and div
## Opening and ending tag mismatch: div line 88 and form
## Opening and ending tag mismatch: form line 87 and div
## Opening and ending tag mismatch: div line 84 and header
## Opening and ending tag mismatch: header line 83 and div
## Opening and ending tag mismatch: script line 27 and html
## Premature end of data in tag script line 24
## Premature end of data in tag head line 7
## Premature end of data in tag html line 6
```

```
## Error: 1: Opening and ending tag mismatch: p line 30 and div
## 2: Opening and ending tag mismatch: p line 42 and div
## 3: Opening and ending tag mismatch: div line 39 and script
## 4: Opening and ending tag mismatch: div line 27 and head
## 5: Specification mandate value for attribute data-offcanvas
## 6: attributes construct error
## 7: Couldn't find end of Start Tag div line 60
## 8: Opening and ending tag mismatch: section line 66 and p
## 9: Opening and ending tag mismatch: div line 71 and p
## 10: Opening and ending tag mismatch: p line 74 and div
## 11: Opening and ending tag mismatch: p line 76 and div
## 12: Opening and ending tag mismatch: div line 70 and section
## 13: Opening and ending tag mismatch: input line 90 and div
## 14: Opening and ending tag mismatch: div line 88 and form
## 15: Opening and ending tag mismatch: form line 87 and div
## 16: Opening and ending tag mismatch: div line 84 and header
## 17: Opening and ending tag mismatch: header line 83 and div
## 18: Opening and ending tag mismatch: script line 27 and html
## 19: Premature end of data in tag script line 24
## 20: Premature end of data in tag head line 7
## 21: Premature end of data in tag html line 6
```

- [Ensembl](http://www.ensembl.org/biomart/martview) - [Genome databases for vertebrates and other eukaryotic species](http://www.ensembl.org/)


```r
host <- "ensembl.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##                biomart               version
## 1 ENSEMBL_MART_ENSEMBL      Ensembl Genes 83
## 2     ENSEMBL_MART_SNP  Ensembl Variation 83
## 3 ENSEMBL_MART_FUNCGEN Ensembl Regulation 83
## 4    ENSEMBL_MART_VEGA               Vega 63
## 5                pride        PRIDE (EBI UK)
```

- [VEGA](http://www.ensembl.org/biomart/martview) - [Manual annotation of vertebrate genome sequences](http://vega.sanger.ac.uk/)


```r
host <- "ensembl.org"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
##                biomart               version
## 1 ENSEMBL_MART_ENSEMBL      Ensembl Genes 83
## 2     ENSEMBL_MART_SNP  Ensembl Variation 83
## 3 ENSEMBL_MART_FUNCGEN Ensembl Regulation 83
## 4    ENSEMBL_MART_VEGA               Vega 63
## 5                pride        PRIDE (EBI UK)
```

- [Rfam](http://xfam-biomart.sanger.ac.uk/) - [The Rfam database is a collection of RNA families, each represented by multiple sequence alignments, consensus secondary structures and covariance models (CMs)](http://rfam.sanger.ac.uk)


```r
host <- "xfam-biomart.sanger.ac.uk"
path <- "/biomart/martservice"
listMarts(mart=NULL, host, path)
```

```
## [1] biomart version
## <0 rows> (or 0-length row.names)
```



```r
listMarts(mart = NULL, host="plants.ensembl.org", path="/biomart/martservice")
```

```
##             biomart              version
## 1       plants_mart           Plant Mart
## 2 plants_variations Plant Variation Mart
```

```r
listMarts(mart = NULL, host="fungi.ensembl.org", path="/biomart/martservice")
```

```
##             biomart               version
## 1       fungal_mart           Fungal Mart
## 2 fungal_variations Fungal Variation Mart
```

```r
listMarts(mart = NULL, host="metazoa.ensembl.org", path="/biomart/martservice")
```

```
##              biomart                version
## 1       metazoa_mart           Metazoa Mart
## 2 metazoa_variations Metazoa Variation Mart
```


## References

- http://www.biomart.org/community.html
- https://support.bioconductor.org/p/75730/#75786
