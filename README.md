# SavingStreamRec

Reconciles expected versus actual interest payments for Saving Stream accounts.

Uses the LoanParts CSV (downloaded from the "My Loans" page) and Statement CSV (downloaded from the "My Account" page, after setting the date range to cover the lifetime of the account) as input, for example:

> ssrec.py SS_LoanParts_20160901.csv SS_Statement_20160901.csv
