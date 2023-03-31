# NGS-flowchart
A flowchart from the NGS assignment 
created by: Sergio, Luwei and Gitte

![Barbie x pokemon flowchart](https://user-images.githubusercontent.com/127951831/229088680-22c36fa6-1685-4f83-aad4-b80245acbbe5.png)

This flowchart contains the tools we used to analyse the illumina and nanopore data provided for this assesment:

## FastQC

Fastqc does the quality control of the illumina data and reportst summary statistics including the phred score.

## MultiQC

MulitiQC takes the FastQC reports and combine them to provide one summary overvieuw of all FastQC files.

## Trimmomatic

This tool trims the illumina data by a quality of 20 and a minimal read length of 30 bp.

## Nanoplot

Nanoplot provides summary statistics of the Long reads containing the read length and quality score.

## Nanofilt

This tool filters the long read data, the parameter has been set on a minimal read length of 1000bp

## Unicycler

Unicycler does a hybrid assambly using the short and long reads. 

## QUAST

QUAST delivers summary statistics on the assambled data.

## Kraken2

Kraken2 is used to determine the species, it uses a standard data base to alligne the assambled data and calls which species you have.

## Bandage image

Bandage creates a picture that visualize the assambled data.

## Staramr

Staramr is used to determine which antibiotic resistance genes the bacteria has.

## RaXML

RaXML creates a phylogenetic tree from the given genomes.

## Prokka

Prokka annotate the assemblys so they can be further analysed by roary.


## Roary

Genarates a core genome alignment which can be visualized with phandago.

## Phandago

Phandago visualizes the core genome and pan genome with the phylogenetic tree next to it.

For the workflow see: [workflow](https://github.com/sergio2447/NGS-flowchart/blob/main/Galaxy-Workflow-NGS_assignment_final_try.ga)
