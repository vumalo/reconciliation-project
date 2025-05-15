Reconciliation Analysis

This project performs a simple reconciliation between settlement data and account statement data.

 🔍 Checks Performed:
- Values in settlement debit not found in account statement credit
- Values in settlement credit not found in account statement debit
- Values in account statement debit not found in settlement credit
- Values in account statement credit not found in settlement debit

 📂 Output Files:
The outputs are saved as Excel files and include highlighted unmatched entries:
- `settlement_debit_not_in_bank_credit.xlsx`
- `settlement_credit_not_in_bank_debit.xlsx`
- `bank_debit_not_in_settlement_credit.xlsx`
- `bank_credit_not_in_settlement_debit.xlsx`

 🛠 Tools Used:
- Python (pandas)
- Jupyter Notebook
- Excel formatting (highlighting unmatched data)

