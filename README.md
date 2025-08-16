# WK2classpracticepython
practicing python

#1. Using append()
#The append() method adds an item at the end of the list.
numbers=[0, 1, 2, 3, 4]
print("Before Append:", numbers)
#using appned() to add an item
numbers.append(10)

print("After Append:",numbers)
#2. Using extend()
languages = ["Python", "Dart", "Web"]
print("Before Extend:", languages)
#using extend() to add multiple items
languages.extend(["Java", "C++", "JavaScript"]) 
print("After Extend:", languages)
#3. Using insert()
#The insert() method adds an item at a specified index.     
languages = ["Python", "Dart", "Web"]
print("Before Insert:", languages)
languages.insert(1, "Java")
print("After Insert:", languages)
#Access String Items
site_name = "Power Learn Project"   
print(site_name[6])  # Accessing the character at index 6
#4. Using remove()
#The remove() method removes the first occurrence of a specified item.
languages = ["Python", "Dart", "Web", "Java"]
print("Before Remove:", languages)
languages.remove("Dart")
print("After Remove:", languages)  
#5. Using pop()
#The pop() method removes the item at the specified index (or the last item if no index is specified).
languages = ["Python", "Dart", "Web", "Java"]           
print("Before Pop:", languages)
languages.pop(2)  # Removes the item at index 2 
print("After Pop:", languages)
#Access String Items
site_name = "Power Learn Project"   
print(site_name[6])  # Accessing the character at index 6
print(site_name[0])  # Accessing the first character 
print(site_name[5])  # Accessing the character at index 5
#Python Dictionary Data Type
capital_city = {"Kenya": "Nairobi", "Nigeria": "Lagos"}
print(capital_city["Kenya"])  # Accessing the value for the key "Kenya"
print(capital_city["Nigeria"])  # Accessing the value for the key "Nigeria"
#Python Set Data Type
student_ids = {112, 114, 117, 113}
print(student_ids)
print(student_ids)  # Printing the set of student IDs
#Python Numeric Data type
num1 = 55
num2 = 5.3
print(num1)  # Printing the integer number
print(num2)  # Printing the float number
#Python List Data Type

languages = ["Python", "Dart", "Web", 23]
print(languages)  # Printing the list of languages
print(languages[1])  # Accessing the second item in the list
print(languages[1])  # Accessing the second item in the list
#Python Tuple Data Type
products = ('XBox', 499.99, "Habibi", 23)
print(products)  # Printing the tuple of products       
print(products[2])  # Accessing the third item in the tuple
#Python String Data Type
site_name = "Power Learn Project"
print(site_name)  # Printing the string 
print(site_name[6])  # Accessing the character at index 6
#Python Set Data Type           
student_ids = {112, 114, 117, 113}
print(student_ids)  # Printing the set of student IDs
