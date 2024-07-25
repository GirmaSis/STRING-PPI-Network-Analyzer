# STRING-PPI-Network-Analyzer




This repository contains a Python script that identifies and prints interactions between a given list of proteins. The script fetches interaction data from the STRING database API and filters interactions with a medium or higher confidence experimental score.

## Features

- **Fetches PPI data from the STRING database.**
- *Filters interactions based on experimental confidence scores.*
- Outputs interactions with a medium or higher confidence score.
- Saves the interaction data to a CSV file for further analysis.
- Plots the interaction network.

## Installation

To use this script, you need to have Python installed on your machine with the required Python packages. 
You can do this using the following commands:

```sh
git clone https://github.com/your-username/protein-interaction-network-analyzer.git
cd protein-interaction-network-analyzer
pip install -r requirements.txt

## Running the Script:
```sh
python ppi_analyzer.py -g TP53 BRCA1 EGFR VEGFA -o output.csv -t 0.4
python ppi_analyzer.py -g TP53 BRCA1 EGFR VEGFA MYC PTEN ESR1 CDKN2A -o output_4.csv -t 0.4


