---
layout: draft
title: Data Essentials (101)
date: 2017-01-26
permalink: /101/
---

### Government data is commonly stored in these formats:
- Excel
- CSV/TXT (delimited or positional raw text)
- Databases (access, sql server, teradata, oracle)
- PDF
- SAS (.sas7bdat)
- XML
- JSON

### Check data to see how it looks in the portal (tables, charts, graphs)

Once you are satisfied with your table and metadata, change draft status to "needs review," which does not yet publish it to the public site. You will be able to see whether the portal is correctly rendering your tables, charts and graphs. 

### Updating Your Data Table

If your data table needs a full replace or major append (i.e. change) after you’ve published, you can update the new dataset in the portal and mark it as "needs review" for your department data coordinator to review. 

If you plan to make any changes, please let us know so that we can keep track of your recent updates. For frequent updates to data tables (but no other edits) it is recommended that you request Publisher permissions from the Portal Administrator.

### Data FAQs
- File extensions (**csv, txt, xlsx**)
  - Don't affect the underlying data
  - Used to tell operating systems what 'default' program to open a file with
  - Can make "batch" operations on groups of files easier
  - This means that a "csv" comma separated file is not **necessarily** separated with commas
- "Flat" files
  - A file with no *internal hierarchy*
  - Excel is NOT a flat file format
- Hierarchical data
  - A file with a internal hierarchy/structure
  - Common examples include **json** and **xml** which are commonly used to exchange data over web protocols