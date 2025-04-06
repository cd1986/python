```python
retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}
```
## 🟢 Easy (Level 1)

1. How do you get all the keys from a dictionary? `(Use .keys())`
retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}

print(type(retail_inventory))
print("retail_inventory : ", retail_inventory.keys())



2. How do you get all the values from a dictionary? `(Use .values())
retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}

print(type(retail_inventory))
print("retail_inventory : ", retail_inventory.values())



3. How do you retrieve the value for a specific key safely? `(Use .get(key))`
retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}

print(type(retail_inventory))
print("retail_inventory : ", retail_inventory.get("Electronics"))



   
4. How do you check if a key exists in a dictionary? `(Use in)`


retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}

# exist_check_list = ['laptop','Tablet','Fan','Jeans','Microwave']


# for exist_check_list in exist_check_list


if 'name' in retail_inventory:
    print("exitst")
else:
    print("does not exist")



5. How do you remove a key and return its value? `(Use .pop(key))`
retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}


6. How do you copy a dictionary? `(Use .copy())`
retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}

copy_dict = retail_inventory.copy()
print(copy_dict)


7. How do you remove all key-value pairs from a dictionary? `(Use .clear())`
retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}

clear_retail_inventory = retail_inventory.clear()

print(clear_retail_inventory)


# 8. How do you add or update a value for a key? `(Use .update({key: value}))`
retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}

retail_inventory.update({"Home Appliances": {
        "Juicer": [8500, 15, "Preethi"]})

print(retail_inventory.itemds())

9. How do you retrieve both keys and values? `(Use .items())`
retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"]
    }
}


print(retail_inventory.items())



# 10. How do you create an empty dictionary? `(Use {} or dict())`


empty_dict ={}

print(empty_dict)



---

## 🟡 Medium (Level 2)

11. Use `.setdefault()` to assign a default value to a missing key.
# Use .setdefault() to assign a default value to a missing key.


retail_inventory = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    },
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    },
    "Home Appliances": {
        "Microwave": [8500, 15, "LG"],
        "Vacuum Cleaner": [7000, 10, "Philips"],
        "Refrigerator": [30000, 8, "Samsung"],
        #"Juicer":[]
    },
    "Interiors":{}
}

retail_inventory.setdefault("Hello")
print(retail_inventory)




12. Use `.update()` to merge two dictionaries. 
retail_inventory_1 = {
    "Electronics": {
        "Laptop": [55000, 30, "Dell"],
        "Mobile": [25000, 50, "Samsung"],
        "Tablet": [18000, 20, "Lenovo"],
        "Smart Watch": [7999, 40, "Noise"]
    }}
    
retail_inventory_2 = { 
    "Apparel": {
        "T-Shirt": [499, 100, "H&M"],
        "Jeans": [1199, 60, "Levi's"],
        "Jacket": [2499, 25, "Puma"]
    }}

retail_inventory_1.update(retail_inventory_2)

print(retail_inventory_1)



13. Use `.get()` with a default return value if key is not found.
retail_inventory_1 = {
    "Electronics": {
    "Laptop": [55000, 30, "Dell"],
    "Mobile": [25000, 50, "Samsung"],
    "Tablet": [18000, 20, "Lenovo"],
    "Smart Watch": [7999, 40, "Noise"]
}}
print(retail_inventory_1.get("Fablet", "Currently no Fablet available"))



14. What’s the difference between `.pop()` and `.popitem()`? Try both.
my_dict = {'name': 'Alice', 'age': 25, 'city': 'New York'}
item = my_dict.popitem()
print(item)        # Output: ('city', 'New York')
print(my_dict)     # {'name': 'Alice', 'age': 25}
('city', 'New York')
{'name': 'Alice', 'age': 25}


my_dict = {'name': 'Alice', 'age': 25, 'city': 'New York'}
age = my_dict.pop('age')
print(age)         # Output: 25
print(my_dict)     # {'name': 'Alice', 'city': 'New York'}
25
{'name': 'Alice', 'city': 'New York'}


 
15. Use `del` to remove a key from a dictionary.
person = {
    'name': 'Alice',
    'age': 25,
    'city': 'New York'
}

# Remove the 'age' key
del person['age']

print(person)
# Output: {'name': 'Alice', 'city': 'New York'}


16. Get the number of keys in a dictionary. `(Use len())`
person = {
    'name': 'Alice',
    'age': 25,
    'city': 'New York'
}

print("length of dictionary person ", len(person))
# Output: {'name': 'Alice', 'city': 'New York'}
    
17. Convert a list of tuples into a dictionary. `(Use dict() constructor)`  
person = (('name','Alice'),('age',25),('city','New York'))

# converting dic person to tuple
person_dict=dict(person)


print("length of dictionary person ", len(person))
print(person)
# Output: {'name': 'Alice', 'city': 'New York'}


18. Create a dictionary from two lists: one of keys and one of values. `(Use zip() and dict())`  
keys = ['name', 'age', 'city']
values = ['Alice', 25, 'New York']

# Combine keys and values using zip, then convert to dictionary
person = dict(zip(keys, values))
print(person)


19. Check if two dictionaries have the same keys. `(Use .keys() and ==)`  
dict_1 = {'name':'ravi'}
dict_2 = {'age':30}

dict_3 = {'name':'ravi'}
dict_4 = {'name':'ravi'}


print('checking if both dictionaries are equal or not: ', dict_1 == dict_2)
print('checking if both dictionaries are equal or not: ', dict_3 == dict_4)


20. Check if a dictionary is empty. `(Use not or len())`
dict_1 = {'name':'ravi'}
dict_2 = {}

print('checking if dictionary empty or not: ', len(dict_1) != 0)
print('checking if dictionary empty or not: ', len(dict_2) != 0)


---

## 🔴 Complex (Level 3 — Still no loops)

21. Get a list of all unique values using `set()` and `.values()`.  
person = {
    'name': 'Alice',
    'city': 'New York',
    'nickname': 'Alice',
    'country': 'USA'
}

# Get unique values
unique_values = set(person.values())
print(unique_values)


22. Create a nested dictionary using dictionary literals.  
company = {
    'emp1': {'name': 'John', 'role': 'Engineer'},
    'emp2': {'name': 'Emma', 'role': 'Designer'},
    'emp3': {'name': 'Liam', 'role': 'Manager'}
}

print(company)


23. Merge 3 dictionaries using chained `.update()`.  
company_1 = {'emp1': {'name': 'John', 'role': 'Engineer'}}
company_2 = {'emp2': {'name': 'Emma', 'role': 'Designer'}}
company_3 = {'emp3': {'name': 'Liam', 'role': 'Manager'}}

# Merge all into one dictionary
all_company_employees = {}
all_company_employees.update(company_1)
all_company_employees.update(company_2)
all_company_employees.update(company_3)
print(all_company_employees)


24. Use `.fromkeys()` to create a dictionary with default values.  
subjects = ['math', 'science', 'english']
default_score = 0
scores = dict.fromkeys(subjects, default_score)
print(scores)


25. Use `.get()` to avoid a `KeyError` while accessing a deeply nested dictionary.  


26. Copy a dictionary and modify the copy (check original doesn’t change).  


27. Extract only the keys from a dictionary where the value is a specific type (e.g., list).  

28. Convert a flat dictionary to a string using `str()` or `json.dumps()`.  

29. Check if a dictionary has all keys from a given list using `all()` and `in`.  


30. Use `max()` and `min()` to find keys or values with highest/lowest value.
