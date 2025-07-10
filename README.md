# Automated PDF Report Generation

This project is a Python script that demonstrates how to automatically generate a professional, formatted PDF report from a dataset. The script reads sales data, performs a basic analysis, and outputs a clean report with a summary and a detailed data table.

## Features

- **Data Analysis**: Calculates total revenue, average sale value, and identifies the top-performing salesperson.
- **Dynamic PDF Generation**: Uses the `fpdf2` library to create a multi-page PDF document from scratch.
- **Custom Formatting**: Includes a custom header with a title and timestamp, and a footer with page numbers.
- **Embedded Data**: The sample sales data is included directly in the script, so no external CSV file is needed.

## Sample Output

Here is an example of the generated PDF report:

*(To generate this, run the script and take a screenshot of the first page of `sales_report_india.pdf` and save it as `sample_report.png` in this folder)*

![Sample PDF Report](./sample_report.png)

## Technology Stack

- **Python 3**
- **Pandas**: For data manipulation and analysis.
- **FPDF2**: For PDF document generation.

## Setup and Installation

1.  **Clone the repository (optional):**
    ```bash
    git clone <your-repository-url>
    cd report_project
    ```

2.  **Install dependencies:**
    Make sure you have Python 3 installed. Then, install the required libraries using pip.
    ```bash
    pip install pandas fpdf2
    ```

## Usage

To generate the report, simply run the Python script from your terminal:

```bash
python generate_report.py
