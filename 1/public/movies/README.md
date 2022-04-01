# Star Trek movies popularity from TMDB

Demonstrating use of 'secret' datasource, which is used to store the TMDB
'api_key' of our account in order to query the API.

The folder contains the following files;

- README.md, This file
- code.rql, the file containing the RQL specifications
- star-treks.yml, specifies endpoint for displaying results after a TMDB query

In code.rql, we can inspect the 'secret('tmdb_api_key')' command that enables us
to access a privately stored secret key and use it on runtime to access an API resource

