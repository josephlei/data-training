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

### Why do formats matter?
- They enable or hinder machine readability
- They affect file size, which affects file transfer

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