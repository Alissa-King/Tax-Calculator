# 2024 US Federal and State Tax Calculator

## Description

This project is a comprehensive tax calculator for the 2024 tax year in the United States. It calculates both federal and state taxes based on income, filing status, state of residence, and number of dependents. The calculator uses up-to-date tax brackets and incorporates state-specific standard deductions and personal exemptions.

## Features

- Calculates federal taxes for four filing statuses:
  - Single
  - Married Filing Jointly
  - Head of Household
  - Married Filing Separately
- Incorporates state-specific tax calculations for all 50 states and Washington D.C.
- Includes state-specific standard deductions and personal exemptions
- Accounts for dependent exemptions by state
- Provides an interactive user interface using Jupyter widgets
- Displays a detailed tax calculation summary

## Requirements

- Python 3.7+
- Jupyter Notebook
- pandas
- ipywidgets

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/Alissa-King/2024-tax-calculator.git
   cd 2024-tax-calculator
   ```

2. Install the required packages:
   ```
   pip install jupyter pandas ipywidgets
   ```

3. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

4. Open the `Tax_Calculator_2024.ipynb` file in the Jupyter Notebook interface.

## Usage

1. Run all cells in the notebook.
2. Use the interactive widgets to input your information:
   - Enter your annual income
   - Select your state of residence
   - Choose your filing status
   - Set the number of dependents
3. Click the "Calculate Taxes" button to see your tax calculation summary.

## Limitations and Disclaimer

- State tax calculations are simplified and may not reflect all nuances of state tax laws.
- The calculator does not account for all possible deductions, credits, or adjustments that might apply to an individual's tax situation.
- This tool is for educational and estimation purposes only. For accurate tax calculations and advice, please consult a qualified tax professional.

## Contributing

Contributions to improve the calculator are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, please open an issue on this GitHub repository.
