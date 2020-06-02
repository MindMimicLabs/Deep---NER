# Deep Named Entity Recognition - Part of Speech  

The following repo provides a deep NER model to identify POS from subtitles text samples. 

# Code 

(1) data.processing.r - This script will process the gz file of subtitles which can be downloaded from http://opus.nlpl.eu/OpenSubtitles.php and provide a csv data file for further modeling stored in the csv folder. 

(2) dner.py - This script will train a deep NER model on the finaldf.csv, attempting to accurately idenfity POS from subtitles. 
