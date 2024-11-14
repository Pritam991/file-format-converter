# File Format Converter

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)


A Python-based tool for converting CSV files into JSON format. This converter dynamically loads CSV files, applies schemas for consistent data formatting, and saves them as JSON files. Ideal for processing multiple datasets efficiently, the converter offers a modular design and batch-processing capabilities.

## Features

- **Automatic File Detection**: Utilizes glob patterns to automatically detect CSV files for processing.
- **Schema-Based Conversion**: Reads column schemas from a configuration file to ensure consistency in the output JSON structure.
- **Dynamic Dataset Identification**: Extracts dataset names from file paths or names using regular expressions.
- **Flexible CSV to JSON Transformation**: Loads CSV files into Pandas DataFrames with the specified schema, allowing flexible data manipulation.
- **Target Path Generation**: Automatically generates output file paths for the JSON files.
- **Batch Processing Wrapper**: Supports converting multiple datasets in a single call, making it efficient for handling large volumes of files.

## Requirements

- **Python 3.x**
- **Pandas** library (`pip install pandas`)

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/file-format-converter.git
