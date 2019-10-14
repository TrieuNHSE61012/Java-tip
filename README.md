# Find index of array
--------------------
Case 1: Nornmal: Linear Search

Case 2: Array has been sorted: Binary Search


# Copy Array
-----------
1. Using Clone(): newArray = oldArray.Clone()
2. Using System.arraycopy(): public static void arraycopy(Object src, int srcPos, Object dest, 
                             int destPos, int length)

--> System.arraycopy() is faster than clone() as it uses Java Native Interface
