# Modified semi-nested PCR protocol for _P. malariae_ microsatellite genotyping
This document provides the details for the modified semi-nested PCR protocol for _P. malariae_ microsatellite genotyping.

Please use the following citation when referencing this modified PCR protocol and the newly designed outer primers for the first-round PCR:
* _This manuscript is in preperation and will be provided once published (Rios-Teran et al. (2025))_


#
This appraoch involves twelve _P. malariae_ microsatellite loci distributed across eight chromosomes: six loci are from the panel developed by [Bruce et al. (2006)](https://pmc.ncbi.nlm.nih.gov/articles/PMC1868962/) (Pm01_817, Pm04_262, Pm04_548, Pm12_232, Pm12_649, Pm13_337) and six loci are from the panel developed by [Mathema et al. (2020)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6988369/) (Pm05_707, Pm06_506, Pm07_429, Pm09_801, Pm12_426, Pm13_110). 

For this modified protocol, these two separate panels were combined and multiplexed, allowing simultaneous amplification of multiple loci in a single reaction. This multiplexing approach was necessary to conserve the amount of gDNA used, espcailly when working with dried blood spot (DBS) samples collected from participants with low-density _P. malariae_ infections.


## Primers
The modified semi-nested PCR for _P. malariae_ microsatellite genotpying was carried out using the primers described by [Bruce et al. (2006)](https://pmc.ncbi.nlm.nih.gov/articles/PMC1868962/) and [Mathema et al. (2020)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6988369/). 

For this modified PCR protocol the primers for the six loci from [Mathema et al. (2020)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6988369/) were adapted for a semi-nested PCR strategy by designing outer primers for the first round of amplification, with one primer reused in the second round,  while the primers for the six loci from [Bruce et al. (2006)](https://pmc.ncbi.nlm.nih.gov/articles/PMC1868962/) were used as originally designed. 

Reagent concentrations and cycling conditions were optimized to improve sensitivity when working with low-density _P. malariae_ infections.


#### Table 1. Primer sequences for the _P. malariae_ microsatellite genotyping.

| Locus     | Previously Published Locus Name | Multiplex Grouping (1st round PCR)<sup>a</sup> | Primer Sequences (5'-3') | Fluorescent Tag<sup>*</sup> | Repeat Unit | Chr | Reference Genome Position (bp)<sup>d</sup> |
|----------|-------------------------------|----------------------------------------------|----------------------------|-----------------------------|--------------|-----|--------------------------------------------|
| Pm12_23  | Pm02<sup>b</sup>              | Multiplex 1                                  | for GGGGCATAAAGGAAAAAC<br>rev GAATTTTTGAATAACAAGAAACC<br>for* GCATAATACAGTGATGCTTAG | 6-FAM          | (CATA)       | 12  | 2328408 – 2328592                       |
| Pm04_26  | Pm11<sup>b</sup>              | Multiplex 1                                  | for CTTTATTTGTGGTCGAGG<br>rev GGGATATGAATTACATACAC<br>rev* GAGGAAAGGTTGAAGTGG       | HEX            | (TAAAACAAAAA)| 4   | 262698 – 262978                           |
| Pm12_64  | Pm25<sup>b</sup>              | Multiplex 2                                  | for GAGGTAACTTAAAAAATTCAC<br>rev CCAAATAAGTGACATACAAC<br>rev* CTCCCCATTTTTCGTTC     | NED            | (GT)         | 12  | 649749 – 649860                           |
| Pm13_33  | Pm34<sup>b</sup>              | Multiplex 2                                  | for TTGGACAATGAAAAAACTAAG<br>rev GAATGGAAAAATTCCTTCAG<br>for* CAAGATGAACAACTGATAGGG | 6-FAM          | (CA)         | 13  | 337588 – 337807                           |
| Pm04_54  | Pm47<sup>b</sup>              | Multiplex 3                                  | for TGTATGTTTTATGTTCACTTC<br>rev TAAAGGTGTAGTGTAGAG<br>for* AAACCGCTGGCTTTACG       | HEX            | (CAATT)      | 4   | 548614 – 548948                           |
| Pm01_81  | Pm09<sup>b</sup>              | Multiplex 3                                  | for GTTCATAACTTTGATCTTAAC<br>rev ACGATAATAATATAAATGGGG<br>for* CATTTGACCAATTTAACACATTC | NED        | (GCAAAATAACAAAAAGA) | 1 | 817944 – 818261                           |
| Pm05_70  | Pm05_707<sup>c</sup>          | Multiplex 1                                  | **for~ ACTTTTGGTGACTCGGGCAA**<br>rev CGCTCGGGTCATCGTTATTA<br>for* GGTAGAAGGAGCAACGGACA   | 6-FAM          | (AAT)        | 5   | 707573 – 707750                           |
| Pm06_50  | Pm06_506<sup>c</sup>          | Multiplex 1                                  | **for~ TGTTCTGGCGTTCTGTTGAC**<br>rev CAAAAGGGAAGGAGCACAAA<br>for* TTGTGCGTATGCAACCTTTC   | HEX            | (ACAT)       | 6   | 506234 – 506508                           |
| Pm07_42  | Pm07_429<sup>c</sup>          | Multiplex 2                                  | **for~ CCTCAGAATCTTCTGCATCCGT**<br>rev CGAATGAGAGTAGTGCGGAAA<br>for* TTCCTTTTCATCCTCTGCAA | NED          | (AAT)        | 7   | 429296 – 429513                           |
| Pm09_80  | Pm09_801<sup>c</sup>          | Multiplex 2                                  | **for~ TACACCGTCCGGTCAACTTA**<br>rev TCACACTCCTTTCAATTTCTCA<br>for* TGACTTCGGTTAGAATATGTTTGC | 6-FAM      | (ACAT)       | 9   | 801873 – 802096                           |
| Pm12_42  | Pm12_426<sup>c</sup>          | Multiplex 3                                  | **for~ ACGTGCTCTCCTTTTCCACA**<br>rev GATCACTTCGCACGGGATAG<br>for* TTCGTGTTCTCGCTTTCCTC   | HEX            | (ATC)        | 12  | 426095 – 426285                           |
| Pm13_11  | Pm13_110<sup>c</sup>          | Multiplex 3                                  | **for~ GTCCTCGACAGGGAACAAAA**<br>rev CAGACGAGGACTTTCATTTCG<br>for* TCAAGTGGAATAACCGCAAG  | NED            | (AAT)        | 13  | 1109697 – 1109856                       |

<sup>a</sup> Groups of primers multiplexed together during the first round of the semi-nested PCR.  
<sup>b</sup> Primers first described by [Bruce et al. (2006)](https://pmc.ncbi.nlm.nih.gov/articles/PMC1868962/) .  
<sup>c</sup> Primers first described by [Mathema et al. (2020)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6988369/).  
<sup>~</sup> Primers in bold were designed in this study (Rios-Teran et al., 2025, publication in preperation) to target previously published loci using a semi-nested PCR approach.  
<sup>*</sup> Fluorescent tags used for second-round semi-nested PCR.  
<sup>d</sup> Genome position (bp) based on _P. malariae_ reference genome ([PmUG01, NIH, NCBI 2025](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_900090045.1/)), relative to second-round product.


## PCR Protocol
The original PCR protocols were developed by [Bruce et al. (2006)](https://pmc.ncbi.nlm.nih.gov/articles/PMC1868962/) and [Mathema et al. (2020)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6988369/) and were modified, as described below. 

The semi-nested PCR protocol and cycling conditions were modified to maximize amplification success, particularly for DBS samples from low-density _P. malariae_ infections.

### Round 1
Each first-round of this semi-nested PCR was carried out in a total volume of 25 µL, comprising 5 µL of gDNA template, with final concentrations of 1X buffer, 3 mM of MgCl₂, 0.4 mM of dNTP mix, 0.04 µM of each primer (i.e., Primer 1-4, forward and reverse; see Table 1), 1.2 units of GoTaq G2 Hot Start polymerase (Promega), and nuclease-free water. 

The first-round PCRs were multiplexed (i.e., three separate PCR reactions each containing four different sets of primers)(see Table 1).

_Note: The same PCR protocol was used for all three first round multiplex reactions (i.e., Multiplex 1, Multiplex 2, and Multiplex 3)._

#### Table 2. Round 1 PCR mastermix.

| Reagent                      | Final Concentration | Volume 1X |
|-----------------------------|---------------------|-----------|
| Buffer (5X)                 | 1X                  | 5 μL      |
| MgCl₂ (25 mM)               | 3 mM                | 3 μL      |
| dNTP mix (10 mM)            | 0.4 mM              | 1 μL      |
| Primer-1 forward (2.5 μM)   | 0.04 μM             | 0.4 μL    |
| Primer-1 reverse (2.5 μM)   | 0.04 μM             | 0.4 μL    |
| Primer-2 forward (2.5 μM)   | 0.04 μM             | 0.4 μL    |
| Primer-2 reverse (2.5 μM)   | 0.04 μM             | 0.4 μL    |
| Primer-3 forward (2.5 μM)   | 0.04 μM             | 0.4 μL    |
| Primer-3 reverse (2.5 μM)   | 0.04 μM             | 0.4 μL    |
| Primer-4 forward (2.5 μM)   | 0.04 μM             | 0.4 μL    |
| Primer-4 reverse (2.5 μM)   | 0.04 μM             | 0.4 μL    |
| GoTaq G2 Flexi (5 U/μL)     | 1.2 units           | 0.24 μL   |
| Nuclease-free water         |                     | 7.56 μL   |
| gDNA Template               |                     | 5 μL      |
| **TOTAL VOLUME**            |                     | **25 μL** |

#### Cycling conditions:
* 94ᵒC for 4 min
* 35 cycles of
   * 94ᵒC for 30 sec
   * 48ᵒC for 30 sec
   * 68ᵒC for 1 min
* 68ᵒC for 2 min
* storage at 4°C

_Note: For each PCR, positive (i.e., previously genotyped P. malariae isolates) and negative (i.e., nuclease-free water) controls were included for quality control._

### Round 2
The second-round PCRs required the preparation of 12 separate reactions with the fluorescent-labelled primers (see Table 1). 

Each second-round PCR was carried out in a total volume of 25 µL, comprising 3 µL of the first-round PCR product, with final concentrations of 1X buffer, 3 mM of MgCl₂, 0.2 mM of dNTP mix, 0.08 µM of each primer (see Table 1), 0.6 units of GoTaq G2 Hot Start polymerase (Promega), and nuclease-free water. 

#### Table 3. Round 2 PCR mastermix.

| Reagent                    | Final Concentration | Volume 1X |
|----------------------------|---------------------|-----------|
| Buffer (5X)                | 1X                  | 5 μL      |
| MgCl₂ (25 mM)              | 3 mM                | 3 μL      |
| dNTP mix (10 mM)           | 0.2 mM              | 0.5 μL    |
| Primer-1 forward (2.5 μM)  | 0.08 μM             | 0.8 μL    |
| Primer-1 reverse (2.5 μM)  | 0.08 μM             | 0.8 μL    |
| GoTaq G2 Flexi (5 U/μL)    | 0.6 units           | 0.12 μL   |
| Nuclease-free water        |                     | 11.78 μL  |
| First-round PCR product    |                     | 3 μL      |
| **TOTAL VOLUME**           |                     | **25 μL** |
 
#### Cycling conditions:
* 94ᵒC for 4 min
* 45 cycles of
   * 94ᵒC for 30 sec
   * 52ᵒC for 30 sec
   * 68ᵒC for 1 min
* 68ᵒC for 2 min
* storage at 4°C
 
### Capillary electrophoresis
For the capillary electrophoresis, four pools with the fluorescently labeled round-two PCR products were prepared for each _P. malariae_ isolate, as descibed below (see Table 4). 

These pools were then sent to the [Australian Genome Research Facility](https://www.agrf.org.au) (Melbourne, AU) where capillary electrophoresis was performed on an Applied Biosystems 3730xl DNA analyser with a 50m array and POP-7 polymer (ThermoFisher Scientific) and the size standard LIZ500. 

#### Table 4. Pooling strategy for _P. malariae_ microsatellite genotyping.

| Pool     | Marker 1     | Marker 2     | Marker 3     | Water | Total Volume |
|----------|--------------|--------------|--------------|--------|---------------|
| **Pool 1** | Pm12_232     | Pm04_262     | Pm12_649     |        |               |
| Fluorescent Dye | 6-FAM        | HEX          | NED          |        |               |
| Amplicon Size (bp) | 185          | 281          | 112          |        |               |
| Volume (per primer mix) | 2 µL         | 2 µL         | 2 µL         | 6 µL   | 12 µL         |
``
| **Pool 2** | Pm13_337     | Pm04_548     | Pm01_817     |        |               |
| Fluorescent Dye | 6-FAM        | HEX          | NED          |        |               |
| Amplicon Size (bp) | 220          | 335          | 318          |        |               |
| Volume (per primer mix) | 2 µL         | 2 µL         | 2 µL         | 6 µL   | 12 µL         |
``
| **Pool 3** | Pm05_707     | Pm06_506     | Pm07_479     |        |               |
| Fluorescent Dye | 6-FAM        | HEX          | NED          |        |               |
| Amplicon Size (bp) | 178          | 275          | 218          |        |               |
| Volume (per primer mix) | 2 µL         | 2 µL         | 2 µL         | 6 µL   | 12 µL         |
``
| **Pool 4** | Pm09_801     | Pm12_426     | Pm13_110     |        |               |
| Fluorescent Dye | 6-FAM        | HEX          | NED          |        |               |
| Amplicon Size (bp) | 224          | 191          | 160          |        |               |
| Volume (per primer mix) | 2 µL         | 2 µL         | 2 µL         | 6 µL   | 12 µL         |
``


## Citations used in

This modified semi-nested PCR protocol for _P. malariae_ microsatellite genotyping has been used in the following citations:

* Tan MH, Bangre O, Rios-Teran CA, Tiedje KE, Deed SL, Zhan Q, Rasyidi F, Pascual M, Ansah PO, Day KP. Metagenomic analysis reveals extreme complexity of Plasmodium spp. infections in high transmission in West Africa. medRxiv [Preprint]. 2025 May 2:2025.04.29.25326533. doi: 10.1101/2025.04.29.25326533. PMID: 40343031; PMCID: PMC12060935 (https://pubmed.ncbi.nlm.nih.gov/40343031/)
