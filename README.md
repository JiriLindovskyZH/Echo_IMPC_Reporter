# Echo_IMPC_Reporter
Matlab app that searches through sonography report (csv file) output from VevoLab (by Fujifilm Visualsonics) and saves Excel spreadsheet with selected parameters of interest.

The app requires data input in a specific format, the necessary inputs are:
 1) Template .xlsx file which defines settings, input and output parameters (for testing, use IMPC_Echo_Template.xlsx) and metadata.
 2) List of animals with optional metadata (for testing, use Example animal list.txt). The content of this file will need to be in Windows clipboard, therefore, open the file in a text editor and use keyboard shortcuts "Ctrl + a" and "Ctrl + c". Notepad++ is a recommended text editor.
 3) VevoLab report file (for testing, use Example data.csv).
