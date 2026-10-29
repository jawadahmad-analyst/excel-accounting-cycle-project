# Accounting Cycle in Excel

I built this project to practise the full accounting cycle in Excel, from the first journal entry to the final balance sheet. The company is a made-up trading business, Nexora Industries Limited, and the year runs from 1 July 2025 to 30 June 2026. All amounts are in PKR.

The idea was simple: type the transactions once in the journal, and let everything else (ledger, trial balance, income statement, balance sheet) come from formulas.

## Files

| File | What it is |
|---|---|
| `Accounting_Cycle_Nexora.xlsx` | The Excel workbook (download this to open it) |
| `Accounting_Cycle_Nexora.pdf` | Same workbook as a PDF, if you just want to read it |
| `screenshots/` | Images of each sheet |
| `docs/` | Notes on the transactions and the formulas I used |

GitHub can't show Excel files in the browser, so please download the `.xlsx` to use the formulas.

## Sheets in the workbook

1. **Overview** - short summary, key results and assumptions
2. **Chart of Accounts** - 15 accounts with code, category and the statement they belong to
3. **General Journal** - 14 double-entry journal entries (the only place with typed numbers)
4. **Ledger** - every account with a running balance
5. **Trial Balance** - totals per account, with a check that debits equal credits
6. **Income Statement** - sales down to net profit after 30% tax
7. **Balance Sheet** - assets against liabilities and equity

## Results

- Sales: 1,225,000
- Gross profit: 735,000
- Operating profit: 475,000
- Net profit after tax: 332,500
- Total assets: 6,225,000
- Trial balance and balance sheet both balance (check cells show 0)

## Screenshots

![Journal](screenshots/03-general-journal.png)
![Trial balance](screenshots/06-trial-balance.png)
![Income statement](screenshots/07-income-statement.png)
![Balance sheet](screenshots/08-balance-sheet.png)

More in the `screenshots` folder.

## Assumptions

- The payment method was not given for the Multi Media purchase, the computer, office, entertainment, salary and rent. I assumed all were paid from the bank.
- No depreciation on the computer, to keep the exercise simple.
- Tax is 30% of operating profit, recorded at year end as payable to the government.
- Cost of goods sold (490,000) is recorded as two adjusting entries against inventory.

## What I learned

- How one journal entry flows through every statement
- Using `SUMIF` to build a trial balance instead of a pivot table
- Adding check cells so mistakes show up immediately
- Keeping inputs (blue) separate from formulas (black)

## Possible next steps

- Add depreciation on the computer
- Add a cash flow statement
- Add more months of transactions

---
Jawad Ahmad | BBA Finance, CUSIT Peshawar
