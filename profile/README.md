# Welcome to CNU-nuclear

A repository for research in Nuclear Physics at CNU!

Please find:
* A list of references below
* Pposters, talks and other research presentations [in this Google drive folder](https://drive.google.com/drive/folders/1BWwwZptw6c7BQ-n_Xrf1Cb8SgVdB0OOj?usp=sharing) 

# References 

.... work in progress ....

This Readme might also be a good places to maintain the list of references that we currently have in a canvas in Slack. (but no collapsible sections and subsections...) Let's give it a try.

# Getting started

## LaTeX

- Getting started in LaTeX - Overleaf: https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes

## Nuclear physics

Overviews:

- [Protons are made of quarks but ruled by gluons](https://bigthink.com/starts-with-a-bang/protons-quarks-gluons/) - by Ethan Siegel, Big think (2025)
- [Strong Interactions: stories from the heart of the matter](https://www.stronginteractions.org/episodes/)
  - great podcast
  - see esp. Episode 3 for PDFs (and Ep.1 for an intro)
- [Visualizing the Quantum World](https://www.jlab.org/physics/visualizingthequantumworld) website
  - Visualizations of
    - the quark-gluon structure proton
    - and the proton-neutron structure of nuclei
  - (plus explanations, links)

(Grad) textbooks

- Povh et al., "[Particles and Nuclei](https://www.amazon.com/Particles-Nuclei-Introduction-Physical-Concepts/dp/3662463202)", Springer 2015
  - Especially Chapters 6, 7, 8 on electron scattering
  - available also at [this link](https://www.phenix.bnl.gov/WWW/publish/elke/EIC/BOOKs/ParticlesAndNuclei.pdf)
- Griffith, Intro to [Particle Physics](https://www.amazon.com/Introduction-Elementary-Particles-David-Griffiths-ebook/dp/B08R2BZ4MX), Wiley 2004

## Probability and statistics

- H. Pishro-Nik, "Introduction to probability, statistics, and random processes", available at [https://www.probabilitycourse.com](https://www.probabilitycourse.com/), Kappa Research LLC, 2014.
  - Good introductory text - practical, with solid math foundation
  - Notable: Chap 14 - [Simulations in Python](https://www.probabilitycourse.com/chapter14/chapter14.php)
- ....

## Plotting advice

- Ten simple rules for better figures: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003833

## Greek alphabet

- Not the best (I don't like the lower case nu and upper case sigma) but not bad: https://www.pinterest.com/pin/handwritten-greek-alphabet-guide--413627547039983858/
- With more detail on the pen strokes: https://www.pinterest.com/pin/281543706662962/

# Python and computing

- Python Tutorial - W3schools: [free here](https://www.w3schools.com/python/) Pretty goo also as a reference; try it yourself code cells
- Python Data Science Handbook - J. VanderPlas ~2016: free on the [Web](https://jakevdp.github.io/PythonDataScienceHandbook/)and [GitHub](https://github.com/jakevdp/PythonDataScienceHandbook)

- LHAPDF parton distributions in Colab: https://colab.research.google.com/drive/1YqmSehxmKIiDXLgW48ALz0CFBRvr9sqz?usp=sharing
- CJ-JAM database (PDFs and structure functions) https://github.com/JeffersonLab/CJ-JAM-database

# Parton Distributions

## General references

- Valence quark Q^2 evolution https://inspirehep.net/literature/1788615
- Large-x exponents https://inspirehep.net/literature/1439779
- W. K. Tung, [Perturbative QCD and the parton structure of the nucleon](https://indico.cern.ch/event/507575/contributions/2164831/attachments/1276861/1894847/IntroPqcd.pdf) (Lecture notes on PDFs and high energy probes of hadron structure)
- K. Kovarik, P. M. Nadolski, D. E. Soper, [Hadron structure in high-energy collisions](https://inspirehep.net/literature/1735355) (Review paper on PDFs and "global QCD fits")
- Owens, Tung, [Parton distribution functions of hadrons](https://inspirehep.net/literature/333107), Ann.Rev.Nucl.Part.Sci. 42 (1992) 291-332 (Old but compact review on PDFs - see especially the first 3 sections)
- [Monte Carlo Particle Numbering Scheme](https://pdg.lbl.gov/2024/reviews/rpp2024-rev-monte-carlo-numbering.pdf)

And now for some history:

- [Q^2 Dependent Parametrizations of Parton Distribution Functions](https://inspirehep.net/literature/194172), Phys.Rev.D 30 (1984) 49-54 (One of the first PDF fits ever)
- And its 1991 update: [An Updated set of parton distribution parametrizations](https://inspirehep.net/literature/316513), Phys.Lett.B 266 (1991) 126-130

## Modern PDF Sets

Needs a little update. These are one generation behind.

- CJ15:
  - [Accardi et al.](https://inspirehep.net/literature/1420566), 2016
  - [Park, Accardi et al.](https://inspirehep.net/literature/1904100), 2021
- [CT10](https://inspirehep.net/literature/861245)
- [JAM20](https://inspirehep.net/literature/1840421) (also see FF)
- [MSTW2008](https://inspirehep.net/literature/810127)
- [PDF4LHC15](https://inspirehep.net/literature/1397826) (combination of CT14, MMHT2014, and NNPDF3.0)
- [PDF4LHC21](https://inspirehep.net/literature/2049642) (combination of CT18, MSHT20, and NNPDF3.1)

# Higher-Twist corrections in DIS

Gemini has a [nice AI summary](https://www.google.com/search?q=how+would+you+describe+higher+twist+corrections+to+DIS+processes+in+a+simple+way%2C+at+an+undergraduate+im+Physocs+level%3F&rlz=1C1RXQR_enUS1017US1017&oq=how+would+you+describe+higher+twist+corrections+to+DIS+processes+in+a+simple+way%2C+at+an+undergraduate+im+Physocs+level%3F&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIHCAEQIRiPAjIHCAIQIRiPAtIBCjI2NTk0ajBqMTWoAgiwAgHxBfKBBpMIqyP0&sourceid=chrome&ie=UTF-8)

Here is a couple of journal articles:

- Accardi 2010: "Subleading effects in QCD global fits" https://inspirehep.net/literature/885622
- Cerutti et al. 2025: "Systematic uncertainty from HT corrections..." https://inspirehep.net/literature/2867833 (esp. Sect II.C)

The first one is a short (and I hope sweet) overview of 1/Q2 corrections. The second one discusses the implementation of HT in global fits: Sect II.C is a short review, and Sect II.D discusses global fit-specific issues.

# Fragmentation Functions

- Reviews: Metz, Vossen, "[Parton Fragmentation Functions](https://inspirehep.net/literature/1475000)", Prog.Part.Nucl.Phys. 91 (2016) 136-202 Particle Data Group (2024), [Fragmentation Functions](https://pdg.lbl.gov/2024/web/viewer.html?file=../reviews/rpp2024-rev-frag-functions.pdf)
- Lectures: E. Nocera @ HUGS 2017 [Lecture 1](https://www.jlab.org/hugs/lectures/NOCERA_HUGS17_1.pdf), [Lecture 2](https://www.jlab.org/hugs/lectures/NOCERA_HUGS17_2.pdf), [Lecture 3](https://www.jlab.org/hugs/lectures/NOCERA_HUGS17_3.pdf) (summary table on page 3) Accardi @ Academia Sinica, Taiwan 2017 [Recent developments in FF analysis and applications](https://phys.ncts.ntu.edu.tw/uploads/asset/data/61d2b5a61d41c85d941eed8f/20181126_Accardi.pdf) E. Nocera, INT workshop 2021 [Collinear FF tehorey review](https://archive.int.washington.edu/talks/WorkShops/int_21_80W/People/Nocera_E/Nocera.pdf)

## Papers for FF sets

- [DSS07](https://inspirehep.net/literature/746992)
- [DSS14](https://inspirehep.net/literature/1323293) (Pion FF update)
- [DSS17](https://inspirehep.net/literature/1514558) (Kaon FF update)
- [HKNS](https://inspirehep.net/literature/745249) 2007
- [JAM20](https://inspirehep.net/literature/1840421) (also see PDF)
- MAPFF10:
  - [Pions and Kaons at NNLO](https://inspirehep.net/literature/2071159) 2022
  - [Pions](https://inspirehep.net/literature/1864155) 2021
- [NNFF](https://inspirehep.net/literature/1606327)
- NPC23:
  - Gao et al., [PRL 132 (2024) 26](https://inspirehep.net/literature/2743585)
  - Gao et al., [arXiv:2502.17837](https://inspirehep.net/literature/2894356)
- HAPS-FF1.0
  - [Pions and Kaons](https://inspirehep.net/literature/3168717)
  - [Unidentified Hadrons](https://inspirehep.net/literature/3162974)
  - HAPS-PiFF1.0 Pion FF for LHAPDF ([LHAPDF Set](https://github.com/HAPS-Collaboration/HAPS-PiFF1.0))
  - HAPS-KaFF1.0 Kaon FF for LHAPDF ([LHAPDF Set](https://github.com/HAPS-Collaboration/HAPS-KaFF1.0))
- [SGKS20](https://inspirehep.net/literature/1811390)

HAPS Collaboration fragmentation functions. Fits from 2026 including updated COMPASS data and considerations of HMCs - [Modern Determination of Pion and Kaon Fragmentation Functions from SIA and High-Precision COMPASS SIDIS Multiplicities](https://inspirehep.net/literature/3168717) - [Revisiting Unidentified Charged-Hadron Fragmentation Functions with Modern COMPASS SIDIS Multiplicities](https://inspirehep.net/literature/3162974)

# Hadron Mass Corrections

## Getting Started

- Short summary: [A Note on Hadron Mass corrections](https://drive.google.com/file/d/18cC7c1LbOleafpPWuazTR3oXHnYpzRlf/view?usp=drive_link) (A. Accardi)
- Talk by Alberto Accardi at the Frascati workshop, Dec 2024: https://agenda.infn.it/event/39742/contributions/248673

## Formalism

- [Hadron mass corrections in semi-inclusive deep inelastic scattering](https://inspirehep.net/literature/825647), Accardi, Hobbs, Melnitchouk, JHEP 11 (2009), 084

First one, also looks at pion and kaon data from JLab and HERMES

- [Hadron mass corrections in semi-inclusive deep-inelastic scattering](https://inspirehep.net/literature/1369104), Guerrero et al., JHEP 09 (2015), 169

More complete analysis, canbe used as references for our calculations

## Applications

- [Gauge invariance and kaon production in deep inelastic scattering at low scales](https://inspirehep.net/literature/1635890), Guerrero, Accardi, Phys.Rev.D 97 (2018) 11, 114012

Looks at HERMES vs. COMPASS kaons (plus more theory)

# SIDIS experimental data (papers & databases)

## HERMES

- [Multiplicities of charged pions and kaons from semi-inclusive deep-inelastic scattering by the proton and the deuteron](https://inspirehep.net/literature/1208547), HERMES Collaboration, A. Airapetian, Phys.Rev.D 87 (2013) 074029
  - [HERMES Kaon and Pion HEPData](https://www.hepdata.net/record/ins1208547)
- [Reply to “Comment on ‘Reevaluation of the parton distribution of strange quarks in the nucleon’”](https://inspirehep.net/literature/1388183), HERMES Collaboration, E.C. Aschenauer, Phys.Rev.D 92 (2015) 9, 098102
  - Data included in paper (M^K+ + M^K- extraced from tables III and IV)
- The HERMES multiplicities database:
  - Original site [archived on the wayback machine](https://web.archive.org/web/20150613012228/http://hermesmults.appspot.com/) (click "[download all](https://web.archive.org/web/20150613012228/http://www-hermes.desy.de/multiplicities/database/data/HERMES-multiplicities.tar.gz)" for a zipped file with all the data)
  - Slightly [update version](https://www.hermesmults.appspot.com/) with additional figure and explanation (but to get the data and plots, use the wayback machine version, see above)

## COMPASS

- [Multiplicities of charged pions and charged hadrons from deep-inelastic scattering of muons off an isoscalar target](https://inspirehep.net/literature/1444985), COMPASS Collaboration, C. Adolph, Phys.Lett.B 764 (2017) 1-10
  - Data extracted from Figure 9
  - [COMPASS Pion HEPData](https://www.hepdata.net/record/ins1444985)
- [Multiplicities of charged kaons from deep-inelastic muon scattering off an isoscalar target](https://inspirehep.net/literature/1483098), COMPASS Collaboration, C. Adolph, Phys.Lett.B 767 (2017) 133-141
  - Data extracted from Figures 8 and 9
  - [COMPASS Kaon HEPData](https://www.hepdata.net/record/ins1483098)
- [Addendum to multiplicities of charged pions, kaons and unidentified charged hadrons on an isoscalar target measured by COMPASS Collaboration](https://inspirehep.net/literature/3096394), COMPASS Collaboration, G.D. Alexeev, Phys.Lett.B 875 (2026) 140266
  - Revision of earlier multiplicities with improved radiative corrections
  - [Revised COMPASS Pion, Kaon, and Hadron HEPData](https://www.hepdata.net/record/ins3096394)

## JLab 6 GeV pions

- [The Onset of Quark-Hadron Duality in Pion Electroproduction](https://inspirehep.net/literature/724242), T. Navasardyan et al., Phys.Rev.Lett. 98 (2007) 022001
  - Data included in paper (Cross sections in Table I)
- [Semi-Inclusive Charged-Pion Electroproduction off Protons and Deuterons: Cross Sections, Ratios and Access to the Quark-Parton Model at Low Energies](https://inspirehep.net/literature/891896), R. Asaturyan et al., Phys.Rev.C 85 (2012) 015202
  - Data included in paper (Multiplicity ratio in Table XV)

## JLab 12 GeV pions

- [Flavor dependence of charged pion fragmentation functions](https://inspirehep.net/literature/2822734), H. Bhatt et al., Phys.Lett.B 865 (2025) 139485







