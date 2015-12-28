# Storing-assert-folder-XML-data-to-sqlitedb
Storing android assert folder's XML data into the apppliction's local sqlite database

Descriptions
============

Basic idea is dynamically access XML file and store it into the sqlite database without doing any hardcode work. For that I have handled recusrive method.

Recursive function - XML file's root node may contains any number of child nodes and its values. To access all nodes from root to inner most child nodes and its values, here I have followed recursion method. This process will be helpful on when ever your XML file content has been changed or modified, dynamically this method will traverse through all nodes and values and will store in the local database.
