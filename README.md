# util-flag-pdfs
Utility written in python, designed to distinguish between searcheable vs non-searcheable pdfs, located in a target directory.<br>
It outputs a list contained in a .xlsx file, where pdf names are listed, with the IS_SEARCHEABLE parameter set to True/False.<br>
For usage cases run flag-textpdf-cli.py/.exe -h. If no path is provided, a filemanager window will appear, where you can specify the target directory.<br>
A binary release is located in the output/flag-textpdf-cli directory. The binary was generated using auto-py-to-exe (pyinstaller with a GUI).<br>
