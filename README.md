NG-LGA-API
==========

API for listing all Local Government Areas in Nigeria from the web of data using Linked Data and PHP


INSTALLATION
===============

- Copy 'getlg.php' into any web accessible directory of choice.
- Enter the location of the file on your browser to get a listing of Local Government Areas in Nigeria (e.g http://example.com/lga/getlg.php).


NOTE
========

Default response format is JSON. To get other types of format, simply append format type to the 'f' query string variable (e.g http://example.com/lga/getlg.php?f=xml). Supported options include:
- json
- xml
- csv
- ttl
- rdf
 
A live demo is running at http://linkedopendatang.com/entity/localgov/getlg.php

