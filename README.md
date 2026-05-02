# PRISM to DMN (Canonical Implementation)

This project implements the Canonical PRISM algorithm and converts the extracted IF–THEN rules into a DMN (Decision Model and Notation) decision table compatible with Camunda.

## Features
- Implements the Canonical PRISM rule induction algorithm
- Works with categorical datasets
- Generates IF–THEN classification rules
- Uses separate-and-conquer strategy
- Applies tie-breaking criteria for rule selection
- Supports default class prediction
- Exports rules to DMN XML format (Camunda compatible)

## Example Dataset
- PlayTennis dataset (categorical)

## How to run
Run the script: python playTennisPRISM.ipynb

## Libraries used
- pandas
- xml.etree.ElementTree
- xml.dom.minidom
- uuid
