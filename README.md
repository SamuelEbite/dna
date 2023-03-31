# DNA Analysis Tool

This Python script is designed to analyze a DNA sequence and compare it to a database of known DNA profiles to identify potential matches. The script takes two input files: a CSV file containing the database of known profiles, and a text file containing the DNA sequence to be analyzed.

Prerequisites

This script requires Python 3.x and the csv module to be installed.

Usage

To use the script, run the following command in the terminal:

kotlin
Copy code
python dna.py data.csv sequence.txt
Make sure to replace data.csv and sequence.txt with the correct file paths for your system.

How it works

The script works by first reading the database file into a list of dictionaries, with each dictionary representing a single DNA profile. The script then reads the DNA sequence file into a string variable.

Next, the script searches the DNA sequence for the longest match of each STR (short tandem repeat) found in the database. The STRs are identified by the column headers in the first row of the database file.

After identifying the longest match for each STR, the script checks the database for any profiles that match all of the STRs in the DNA sequence. If a match is found, the script prints the name of the person with the matching profile. If no match is found, the script prints "No match".

Contact

For questions or issues with the script, please contact Ebite Samuel at ebitesamuel01@gmail.com.
