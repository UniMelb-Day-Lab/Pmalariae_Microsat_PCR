# Modified semi-nested PCR protocol for _P. malariae_ microsatellite genotyping
A modified semi-nested PCR protocol for _P. malariae_ microsatellite genotpying. This protocol involves twelve _P. malariae_microsatellite loci distributed across eight chromosomes: six loci are from the panel developed by [Bruce et al. (2006)](https://pmc.ncbi.nlm.nih.gov/articles/PMC1868962/) (Pm01_817, Pm04_262, Pm04_548, Pm12_232, Pm12_649, Pm13_337) and six loci are from the panel developed by [Mathema et al. (2020)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6988369/) (Pm05_707, Pm06_506, Pm07_429, Pm09_801, Pm12_426, Pm13_110). For this modified protocol, these two separate panels were combined and multiplexed, allowing simultaneous amplification of multiple loci in a single reaction. This multiplexing approach was necessary to conserve the amount of gDNA used, espcailly when working with dried blood spot (DBS) samples collected from participants with low-density _P. malariae_ infections.


## Primers
The modified semi-nested PCR for _P. malariae_ microsatellite genotpying was carried out using the primers described by [Bruce et al. (2006)](https://pmc.ncbi.nlm.nih.gov/articles/PMC1868962/) and [Mathema et al. (2020)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6988369/). For this modified PCR protocol the primers for the six loci from [Mathema et al. (2020)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6988369/) were adapted for a semi-nested PCR strategy by designing outer primers for the first round of amplification, with one primer reused in the second round,  while the primers for the six loci from [Bruce et al. (2006)](https://pmc.ncbi.nlm.nih.gov/articles/PMC1868962/) were used as originally designed. Reagent concentrations and cycling conditions were optimized to improve sensitivity when working with low-density _P. malariae_ infections.


| Species (Primer Pairs)    | Primer Name | PCR Round | Primers sequences (5'- 3')
| ----------- | ----------- |----------- |----------- |
| _Plasmodium_ spp.| rPLU6| 1|TTAAAATTGTTGCAGTTAAAACG|
|  |rPLU5| 1|CCTGTTGTTGCCTTAAACTTC|
| _P. falciparum_| rFAL1|2|TTAAACTGGTTTGGGAAAACCAAATATATT|
|  |rFAL2| 2| ACACAATGAACTCAATCATGACTACCCGTC|
| _P. malariae_| rMAL1|2|ATAACATAGTTGTACGTTAAGAATAACCGC|
|  |rMAL2| 2|AAAATTCCCATGCATAAAAAATTATACAAA|
| _P. ovale_ spp.| rOVA1|2|ATCTCTTTTGCTATTTTTTAGTATTGGAGA|
|  |rOVA2| 2|GGAAAAGGACACATTAATTGTATCCTAGTG|
| _P. vivax_| rVIV1|2|CGCTTCTAGCTTAATCCACATAACTGATAC|
|  |rVIV2| 2|ACTTCCAAGCCGAAGCAAAGAAAGTCCTTA|

## PCR Protocol
The original PCR protocols were developed by [Bruce et al. (2006)](https://pmc.ncbi.nlm.nih.gov/articles/PMC1868962/) and [Mathema et al. (2020)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6988369/) and were modified, as described below. 

The PCR protocol and cycling conditions were optimized to maximize amplification success, particularly for DBS samples from low-density _P. malariae_ infections.

### Round 1
Each first-round PCR was carried out in a total volume of 25 µL, comprising 5 µL of gDNA template, with final concentrations of 1X buffer, 3 mM of MgCl2, 0.4 mM of dNTP mix, 0.04 µM of each primer (i.e., Primer 1-4, forward and reverse), 1.2 units of GoTaq G2 Hot Start polymerase (Promega), and nuclease-free water. 

The first-round PCRs were multiplexed (i.e., three separate PCR reactions each containing four different sets of primers). Note that the same PCR protocol was used for all three first round multiplex reactions (i.e., Multiplex 1, Multiplex 2, and Multiplex 3). 

 
| Reagent    | Final Concentration | Volume 1X |
| ----------- | ----------- |----------- |
| Buffer (5X)| 1X| 5 μL |
| MgCl2 (25 mM)| 3 mM| 3 μL |
| dNTP mix (10 mM)| 0.4 mM|1 μL |
| Primer-1 forward  (2.5 μM)| 0.04 μM|0.4 μL |
| Primer-1 reverse  (2.5 μM)| 0.04 μM|0.4 μL |
| Primer-2 forward  (2.5 μM)| 0.04 μM|0.4 μL |
| Primer-2 reverse  (2.5 μM)| 0.04 μM|0.4 μL |
| Primer-3 forward  (2.5 μM)| 0.04 μM|0.4 μL |
| Primer-3 reverse  (2.5 μM)| 0.04 μM|0.4 μL |
| Primer-4 forward  (2.5 μM)| 0.04 μM|0.4 μL |
| Primer-4 reverse  (2.5 μM)| 0.04 μM|0.4 μL |
| GoTaq G2 Flexi (5 U/μL)| 1.2 units |0.24 μL |
|Nuclease-free water|  | 7.56 μL |
|gDNA Template|  |5 μL |
|TOTAL VOLUME|  |25 μL |

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
The second round was carried out in four separate tubes, each containing a single species-specific primer pair (i.e., rFAL1/rFAL2 to detect the presence of _P. falciparum_, rMAL1/rMAL2 for _P. malariae_, rOVA1/rOVA2 for _P. ovale_ spp., rVIV1/rVIV2 for _P. vivax_).

The second round of the nested nested _18S rRNA_ PCR, was carried out in a total volume of 20 μL, comprising 2 µL of gDNA of the first-round PCR product, with final concentrations of 1X buffer, 2 mM of MgCl2, 0.125 mM of dNTP mix, 0.125 μM of each primer, 0.4 units of GoTaq G2 Flexi DNA polymerase (Promega), and nuclease-free water.
 


## References
Please use the following citation, as indicated, when referencing this protocol:
* Tiedje KE, Oduro AR, Agongo G, Anyorigiya T, Azongo D, Awine T, Ghansah A, Pascual M, Koram KK, Day KP. Seasonal variation in the epidemiology of asymptomatic _Plasmodium falciparum_ infections across two catchment areas in Bongo District, Ghana. Am J Trop Med Hyg. 2017;97: 199–212.(https://pmc.ncbi.nlm.nih.gov/articles/PMC5508908/)
