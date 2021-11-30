# mastersthesis-experimental-data

This repository serves as a documentation for the experiments described in my Master's Thesis "Pruning Techniques for Lifted SAT-Based Hierarchical Planning".

## Used Software

The softwares we evaluated are located here:

* Our modified Lilotane: https://github.com/NikolaiLMS/lilotane (forked from https://github.com/domschrei/lilotane)
* PandaPIParser: https://github.com/panda-planner-dev/pandaPIparser
* PandaPIGrounder: https://github.com/panda-planner-dev/pandaPIgrounder
* PandaPIEngine: https://github.com/panda-planner-dev/pandaPIengine
* HyperTensioN: https://github.com/Maumagnaguagno/HyperTensioN and https://gitlab.anu.edu.au/u1092535/ipc2020-competitor-4

Additionally we used the following software to help with test execution:
* Runwatch: https://github.com/domschrei/runwatch

## Content

* trainingset and testset contain our training and test data, which consists of the total-order instances of the IPC 2020 (https://github.com/panda-planner-dev/ipc2020-domains/tree/master/total-order)

* parameterevaluation, perdomainevaluation and sotaevaluation contain the experimental data for the Parameter Evaluation, the Per Domain Evaluation and State of The Art Evaluation, comprising of the logs for each instance, aswell as additional files that contain already computed metrics like IPC-Score, PAR2-Score, Coverage etc.
