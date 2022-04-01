# Olympic games

Demonstrating use of public and private S3 buckets, along with READ_CSV, and
RQL select/union queries.

The folder contains the following files;

- README.md, This file
- code.rql, the file containing the RQL specifications
- athele.yml, specifies endpoint for athlete medals
- country-medals.yml, specifies endpoint for country medals, and
- country-gold-medals.yml, specifies endpoint for all country gold
  medals.

In code.rql, we can inspect the 'READ_CSV' RQL command that reads data from
csv files that are contained in s3 buckets. 

From an openly accessible CSV file, we declare the variable
'country_codes' that we then join with the S3 data to generate our endpoints
per the declarations that follow in the file.
