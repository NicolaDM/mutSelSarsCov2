# mutSelSarsCov2

This repository contains the script and data for running the mutation and selection SARS-CoV-2 analysis of De Maio et al 2021 https://doi.org/10.1101/2021.01.14.426705 .

An example command line to run is: 
python3 estimate_and_plot_rates.py --path /example_path/coronavirus/mutation_selection/

The path in --path used to run the script needs to contain the reference and masked sites files, both of which can be found in this repository.

The script will then produce all the results of the analysis described in the manuscript.

In order to run the script, you will need a few python3 modules installed, including numpy, scipy, matplotlib, and discreteMarkovChain .

Please note that the main file with inferred mutation events is not included in the repository. In order to have access to this file (which was created with the help of Rob Lanfear, Yatish Turakhia and Russ Corbett-Detig) you need to accept the conditions of the GISAID database. After you have done this, please contact me.
