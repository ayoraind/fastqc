## Pre-assembly QC workflow.
### Usage

```

=======================================================================
  PRE-ASSEMBLY QC: TAPIR Pipeline version 1.0dev
=======================================================================
 The typical command for running the pipeline is as follows:
        nextflow run main.nf --reads "PathToReadFile(s)" --output_dir "PathToOutputDir"  

        Mandatory arguments:
         --reads                        Query fastq.gz file of sequences you wish to supply as input (e.g., "/MIGE/01_DATA/01_FASTQ/T055-8-*.fastq.gz")
         --output_dir                   Output directory to place output (e.g., "/MIGE/01_DATA/03_ASSEMBLY")
         
        Optional arguments:
         --help                         This usage statement.
         --version                      Version statement

```


## Introduction
This pipeline generates pre-assembly QC plots. A large percentage of this pipeline was adapted from the [CGPS Nextflow Assembly Pipeline](https://gitlab.com/cgps/ghru/pipelines/dsl2/pipelines/assembly/-/tree/master/) and the fastqc module from the [NF Core Github page](https://github.com/nf-core/modules/blob/master/modules/nf-core/fastqc/main.nf). Fastqc may not be suitable for metagenomic reads derived from the ONT sequencing platform. 


## Sample command
An example of a command to run this pipeline is:

```
nextflow run main.nf --reads "Sample_files/*.fastq.gz" --output_dir "test2"
```

## Word of Note
This is an ongoing project at the Microbial Genome Analysis Group, Institute for Infection Prevention and Hospital Epidemiology, Üniversitätsklinikum, Freiburg. The project is funded by BMBF, Germany, and is led by [Dr. Sandra Reuter](https://www.uniklinik-freiburg.de/institute-for-infection-prevention-and-control/microbial-genome-analysis.html).


## Authors and acknowledgment
The TAPIR (Track Acquisition of Pathogens In Real-time) team.
