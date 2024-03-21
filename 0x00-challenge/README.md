# Task 0
- check for the multiples of 3 and 5 first before checking other conditions.

# Task 1
- changed parseInt(process.argv[2], 16) to parseInt(process.argv[2], 10) to ensure the size argument is parsed as a decimal number, as intended.

# Task 4
- Properly updated the prev and next pointers of neighboring nodes when deleting a node in the delete_dnodeint_at_index function

# Task 2
- Using i - 1 would actually insert the new element one position before the intended position, leading to incorrect sorting. So, I corrected the index used for insertion to i instead of i - 1 meaning that i represents the position where the new element should be inserted.
