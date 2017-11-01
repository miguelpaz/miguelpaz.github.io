---
layout: post
title: Checklist to work with data and avoid mistakes
tags:
- Courses
- Data Journalism
- Tutorials
- Tip-sheets
- Resources
---


*Summarized by Miguel Paz from ProPublica’s [Guide to bulletproofing your data](https://github.com/propublica/guides/blob/master/data-bulletproofing.md) and [The Quartz guide to bad data](https://github.com/Quartz/bad-data-guide). For more advice in detail, please go to the sources of this tip-sheet.*


### ☑  Never touch the original dataset

- Never work in the original dataset. Save it, create a backup and make a copy of the file to work on it. If it's a workbook (Excel file) or Google Spreadsheet or a .CSV or any other file format, follow the same principles. 

### ☑  Add important notes to the document with information about the data

- Add a worksheet in the Excel file you are working on and include there all the important notes about the data that you and your editor need to know. Things like: Title of the original dataset; name of the file, description, source/s of the data (organization or person that is the author or publisher and links), method of collection, area and time period covered, date and frequency of release, where is the record layout or codebook; data format (text, numbers, currency); missing values, data quality of the original, etc. Also, who is working with this data in your team and who is the editor.

### ☑  Keep a data log or data diary

- Create a document (a Word document, a spreadsheet, comments in the Excel workbook, you choose what you prefer) and write down all the steps you have taken while working with the data. You must do this for two main reasons:

1. If you make a mistake and want to trace back the error, your notes in the data diary will help you find it. 

2. Your editor and expert sources will be able to check your work and follow all the steps you took to get to your results.

- This is useful for projects of all sizes because memory is fragile. 

### ☑  Choose a naming convention for documents and stick to it

- ALWAYS name files with lowercase and NEVER use spaces between words. Instead use underscore if you want to separate_words_in_a_file_name. 

- For field names you can use uppercase and lowercase or all CAPS but you must still use underscore as word separator. 
- Decide how you are going to name files, datasets and where you are going to store everything. Stick to that nomenclature.

- Decide how you are going to name new versions of the file you are working on.

Example: datasetname_month_day_year.

- If you are working in a team, everyone should agree on this and abide by the agreement.

- Your newsroom might already have a defined naming convention. Specially for documents that are published in your newsroom PANDA system (you can ask James Neff and Dylan Purcell about it).

### ☑  When you access or request data, always get the methodology

- Get the methodology. If they won’t give it to you, that’s a red flag.
- How was the data collected? Manually, automatic measurements (e.g. weather data), surveys (census data), records of decisions (budget data), ongoing transactions (spending data), aggregation of many records (crime data), etc.

- Who is the author or publisher?

- Description?

- Area and time period covered, date and frequency of release? 

- Where is the record layout or codebook? 

- Are there any caveats? Missing values? Margin of error? 

- How big is the sample of the population? Very important in surveys.

- Beware of nonscientific methods: Web surveys, man on the street or other self-selection.


### ☑  Check data with experts and colleagues

- Seek experts in the field that can review the data and your results. Statisticians and academics that work with data, can be a great resource for double checking your work. 

- Compare the data you got with other similar datasets.

- If something looks weird or too good to be true, there is a chance there is a mistake. Talk with experts.

### ☑  Check Spelling

- Always check if all entity names are spelled correctly and in the same way.

Example: New York, new york, newyork, nyork, NY, NYC, New York City, NY City, City of New York, Philadelphia, philadelphia, Philladellphia, Philly, PHILADELPHIA, City of Philadelphia.
- Make sure all states/cities/counties are included. Check the range of fields. 
- In Excel use "Sort" to sort alphabetically in every key field. You can do so by sorting ascending or descending (A to Z or Z to A). Same thing with numerical values.

### ☑  Check for missing data or blank fields

- Are they real values, or did something happen in the data entry and data collection or importing process?

You should find out why that happens.

### ☑  Check formats of values

- Units and currency. If something looks weird find out which measurement unit is used in the dataset you are working on.

- Numerical data and decimals. 

- Date formats

### ☑  Your Excel file has 65,536 rows?

- This is not a problem with newer versions of Excel (2013…) that support up to 1,048,576 rows in a Worksheet. Older versions supported a maximum of 65,536 rows. If you get a Excel spreadsheet with 65,536 rows there is a big chance that the dataset is incomplete. If you hit the 65,536 issue, check your sources and ask about this.

### ☑  Totals differ from what a public official say?

- Imagine you have a dataset with a full list of incidents of police use-of-force. You open it up and discover it has 2,467 rows. But at the same time, the chief of police said in an interview that the reported incidents are less than 1,500. This doesn't match your dataset. These sorts of discrepancies between published statistics and raw data can be a very great source of leads. Often the answer will be simple. For instance, the data you were given may not cover the same time period he was speaking about. But sometimes you'll catch them in a lie. Either way, you should make sure the published numbers match the totals for the data you're given.

### ☑  Spreadsheet has dates in 1900, 1904, 1969, or 1970?

- Excel's default date from which it counts all other dates is January 1st, 1900, unless you're using Excel on a Mac, in which case it's January 1st, 1904. There are a variety of ways in which data in Excel can be entered or calculated incorrectly and end up as one of these two dates. If you spot them in your data, it's probably an issue. Many databases and applications will often generate a date of 1970-01-01T00:00:00Z or 1969-12-31T23:59:59Z which is the Unix epoch for timestamps. In other words this is what happens when a system tries to display an empty value or a 0 value as a date.

### ☑  Text has been converted to numbers?

- Not all numerals are numbers. For instance, the US Census Bureau uses "FIPS codes" to identify every place in the United States. These codes are of various lengths and are numeric. However, they are not numbers. 037 is the FIPS code for Los Angeles County. It is not the number 37. The numerals 37 are, however, a valid FIPS code: for North Carolina. 
- Excel and other spreadsheets will often make the mistake of assuming numerals are numbers and stripping the leading zeros. Watch out for data where this has happened before it was given to you.

### ☑  Numbers have been stored as text?

- When working with spreadsheets, numbers may be stored as text with unwanted formatting. This often happens when a spreadsheet is optimized for presenting data rather than making it available for re-use. For example, instead of representing a million dollars with the number "1000000" a cell might contain the string "1,000,000" or "1 000 000" or "USD 1,000,000" with the formatting of commas, units and spaces entered as characters. Excel can take care of some simple cases with built-in functions in the Format options, but you'll often need to use formulas to strip out characters until cells are clean enough to be recognized as numbers. Good practice is to store numbers without formatting and to include supporting information in column names or metadata.

