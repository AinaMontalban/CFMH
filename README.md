# Code For Mental Health - bitsxlaMarató 2021 Hackathon

## Authors: 
* Lluis Grifols
* Paula Iborra
* Aina Montalban

## Description

`Snakemake` workflow to identify a consensus of protein-protein complexes obtained from different different protein docking programs (e.g., ftdock, zdock)

## Repository Content

* The [input_files]() folder contains the PDB structures of protein-protein complexes from __ftdock__ and __zdock__ docking programs.
* The [logs]() folder contains the log files from the workflow.
* The [results]() folder contains the best configuration for each docking program.
* The [scripts]() folder contains the python scripts used in the workflow.
* The [workflow]() contains the [Snakefile]() file.
* 

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

