# nitish_research

This repo will contain the codesss for parsing and displaying HealthKit XML data using python and R

# Installation
1. Clone main repo:
git clone https://github.com/ajwr/vitish_research
2. Clone included submodule:
git clone --recurse-submodules -j8 https://github.com/stefanluyten/HealthKitExportParser/


# Usage
1. Use applehealthdata.py to parser export.xml to a CSV file
1.1 - 'mkdir csv_files' 
1.2 - 'mv *.csv csv_files'
2. Feed CSV files into apple_health_load_analysis_R.r
3. Enjoy... :)

