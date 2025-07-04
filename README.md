# Modified PCR protocol for _P. malariae_ microsatellite genotyping
A modified semi-nested PCR protocol for _P. malariae_ microsatellite genotpying. This protocol involves twelve _P. malariae_microsatellite loci distributed across eight chromosomes: six loci are from the panel developed by [Bruce et al. (2006)] (Pm01_817, Pm04_262, Pm04_548, Pm12_232, Pm12_649, Pm13_337) and six loci are from the panel developed by [Mathema et al. (2020)] (Pm05_707, Pm06_506, Pm07_429, Pm09_801, Pm12_426, Pm13_110). For this modified protocol, these two separate panels were combined and multiplexed, allowing simultaneous amplification of multiple loci in a single reaction. This multiplexing approach was necessary to conserve the amount of gDNA used, espcailly when working with dried blood spot (DBS) samples collected from participants with low-density infections (e.g., submicroscopic _P. malariae_ infections). 

For this updated protocol the six markers from Mathema et al. (2020) were adapted for a semi-nested PCR strategy by designing outer primers for the first round of amplification, with one primer reused in the second round,  while the six markers from Bruce et al. (2006) were used as originally designed. Reagent concentrations and cycling conditions were optimized to improve sensitivity when working with low-density _P. malaria_e infections.

## Primers
The modified semi-nested PCR for _P. malariae_ microsatellite genotpying was carried out using the primers described by

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
This nested _18S rRNA_ PCR protocol was developed by [Snounou et al. 1993](https://pubmed.ncbi.nlm.nih.gov/8264734/) and further adapted by [Boonma et al. 2007](https://pubmed.ncbi.nlm.nih.gov/17868467/). 

These published PCR protocols were modified (as described below) by [Tiedje et al. 2017](https://pmc.ncbi.nlm.nih.gov/articles/PMC5508908/) to maximize amplification success, particularly with dried blood spot (DBS) samples collected from participants with low-density infections (e.g., submicroscopic _Plasmodium_ spp. infections).  

### Round 1
The first round of the nested nested _18S rRNA_ PCR, was carried out in a total volume of 20 μL, comprising 2 µL of gDNA template, with final concentrations of 1X buffer, 2 mM of MgCl2, 0.125 mM of dNTP mix, 0.125 μM of each primer (rPLU6/rPLU5), 0.4 units of GoTaq G2 Flexi DNA polymerase (Promega), and nuclease-free water.
 
| Reagent    | Final Concentration | Volume 1X |
| ----------- | ----------- |----------- |
| Buffer (5X)| 1X| 4 μL |
| MgCl2 (25 mM)| 2 mM|1.6 μL |
| dNTP mix (10 mM)| 0.125 mM|0.25 μL |
| Primer rPLU6 (2.5 μM)| 0.125 μM|1 μL |
| Primer rPLU5 (2.5 μM)| 0.125 μM|1 μL |
| GoTaq G2 Flexi (5 U/μL)| 0.4 units |0.08 μL |
|Nuclease-free water|  |10.07 μL |
|gDNA Template|  |2 μL |
|TOTAL VOLUME|  |20 μL |

#### Cycling conditions:
* 95ᵒC for 2 min
* 25 cycles of
   * 58ᵒC for 2 min
   * 72ᵒC for 5 min
   * 94ᵒC for 1 min
* 58ᵒC for 2 min
* 72ᵒC for 2 min
* storage at 4°C

_Note: For each PCR, positive (i.e., P. falciparum 3D7 isolate) and negative (i.e., nuclease-free water) controls were included for quality control._

### Round 2
The second round was carried out in four separate tubes, each containing a single species-specific primer pair (i.e., rFAL1/rFAL2 to detect the presence of _P. falciparum_, rMAL1/rMAL2 for _P. malariae_, rOVA1/rOVA2 for _P. ovale_ spp., rVIV1/rVIV2 for _P. vivax_).

The second round of the nested nested _18S rRNA_ PCR, was carried out in a total volume of 20 μL, comprising 2 µL of gDNA of the first-round PCR product, with final concentrations of 1X buffer, 2 mM of MgCl2, 0.125 mM of dNTP mix, 0.125 μM of each primer, 0.4 units of GoTaq G2 Flexi DNA polymerase (Promega), and nuclease-free water.
 
| Reagent    | Final Concentration | Volume 1X |
| ----------- | ----------- |----------- |
| Buffer (5X)| 1X| 4 μL |
| MgCl2 (25 mM)| 2 mM|1.6 μL |
| dNTP mix (10 mM)| 0.125 mM|0.25 μL |
| Primer example rFAL1 (2.5 μM)| 0.125 μM|1 μL |
| Primer example rFAL2 (2.5 μM)| 0.125 μM|1 μL |
| GoTaq G2 Flexi (5 U/μL)| 0.4 units |0.08 μL |
|Nuclease-free water|  |10.07 μL |
|gDNA Round 1 PCR|  |2 μL |
|TOTAL VOLUME|  |20 μL |

#### Cycling conditions:
* 30 cycles of
   * 58ᵒC for 2 min
   * 72ᵒC for 5 min
   * 94ᵒC for 1 min
* 58ᵒC for 2 min
* 72ᵒC for 2 min
* storage at 4°C

## References
Please use the following citation, as indicated, when referencing this protocol:
* Tiedje KE, Oduro AR, Agongo G, Anyorigiya T, Azongo D, Awine T, Ghansah A, Pascual M, Koram KK, Day KP. Seasonal variation in the epidemiology of asymptomatic _Plasmodium falciparum_ infections across two catchment areas in Bongo District, Ghana. Am J Trop Med Hyg. 2017;97: 199–212.(https://pmc.ncbi.nlm.nih.gov/articles/PMC5508908/)
