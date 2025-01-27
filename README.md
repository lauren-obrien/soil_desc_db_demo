# About this repository

This repo contains some very basic implementations of the data model depicted in the New Zealand Soil Description Manual (2024 draft). Included:

- [DuckDB](https://duckdb.org/) 
  - nzsdm_demo_db_duckdb.qmd  
  - template_nzsd.duckdb
- [SQLite](https://www.sqlite.org)  
  - nzsdm_demo_db_sqlite.qmd
  - template_nzsd_sqlite.db
- Excel 
  - test_db_layout_withdata.xlsx

Note that these are not complete products; they exist only to provide interactive examples of one way the manual can be used in practice. The models contain no security, user management or change tracking functionality, and no facility for handling ancillary data like photographs or laboratory results. In the case of the Excel model, only basic data validation controls are in place. The models will also change in response to the results of the NZSD draft review. Do not use these in a production environment.
