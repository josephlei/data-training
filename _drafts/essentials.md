---
layout: draft
title: Preparing Data for Publication
date: 2017-03-14
permalink: /101/
---

Data is stored throughout state government in many different formats across many different systems. To upload data to the California Open Data portal, you have to save and upload your datasets in a particular format to ensure that they are properly stored and presented by the portal. 

This page continues by describing the format that is needed for the upload to [data.ca.gov](https://data.ca.gov/).

### Government data is often stored in a wide-range formats including, but not limited to:
- Excel
- CSV/TXT (delimited or positional raw text)
- Databases (access, sql server, teradata, oracle)
- PDF
- SAS (.sas7bdat)
- XML
- JSON

To upload data to the California Open Data Portal **all datasets must be in a flat CSV file format.**

### Header Row

The first row of your dataset must be a row that contains column names.

### CSV Files

The California Open Data portal only accepts data files that are uploaded with the “.csv” extension. 

File extensions do not affect the underlying data. They are used to tell operating systems what ‘default’ program with which to open a file. 

This means that a “csv” comma separated file is not **necessarily** separated with commas. 

### Delimiters

Values in flat datasets are [separated by delimiters](https://en.wikipedia.org/wiki/Delimiter-separated_values).

The California Open Data Portal can handle four delimiters: 
* Comma: ,
* Semicolon: ;
* Pipe: \|
* Plus: +

Tabs are NOT a delimiter that can be used on data.ca.gov. Your files will not properly display with a tab delimiter, so please reformat your file to one of the four accepted delimiters. 

### Flat Files

Currently CA is focusing on loading flat file data before moving on to hierarchical or geo-spatial data. 
A flat file is one with no internal hierarchy. Excel is NOT a flat file format.
Hierarchical data is a file with a internal hierarchy/structure. Common hierarchical data examples include json and xml which are commonly used to exchange data over web protocols. 

### Encoding
Computers encode characters (i.e. “a”, “A”, “3”, “$”) in different formats. Any particular character can be encoded in many different ways, depending on which encoding is used to read or write them. [For a very detailed guide on encoding click here](http://kunststube.net/encoding/).

To ensure that people who download your dataset can properly understand the characters when they download it, we require that your file be encoded in [UTF-8](https://en.wikipedia.org/wiki/UTF-8).
This is the standard encoding for most systems and if you are unsure about the encoding of your file, check with the California Department of Technology’s Open Data Team.

### Conclusion

This section of the guide is intended to make sure the data in your dataset is ready for upload. It is the minimum required to get your data ready for publication. Having said that, we would also suggest using resources like [Propublica guide to bullet proofing data](https://github.com/propublica/guides/blob/master/data-bulletproofing.md)