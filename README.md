# Sets_py
"""
Set = colection which is unordered , unindexed. No duplicate Value

"""
from re import U


utensils ={"fork", "spoon", "knif"}
dishes ={"bol","plate","cup","knif"}

# utensils.add("napkin")# to addd item 
# utensils.remove("fork")# to remove item 
# utensils.clear()# all set will delete 
# add one set to in another 
utensils.update(dishes)
dinner_table = utensils.union(dishes)# to add two sets 

# compare two sets 
print(utensils.difference(dishes))

print(utensils.intersection(dishes))# to check common element 

# for x in utensils:
#     print(x)

