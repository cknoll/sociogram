# sociogram
Rudimentary toolkit to generate a sociogram.


Some future teachers have to create [https://en.wikipedia.org/wiki/Sociogram] as part of their training. The software support for this task seems to be suboptimal. This repo aims to mitigate the apparently suboptimal software support for this task.

## Data Collection and Preparation

**Ensure that the collected data is anonymized before processing it on a public web service like this!**

The data can be collected with a single question survey like: "How much do you like your classmates? Give each of the following names a rating on a scale from ⭐ to ⭐⭐⭐⭐⭐.

The results of this survey can be written to a table with N rows and N columns. Each column corresponds to one response questionaire. Each cell of that column containing a number between 1 and 5, except the cell corresponding to the author student themselves, which should contain zero. When ordering the columns in the same way as the names on the list The resulting table can be interpreted as a quadratic NxN matrix with zeros on its main diagonal (from upper left to lower right). This matrix should be exported as CSV-file (with some standard spreadsheet software like libre office calc). CSV is a text format with "**c**omma **s**eparated **v**alues". The next step is to open that text file and to copy its complete content to the clipboard.



## Usage

The toolkit is implemented as jupyter notebook which can be run directly in the browser via the webservice https://mybinder.org/.

- View jupyter notebook: [https://nbviewer.org/...](https://nbviewer.org/github/cknoll/sociogram/main?urlpath=/tree/notebooks)
- Run jupyter notebook:  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cknoll/sociogram/main?urlpath=/tree/notebooks).
    - This will start a virtual machine, install all necessary dependencies and run the notebook. To generate graphical results all cells must be executed (choose "run all cells from the menu").






