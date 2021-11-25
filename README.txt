# Repeat Expansion Database

We maintain a databases of known repeat expansions associated with disease and provide database files for several bioinformatic methods for detecting repeat expansions with short read sequencing for commonly used reference genomes.

For more details about how to perform repeat expansion detection, please see our [tutorial and example repeat expansion analysis workflow](https://github.com/bahlolab/STR_Expansions_Example_Workflow).

## Disease-associated repeat expansions

| Bioinformatic Method         | hg19 | hg38 | GRCh37 | GRCh38 |
|:----------------------------:|:----:|:----:|:------:|:------:|
| ExpansionHunter              | XXXX | XXXX | XXXXXX | XXXXXX |
| exSTRa                       | XXXX | XXXX | XXXXXX | XXXXXX |
| GangSTR                      | XXXX | XXXX | XXXXXX | XXXXXX |
| ExpansionHunter (v2 format)  | XXXX | XXXX | XXXXXX | XXXXXX |

Notes:
1. The strength of the supporting evidence linking each of these repeat expansions to disease varies.. For example, see the review [Depienne & Mandel..](XXX) or the [AGHA Repeat Disorders PanelApp](https://panelapp.agha.umccr.org/panels/3597/)
2. The exSTRa database files contain optional columns with additional useful information, such as pathogenic disease thresholds
3. Only ExpansionHunter supports degenerate bases (eg: GCN polyalanine repeats) thus the database for this tool contains additional repeat expansions not contained in the other catalogs
4. ExpansionHunter version 2 used a different database format compared the more recent versions of the software. We provide both formats for legacy reasons.

