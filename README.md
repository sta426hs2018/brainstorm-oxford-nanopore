# STA426 Group3 - Oxford Nanopore

## How it works

* Prior to sequencing, adapters are ligated to both ends of genomic DNA or cDNA fragments and are leaded through the pore
* The sensor detects changes in ionic current caused by differences in the shifting nucleotide sequences occupying the pore. These ionic current changes are segmented as discrete events that have an associated duration, mean amplitude, and variance.
* This sequence of events is then interpreted computationally as a sequence of 3–6 nucleotide long kmers (‘words’) using graphical models.

![How it works](https://media.springernature.com/full/springer-static/image/art%3A10.1186%2Fs13059-016-1103-0/MediaObjects/13059_2016_1103_Fig1_HTML.gif)


## What is it (Definition from Wikipedia)

Nanopore sequencing uses electrophoresis to transport an unknown sample through an orifice of 10<sup>-9</sup> meters in diameter. A nanopore system always contains an electrolytic solution- when a constant electric field is applied, an electric current can be observed in the system. The magnitude of the electric current density across a nanopore surface depends on the nanopore’s dimensions and the composition of DNA or RNA that is occupying the nanopore. Sequencing is made possible because, when close enough to nanopores, samples cause characteristic changes in electric current density across nanopore surfaces. The total charge flowing through a nanopore channel is equal to the surface integral of electric current density flux across the nanopore unit normal surfaces between times t1 and t2.

 Device| Technology
:-|-:
![Device](/Device.png) | ![Technology](/Nanopore_Seq.jpg)



## Advantage

* Cheap
* Small / Portability
* Rapid processing -> display results in real time

## Disadvantage

* High error rate
"insertion, deletion and substitution rates of 4.9%, 7.8% and 5.1%, respectively" (Jain et al., 2015 in Reuter, Spacek and Snyder, 2015).

Reuter JA, Spacek D, Snyder MP. High-Throughput Sequencing Technologies. Molecular cell. 2015;58(4):586-597. doi:10.1016/j.molcel.2015.05.004.

## Useful links	

* [Wikipedia](https://en.wikipedia.org/wiki/Oxford_Nanopore_Technologies)
* [Oxford Nanopore](https://nanoporetech.com/)
* [Paper on performance of Oxford Nanopore Technology](https://www.sciencedirect.com/science/article/pii/S2214753515000224)
* [A first look](https://onlinelibrary.wiley.com/doi/full/10.1111/1755-0998.12324)
* [Advantages of long reads for genome assembly](https://nanoporetech.com/sites/default/files/s3/white-papers/WGS_Assembly_white_paper.pdf?submissionGuid=40a7546b-9e51-42e7-bde9-b5ddef3c3512)

![Technology](/Oxford-Nanopore.png)

## Group members
Vivian Leung, Samuel Pawel, Charlotte Micheloud, Sandra Siegfried, Mauro Schläpfer, Tobias Hoch
