# week-2-python-assignment

# Step 1: Create an empty list
my_list = []

# Step 2: Append elements to my_list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Step 3: Insert 15 at the second position
my_list.insert(1, 15)

# Step 4: Extend my_list with another list [50, 60, 70]
my_list.extend([50, 60, 70])

# Step 5: Remove the last element
my_list.pop()

# Step 6: Sort my_list in ascending order
my_list.sort()

# Step 7: Find and print the index of 30
index_30 = my_list.index(30)
print("Index of 30:", index_30)

# Print the final list for reference
print("Final list:", my_list)

Index of 30: 3
Final list: [10, 15, 20, 30, 40, 50, 60]

