# csv-generate.ipynb

This notebook generates a CV (Curriculum Vitae) in DOCX format using data from a JSON file.

## Requirements

- Python 3.x
- Libraries:
  - docxtpl

To install the required library, run:
!pip install docxtpl

## Usage

1. **Prepare Data:** Prepare your CV data in JSON format and save it as `model.json`.
2. **Prepare Template:** Prepare your CV template in DOCX format and save it as `cv_model.docx`.
3. **Run the Notebook:** Execute the notebook cell by cell.

## Overview

This notebook demonstrates how to generate a CV document using Python and a DOCX template. It reads data from a JSON file containing CV information and fills in a DOCX template accordingly.

## How it Works

- The notebook loads CV data from a JSON file (`model.json`).
- It loads a DOCX template (`cv_model.docx`) using the `docxtpl` library.
- It populates the template with the CV data.
- The generated CV is saved as `profile.docx`.

Feel free to explore the notebook and adapt the code to your use case!

