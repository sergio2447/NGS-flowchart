# NGS-flowchart
A flowchart from the NGS assignment 
created by: Sergio, Luwei and Gitte

![Barbie x pokemon flowchart](https://user-images.githubusercontent.com/74473159/228907003-ae52893d-0fc4-4517-b642-a71c61d77f52.jpeg)

this flowchart contains the tools we used to analyse the illumina and nanopore data provided for this assesment:

## FastQC

Fastqc does the quality control of the illumina data and reportst summary statistics including the phred score.

## MultiQC

MulitiQC takes the FastQC reports and combine them to provide one summary overvieuw of all FastQC files.

## Trimmomatic

This tool trims the illumina data by a quality of 20 and a minimal read length of 30 bp.

## nanoplot

Nanoplot provides summary statistics of the Long reads containing the read length and quality score.

## nanofilt

This tool filters the long read data, the parameter has been set on a minimal read length of 1000bp

## unicycle

Unicycle does a hybrid assambly using the short and long reads. 

## quast

quast delivers summary statistics on the assambled data.

## kraken

kraken is used to determine the species, it uses a standard data base to alligne the assambled data and calls which species you have.

## bandage image

bandage creates a picture that visualize the assambled data.

## staramr

Staramr is used to determine which antibiotic resistance genes the bacteria has.

## RaXML

RaXML creates a phylogenetic tree from the given genomes.

## prokka

Prokka annotate the assemblys so they can be further analysed by roary.


## roary

Genarates a core genome alignment which can be visualized with phandago.

## phandago

Phandago visualizes the core genome and pan genome with the phylogenetic tree next to it.

