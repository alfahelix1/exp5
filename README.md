🎯 1. Aim
To understand the data structure Dictionary in Python, including its creation, manipulation of key-value pairs, and its application in solving real-world programming problems.

🛠️ 2. Functions & Methods Used
The following built-in Python methods and functions were utilized in this study:

print(): Outputs the dictionary or specific values to the console.

type(): Identifies the data type of the object (e.g., <class 'dict'>).

len(): Returns the number of key-value pairs in the dictionary.

.update(): Adds or updates the dictionary with elements from another dictionary object or iterable.

.get(): Returns the value of a specified key without raising an error if the key doesn't exist.

.pop(): Removes the element with the specified key and returns its value.

max(): Used with the key parameter to find the maximum value (highest marks) within the dictionary.

input(): Captures user input for dynamic searching and validation.

📖 3. Theory
A Dictionary in Python is a built-in data type that stores data in key:value pairs. It is:

Ordered: As of Python 3.7, dictionaries maintain the order of insertion.

Changeable: You can change, add, or remove items after the dictionary has been created.

Unique Keys: Dictionaries cannot have two items with the same key. If a duplicate key is provided, the latest value overwrites the previous one.

📋 4. Algorithms (Problem-wise)
🏷️ Program 1: Update Product Price
Goal: Update the value of an existing key in a product dictionary.

Initialize a dictionary with product names and prices.

Define the target product and the new price.

Check if the product exists in the dictionary using the in keyword.

If it exists, assign the new price to that key.

Print the updated dictionary.

🔍 Program 2: Search Student Marks
Goal: Retrieve a value based on user-provided input.

Initialize a dictionary with student names and marks.

Take the student's name as input from the user.

Search for the name in the dictionary keys.

If found, display the marks; otherwise, display a "Not Found" message.

🔐 Program 3: User Login Validation
Goal: Validate credentials against a stored database.

Store usernames and passwords in a dictionary.

Accept username and password inputs from the user.

Validate: Check if the username exists.

If the username exists, compare the entered password with the value stored in the dictionary.

Display "Success" or specific error messages (e.g., "Invalid Password").

🏆 Program 4: Find Highest Scorer
Goal: Identify the key with the maximum value.

Initialize a dictionary with names and marks.

Use the max() function on the dictionary.

Pass marks.get as the key argument to compare values instead of keys.

Store and print the name (key) and the corresponding score.

✅ 5. Conclusion
Through this experiment, I successfully learned how to use dictionaries to store and manage structured data. I practiced essential operations like adding, updating, and removing items, and applied these concepts to create functional programs for searching, validation, and data analysis.
