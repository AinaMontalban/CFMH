# Code For Mental Health - bitsxlaMarató 2021 Hackathon

## Authors: 
* Lluis 
* Paula 
* Aina 

## Description

`Snakemake` workflow to identify the best protein-protein complex obtained from different different protein docking programs (e.g., ftdock, zdock)

## Repository Content

* The [input_files](https://github.com/AinaMontalban/CFMH/tree/main/input_files) folder contains the PDB structures of protein-protein complexes from _ftdock_ and _zdock_ docking programs.
* The [logs](https://github.com/AinaMontalban/CFMH/tree/main/logs/local) folder contains the log files from the workflow.
* The [results](https://github.com/AinaMontalban/CFMH/tree/main/results) folder contains the best configuration for each docking program.
* The [scripts](https://github.com/AinaMontalban/CFMH/tree/main/scripts) folder contains the python scripts used in the workflow.
* The [workflow](https://github.com/AinaMontalban/CFMH/tree/main/workflow) contains the [Snakefile](https://github.com/AinaMontalban/CFMH/blob/main/workflow/Snakefile) file.
* [Script](https://github.com/AinaMontalban/CFMH/blob/main/run_workflow.sh) to run the workflow.

## Installation steps

1. Install enviroment:
> conda env create -f environment.yml

2. Define all variables in `config.yaml`

3. Execute test workflow dryrun:
> ./test_rule_graph.sh

4. Execute run workflow:
> ./run_workflow.sh

Details of the workflow `rule_graph.svg`
Details of the execution in `snakemake_report.html`

