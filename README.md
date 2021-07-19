# nitish_research

This repo will contain the codesss for parsing and displaying HealthKit XML data using python and R

# Installation
1. Clone main repo:
git clone https://github.com/ajwr/nitish_research
2. Clone included submodule:
git clone --recurse-submodules -j8 https://github.com/stefanluyten/HealthKitExportParser/


# Usage
1. Use applehealthdata.py to parser export.xml to a CSV file. Load into excel/SPSS/etc for graphing and analysis
1.1 - 'mkdir csv_files' 
1.2 - 'mv *.csv csv_files'

**OR**

2. Use healthkit_results in R studio to generate an html file of results. NOTE: Be sure you changed the path on line 26 to your export.xml

3. Enjoy... :)

