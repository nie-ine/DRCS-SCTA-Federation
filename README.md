# DRCS-SCTA-Federation
Just a set of useful queries for data federation/interoperability between drcs and scta. 

## Run

### over the ui

* Navigate to http://fuseki.nie-ine.ch/dataset.html?tab=query&ds=/lombardus and login with your credentials
* Copy & paste a query and run it

### via http post

Run it via http post with the following parameters:

*Server:*
* http://fuseki.nie-ine.ch/lombardus/query

*Headers*
* Content-Type: application/sparql-query
* Accept: application/sparql-results+json

*Body:*
[your query text]
