# Formulas used

**Credit line copies the debit line (General Journal)**
`=F6`

**Trial balance totals per account**
`=SUMIF('General Journal'!$E$6:$E$33, C6, 'General Journal'!$F$6:$F$33)` for debit
`=SUMIF('General Journal'!$E$6:$E$33, C6, 'General Journal'!$G$6:$G$33)` for credit

**Debit / credit balance**
`=MAX(E6-F6,0)` and `=MAX(F6-E6,0)`

**Running balance in the ledger**
`=SUM($E$7:E7)-SUM($F$7:F7)`

**Income statement tax**
`=-ROUND(D16*C17,0)` where C17 is the 30% rate

**Balance sheet check (should be 0)**
`=D16-D27`

Other: data validation drop-down for account names in the journal, cross-sheet cell links, blue font for typed inputs.
