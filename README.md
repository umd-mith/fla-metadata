This repository is intended to demonstrate how HathiTrust collections can be shared using [CSV on the Web](http://www.w3.org/2013/csvw/wiki/Main_Page). It is a work product of MITH's [Workset Creation for Scholarly Analysis](http://mith.umd.edu/research/project/workset-creation-for-scholarly-analysis-project/) project in collaboration with the HathiTrust Research Center.

The CSV and CSVW files were generated with [hathitables](http://github.com/umd-mith/hathitables). 

    % pip install hathitables
    % hathitables.py 1316980598 > 1316980598.csv
    % hathitables --metadata 1316980598 > 1316980598.csv-metadata.json


