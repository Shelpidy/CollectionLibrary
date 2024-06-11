Library Name
License: MIT

Library Name is a lightweight Python library for storing and retrieving data locally in a collection-like format. It is inspired by NoSQL databases like MongoDB and cloud-based services like Firebase Firestore.

Installation
Use the package manager pip to install Library Name.

bash
Copy code
pip install library-name
## Usage
python
Copy code
```py
from library_name import Collection

# Create a new collection
my_collection = Collection('my_collection')

# Add some data to the collection
my_collection.insert({'name': 'John', 'age': 25})
my_collection.insert({'name': 'Jane', 'age': 30})

# Retrieve data from the collection
result = my_collection.find({'age': {'$gt': 25}})
print(result)

# Print the data in the collection as a table in the terminal
my_collection.print_table()
```
