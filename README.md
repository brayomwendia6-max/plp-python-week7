# PLP Python Week 7 - Files and Report Builder

## Files
- my_notes.py - Writes 3 notes to a file, appends a 4th note without erasing, then reads and counts the lines.
- my_notes.txt - The file created by my_notes.py with 4 notes.
- hubs.csv - Data with name, hub, and score for 5 learners.
- report_builder.py - Reads hubs.csv, counts total/passed/failed, calculates average score, and writes report.txt with error handling if hubs.csv is missing.
- report.txt - The generated report with total learners, passed, failed, and average score.
- README.md - Explains the project and answers the question below.

## What would happen if you changed "a" to "w" in Question 1?

If you changed "a" to "w", the file would be erased and overwritten instead of appended to. The first three notes would be deleted and only "I added this later" would remain, so the total lines would be 1 instead of 4.
