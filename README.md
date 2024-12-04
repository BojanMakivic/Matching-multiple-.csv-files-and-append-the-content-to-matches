# Matching-multiple-.csv-files-and-append-the-content-to-matches
The goal is to match multiple .csv files based on a specific column condition and append the matched rows from the secondary .csv files to a primary .csv file.
1. Primary File: A central .csv file contains data with a unique identifier column (e.g., locName).
2. Secondary Files: Other .csv files need to be matched with the primary file based on the locName column.

Process:
For each secondary .csv file:
1. Identify rows in the secondary file where the locName column matches the corresponding value in the primary file.
2. Append all content from the matched row in the secondary file to the respective row in the primary file.
If, for instance, a row in the primary file has a locName value "Event" and a secondary file also contains a row with locName as "Event," the entire content of that matched row from the secondary file will be merged with the primary file's row.

Output: A single consolidated .csv file is created and exported, containing data from the primary file with additional content appended from the secondary files based on matching rows.
