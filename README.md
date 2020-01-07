# large_json_file_import_elasticsearch_python
A basic code to read and insert large json file into elasticsearch database using python api for elasticsearch

The issue with elasticsearch is due to JVM heap size limit, you cannot directly import large json files into the database, hence some workaround is to be found or even if you simply want to import json file directly into elasticsearch

Also, there are situations where the json file is in GBs exceeding the physical RAM on your device and hence it is not possible to open the file at once, so in those situations these code will help.

NOTE: Remove comma and [ ] from the json file so each line contains a stand-alone json record { ... }
ie. each line is a json record in itself (with no commas separating two lines/records)

This jupyter notebook snippet is a solution to the above problems

Sample usage mentioned in the code itself (run inside jupyter notebook) 
