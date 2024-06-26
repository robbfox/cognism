# Cognism Data Manipulation Tools

This project, developed as part of a business marketing task at [Sparta Global](https://www.spartaglobal.com/), is a collection of data manipulation tools designed to compile and de-duplicate contact details stored in various CSV files. The final goal is to prepare these data files for integration into a CRM system.
## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Installation](#installation)
- [Prerequisites](#prerequisites)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

The project provides tools to merge and de-duplicate contact information from multiple CSV files into a single Excel workbook. The initial datasets contain four phone columns which are consolidated into two. Each CSV is then pooled into a master dataframe, and duplicates are removed to ensure that each contact appears only once in the final dataset.

## Features

- **Phone Column Merging:** Consolidates four phone columns into two.
- **CSV Pooling:** Combines multiple CSV files into a single dataframe.
- **Duplicate Removal:** Checks each CSV against the master dataframe and returns a de-duplicated version.
- **Excel Workbook Integration:** The cleaned data is added to an Excel workbook for further use.

## Usage

1. **Prepare Your Data:**
   - Place your CSV files containing contact details in a specific directory.
   
2. **Run the Tools:**
   - Execute the Jupyter notebook or Python script to process the CSV files.
   - The tool will merge phone columns, pool the CSVs, and remove duplicates.
   
3. **Output:**
   - The cleaned data is saved into an Excel workbook ready for CRM integration.

## Installation

To use the tools in this repository, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/robbfox/cognism.git
   ```

2. Navigate to the project directory:
   ```bash
   cd cognism


3. Manually install openpyxl:
   ```bash
   pip install pandas openpyxl
   ```

## Prerequisites

- Python 3.6 or later
- `pandas` for data manipulation
- `openpyxl` for Excel file handling
- A working knowledge of Jupyter notebooks (if using the provided notebooks)

## Contributing

We welcome contributions to enhance the functionality or fix issues. If you wish to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your forked repository:
   ```bash
   git push origin feature-branch
   ```
5. Create a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- This project was developed at [Sparta Global](https://www.spartaglobal.com/), a leading provider of technology and business consulting services.
- Special thanks to the Cognism team for their support and guidance in developing these tools.
- Thank you to the open-source community for the invaluable resources and inspiration.

---

