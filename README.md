# mypipeline

<!-- TODO: Add pipeline title -->

### Introduction

The pipeline is built using [Nextflow](https://www.nextflow.io), a workflow tool to run tasks across multiple compute infrastructures in a very portable manner. 
It comes with docker / singularity containers making installation trivial and results highly reproducible.

The current workflow is based on the nf-core best practice. See the nf-core project from details on [guidelines](https://nf-co.re/).

### Short comparison of trimming tools

|   | TrimGalore | Fastp | Atropos |
|---|------------|-------|---------|
| 'pico'  | &#x2611;  | &#x2611; | &#9746; | 
| Min size trimmed  | &#x2611;  | &#x2612;  | &#x2611;  |
| Atropos |    |   |   |

### Documentation

1. [Installation](docs/installation.md)
2. Pipeline configuration
    * [Local installation](docs/configuration/local.md)
    * [Reference genomes](docs/configuration/reference_genomes.md)  
3. [Running the pipeline](docs/usage.md)
4. [Output and how to interpret the results](docs/output.md)
5. [Troubleshooting](docs/troubleshooting.md)

<!-- TODO nf-core: Add a brief overview of what the pipeline does and how it works -->

### Credits
<!-- TODO add authors -->
