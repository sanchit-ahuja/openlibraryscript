 
 Basically a barebones script to fetch book details from GoodReads (Name, Author and Book Image url) and push those into openlibrary database.

#### Libraries used
1. openlibrary client
2. requests
3. xml ETree

To run the script make sure it's executable and the above libraries are installed.
##### To make the script executable run ```chmod +x script_add.py```
Then simply run the script ```python3 script_add.py [isbn_id]```

#### To Do
1. The script is quite slow. This is because it is fetching data from GoodReads first then reading the xml response and then pushing the data back to the openlibrary databases. Need to think of ways to make it a bit faster.
2. Integrate it with the openlibrary bots repository. 
