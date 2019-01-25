# Miashs project : Moteur de recherche de bibiothèque
 
This project is an attempt to index Gutenberg library in an Elasticsearch DB.

Inspired by https://github.com/guoqiao/gutenberg which is an RDF Parser to retrieve metadata of ebooks.

## Indexing :
The python library parse the RDF files 'gutenberg.py', retrieves the metadata including the url of the ebook, then it scrapes the url and indexes the result in Elasticsearch.

## Searching :
The gutt.py queries the RESTful API and takes the term searched as a parameter then processes a json result.

## Displaying :
display_response.php is responsible of displaying the json response nicely 


