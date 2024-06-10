# SeriviceTitan-task

Overview

This project provides a Python class, InvoiceProcessor, to process and transform invoice data from a pickled file and identify expired invoices based on a given list. The class loads the data, processes each invoice item to calculate various metrics, and transforms the data into a sorted Pandas DataFrame. The final processed data is saved to a CSV file for further analysis.

Features

Load Invoice Data: Load invoices from a pickled file (invoices_new.pkl) and expired invoice IDs from a text file (expired_invoices.txt).
Process Invoice Data: Calculate total_price for each invoice item, percentage_in_invoice, and determine if an invoice is expired.
Transform Data: Transform the processed data into a DataFrame with specified columns and sort by invoice_id and invoiceitem_id.
Robust Data Handling: Handle invalid dates and missing keys gracefully.
