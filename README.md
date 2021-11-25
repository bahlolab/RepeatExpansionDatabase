# Repeat Expansion Database

We maintain a databases of known repeat expansions associated with disease and provide database files for several bioinformatic methods for detecting repeat expansions with short read sequencing for commonly used reference genomes.

For more details about how to perform repeat expansion detection, please see our [tutorial and example repeat expansion analysis workflow](https://github.com/bahlolab/STR_Expansions_Example_Workflow).

## Disease-associated repeat expansions

| Bioinformatic Method         | hg19 | hg38 | GRCh37 | GRCh38 |
|:----------------------------:|:----:|:----:|:------:|:------:|
| ExpansionHunter              | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/hg19/ExpansionHunter_hg19.json) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/hg38/ExpansionHunter_hg38.json) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/GRCh37/ExpansionHunter_GRCh37.json) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/GRCh38/ExpansionHunter_GRCh38.json) |
| exSTRa                       | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/hg19/exSTRa_hg19.txt) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/hg38/exSTRa_hg38.txt) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/GRCh37/exSTRa_GRCh37.txt) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/GRCh38/exSTRa_GRCh38.txt) |
| GangSTR                      | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/hg19/GangSTR_hg19.bed) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/hg38/GangSTR_hg38.bed) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/GRCh37/GangSTR_GRCh37.bed)  | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/GRCh38/GangSTR_GRCh38.bed)  |
| ExpansionHunter (v2 format)  | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/hg19/ExpansionHunter_v2_hg19.tar.gz) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/hg38/ExpansionHunter_v2_hg38.tar.gz) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/GRCh37/ExpansionHunter_v2_GRCh37.tar.gz) | [link](https://github.com/bahlolab/RepeatExpansionDatabase/raw/master/disease/GRCh38/ExpansionHunter_v2_GRCh38.tar.gz) |

Notes:
1. The strength of the supporting evidence linking each of these repeat expansions to disease varies.. For example, see the review [Depienne & Mandel (2021)](https://doi.org/10.1016/j.ajhg.2021.03.011) or the [AGHA Repeat Disorders PanelApp](https://panelapp.agha.umccr.org/panels/3597/).
2. The exSTRa database files contain optional columns with additional useful information, such as pathogenic disease thresholds
3. Only ExpansionHunter supports degenerate bases (eg: GCN polyalanine repeats) thus the database for this tool contains additional repeat expansions not contained in the other catalogs
4. ExpansionHunter version 2 used a different database format compared the more recent versions of the software. We provide both formats for legacy reasons.

