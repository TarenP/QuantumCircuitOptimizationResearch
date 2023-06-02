# QuantumCircuitOptimizationResearch

This repository contains scripts for generating, collecting, and analyzing data on quantum circuits. The scripts serve different purposes, as described below:

## Scripts

1. `Random QC Data Gen.ipynb`: This script generates random quantum circuits with varying complexities. The complexities of the circuits are randomly determined, and the script collects data on these circuits, such as gate counts, execution times, and qubit usage. The collected data is stored for further analysis.

2. `Reconstructor.ipynb`: This script allows for the reconstruction of previously generated quantum circuits. The circuits are stored in a CSV file, and this script reads the file to reconstruct the circuits. The reconstructed circuits can be used for further analysis or experimentation.

3. `Sequential QC Data Gen.ipynb`: This script generates quantum circuits with sequentially increasing complexities. The complexities of the circuits start from a minimum value and increment by a fixed step size. Similar to the `Random QC Data Gen.ipynb` script, data is collected on these circuits for analysis purposes.

## Data Analysis

The collected data from the quantum circuits is used to perform analysis and generate graphs. The analysis includes studying the relationship between circuit complexity and factors such as execution time, gate count, and qubit usage. The generated graphs provide visual representations of the data, allowing for easier interpretation and insights.

1. `/QMachineData`: This file contains the collected data from the generated quantum circuits. It includes information such as circuit complexity, gate counts, execution times, and qubit usage.

2. `/Graphs`: This directory contains the graphs generated from the collected data. Each graph corresponds to a specific analysis, and the files are named accordingly.

This repository has been used to collect data to produce these research papers:
[Analysis of IBM Qiskit's Transpiler and Optimizer for Quantum Circuits](https://widgets.figshare.com/articles/23272724/embed?show_title=1)
[Quantum Circuit Complexity-Based-Optimization](https://widgets.figshare.com/articles/23256344/embed?show_title=1)
