# Cibil_Analysis

This repository contains a Jupyter Notebook for analyzing CIBIL report data. The notebook processes text data extracted from a CIBIL report and generates an Excel file with separate sheets for various personal and financial details.

## Features

- Extracts and processes text data from CIBIL reports.
- Creates an Excel file with sheets for:
  - Personal Details
  - Identification Details
  - Address Details
  - Contact Details
  - Email Details
  - Employment Details
  - All Accounts

## Prerequisites

To run this notebook locally, you need to have:
- Jupyter Notebook installed
- Python 3.x
- Required Python libraries (listed in the notebook)

Alternatively, you can run the notebook directly on Google Colab.

## Setup

### Local Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/Jaisrepo/Cibil_Analysis.git
   cd Cibil_Analysis
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Cibil_Analysis.ipynb
   ```

4. Provide the path to the text file containing the CIBIL report data:
   ```python
   file_path = 'path/to/your/cibil_report.txt'
   ```

5. Run all cells in the notebook to generate the Excel file.

### Google Colab

1. Click the link below to open the notebook in Google Colab:
   [Open in Colab](https://colab.research.google.com/drive/15gBsvzC2Pvwd7xKUxT3dgLR_-9-nZPZI?usp=sharing)

2. Upload the text file containing the CIBIL report data when prompted.

3. Run all cells in the notebook to generate the Excel file.

## Usage

1. Save the text from your CIBIL report as a `.txt` file.
2. Provide the file path in the notebook.
3. Run the notebook to generate an Excel file with the parsed data.

## Output

The output Excel file will contain the following sheets:
- Personal Details
- Identification Details
- Address Details
- Contact Details
- Email Details
- Employment Details
- All Accounts

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by opening issues or submitting pull requests.

Happy analyzing!
