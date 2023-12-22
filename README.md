# YAML to JSONL Converter for GPT Fine-Tuning
____________________________________________________________________________________________________________________________________________
## Overview
This Python project provides a versatile tool for converting YAML formatted data into JSONL (JSON Lines) format, facilitating preparation of data for fine-tuning GPT (Generative Pre-trained Transformer) models.
____________________________________________________________________________________________________________________________________________
# Purpose

Fine-tuning large language models like GPT requires well-formatted data in a suitable format. YAML is a structured and human-readable format, while GPT models often utilize the JSONL format for training. This tool bridges the gap between these formats, enabling swift conversion of YAML files into JSONL, ensuring compatibility and ease in utilizing data for GPT fine-tuning.

<ins>YAML to JSONL Conversion</ins>: Convert YAML files containing structured data into the JSONL format required for GPT fine-tuning.

____________________________________________________________________________________________________________________________________________
# Usage

<ins>Installation</ins>: Clone this repository and install the necessary dependencies outlined in the requirements.txt file.

<ins>Execution</ins>: Run the converter script, specifying the input YAML file(s) and desired output directory:

```bash
python dataset_generator.py --yaml_file <path_to_yaml_file> --output_path <output_directory>
```
____________________________________________________________________________________________________________________________________________
