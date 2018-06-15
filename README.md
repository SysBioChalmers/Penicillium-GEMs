# Penicillium-GEMs

- Brief Model Description

This repository contains the collection of the current genome-scale metabolic models for 24 Penicillium species, which were reconstructed to study their secondary metabolism.

- Abstract:

Modeling of metabolism at the genome scale have proved to be an efficient approach to explain observed phenotypic traits in living organisms. Further, it can be used as a means of predicting the effect of genetic modifications e.g. for generation of microbial cell factories. With the increasing amount of genome sequencing data available, a need exists to accurately and efficiently generate such genome scale metabolic models (GEMs) of non-model organisms, which have limited experimental characterization associated to them. In this study, we present an automatic reconstruction approach applied to 24 Penicillium species, which have potential for production of small molecule pharmaceuticals, so-called secondary metabolites. The models were based on the MetaCyc database and a previously published Penicillium GEM, and gave rise to comprehensive genome scale descriptions of their metabolism. The models proved that while central carbon metabolism is conserved, secondary metabolic pathways represent the main diversity among the species. The automatic reconstruction approach presented in this study can be applied to generate GEMs of other understudied organisms, and the developed GEMs are a useful resource for the study of Penicillium metabolism, for example with the scope of developing novel cell factories.
- Model KeyWords:

**GEM Category:** Collection; **Utilisation:** maximising product growth, experimental data reconstruction; **Field:** metabolic-network reconstruction; **Type of Model:** reconstruction; **Model Source:** [MetaCyC](http://metacyc.org/), [iAL1006](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002980); **Omic Source:** [Genomics](https://www.nature.com/articles/nmicrobiol201744); **Taxonomy:** Penicillium; **Metabolic System:** General Metabolism, Secondary metabolism; **Condition:** Rich Media;

- Reference:  none yet

- Pubmed ID: none yet

- Last update: 2017-11-30

- The model:

|Taxonomy | Template Model | Reactions | Metabolites| Genes |
| ------------- |:-------------:|:-------------:|:-------------:|-----|
|Penicillium antarcticum|	Pantarcticum.xml|	2572|	3064|	1755|
|Penicillium arizonense|	Parizonense.xml|	2629|	3120|	1954|
|Penicillium biforme|	Pbiforme.xml|	2638|	3134|	1878|
|Penicillium brasilianum|	Pbrasilianum.xml|	2658|	3192|	1894|
|Penicillium camemberti|	Pcamemberti.xml|	2631|	3134|	1859|
|Penicillium carneum|	Pcarneum.xml|	2469|	2931|	1611|
|Penicillium coprophilum|	Pcoprophilum.xml|	2443|	2895|	1530|
|Penicillium decumbens|	Pdecumbens.xml|	2211|	2623|	1256|
|Penicillium digitatum|	Pdigitatum.xml|	2351|	2829|	1403|
|Penicillium expansum|	Pexpansum.xml|	2601|	3085|	1873|
|Penicillium flavigenum|	Pflavigenum.xml|	2506|	2973|	1712|
|Penicillium freii|	Pfreii.xml|	2562|	3037|	1766|
|Penicillium fuscoglaucum|	Pfuscoglaucum.xml|	2637|	3154|	1886|
|Penicillium griseofulvum|	Pgriseofulvum.xml|	2579|	3066|	1700|
|Penicillium italicum|	Pitalicum.xml|	2453|	2924|	1536|
|Penicillium nalgiovense|	Pnalgiovense.xml|	2515|	2967|	1677|
|Penicillium oxalicum|	Poxalicum.xml|	2458|	2967|	1435|
|Penicillium paneum|	Ppaneum.xml|	2468|	2935|	1581|
|Penicillium polonicum|	Ppolonicum.xml|	2537|	3016|	1727|
|Penicillium roqueforti|	Proqueforti.xml|	2467|	2935|	1611|
|Penicillium rubens|	Prubens.xml|	2574|	3058|	1771|
|Penicillium solitum|	Psolitum.xml|	2623|	3134|	1886|
|Penicillium steckii|	Psteckii.xml|	2555|	3101|	1748|
|Penicillium vulpinum|	Pvulpinum.xml|	2501|	2949|	1627|



This repository is administered by Sylvain Prigent @syprigen, Division of Systems and Synthetic Biology, Department of Biology and Biological Engineering, Chalmers University of Technology




## Installation

### Required Software:

You need either: 
  * A functional **COBRApy** installation, find it [here](https://cobrapy.readthedocs.io/en/latest/)
or
  * A functional Matlab installation of **Matlab_R_2015_b**  (MATLAB 7.3 and higher)
  * The [RAVEN](https://github.com/SysBioChalmers/RAVEN) toolbox for MATLAB. An up-to-date version from COBRA GitHub repository is strongly recommended . Add the directory to your Matlab path, instructions [here](https://se.mathworks.com/help/matlab/ref/addpath.html?requestedDomain=www.mathworks.com)

### Dependencies - Recommended Software:
* libSBML MATLAB API (version [5.13.0](https://sourceforge.net/projects/sbml/files/libsbml/5.13.0/stable/MATLAB%20interface/)  is recommended).


### Installation Instructions
* Clone [Penicillium-GEMs](https://github.com/SysBioChalmers/Penicillium-GEMs) branch from [SysBioChalmers GitHub](https://github.com/SysBioChalmers)
* Add the directory to your Matlab path, instructions [here](https://se.mathworks.com/help/matlab/ref/addpath.html?requestedDomain=www.mathworks.com)

## Complementary Scripts
The snakefile contains a workflow to parse MetaCyc flat files and create files that could be used for Blast or HMMs studies. 
- MetaCyc flat files should be put in the "data" folder

## Contributors
- [Sylvain Prigent](http://www.sysbio.se/profiles/Sylvain.html), Chalmers University of Technology, Gothenburg Sweden
- [Jens Christian F. Nielsen](http://www.sysbio.se/profiles/JensCh.html), Chalmers University of Technology, Gothenburg Sweden

## License
The MIT License (MIT)

> Copyright (c) 2017 Systems and Synthetic Biology
>
> Chalmers University of Technology Gothenburg, Sweden
>
>Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
>
>The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
>
>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
