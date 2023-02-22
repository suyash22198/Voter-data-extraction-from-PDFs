# Voter-data-extraction-from-PDFs
Disclaimer :- For education purpose only. You can get idea to use Tabula and pyPDF2 library for PDF data  extraction here.

Instruction:-
1. Create two folder name "Feed_folder" and "Output_folder" in same location where you put Voter_data_extraction.ipynb file.
2. Put OCRed PDFs in Feed_folder (You can make PDF searchable or OCRed using any online platform).
3. Install Tabula and pyPDF2 before running script.
4. Run the whole script and after completion you can get CSV of extracted data in "Output_folder".
5. In case of feeding multiple PDFs if any PDF got failed to extrcted you can get logs of those PDFs in "LOG.csv" (you can get this logs file in "Output_folder").
6. Please change the backslash or forward slash in Main function CELL according to system you are using. (i.e. In mac path is like '/Some_folder/sub_folder' and in windows and ubuntu it like 'C:\Some_folder\sub_folder') Otherwise you got error.
