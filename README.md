# POSTMAN

Large file processing :

I have used python and postgreSQL for this assignment and its working .I tried multiple ways and finally got the lowest time possible .

Script running time between 60 to 70 seconds.

Prerequisites:

1) pip install -r requirements.txt
2)Please change the db username ,password and host .


How to run :

1)python3 main.py
2)provide file path (provide just file name if its on the same path)


Features:

Db creation and all are done as part of the code.
Fast execution.
Minimal human interferance.


Future ideas:

Create a dedicated host or site to upload file so that just they can give link and we can process the file.

***
At advanced stage we can do spark streaming on some path and we can process all the incoming file without triggering the script all the file .
***


DB details :

products table :

name sku(primary key) description

Aggregate table :

name no_of_products

Points to achieve :

all 5 points done
feature 1 done
