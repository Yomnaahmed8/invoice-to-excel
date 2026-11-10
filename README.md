# Invoice to Excel

Turns a folder of PDF invoices into a clean Excel report in seconds.

## What it does
- Reads every PDF in the `invoices` folder
- Extracts vendor, invoice number, date, line items and total
- Checks that line items add up to the total (flags mismatches)
- Exports everything to `invoices.xlsx`

## Run it
    pip install -r requirements.txt
    python make_samples.py
    python extract.py

## Built with
Python, pdfplumber, pandas
