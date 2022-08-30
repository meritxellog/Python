## Lists

`list = ["a", "b", "c", "d"]`

**Access list elements:**
- `list[0]` results in `a`.
- `list[1:3]` results in `["b", "c", "d"]`.

**Editing list elements:**
- `list[0] = "1"; print(list)` results in `["1", "b", "c", "d"]`

**Deleting list elements:**
- `del list[0]; print(list)` results in `["b", "c", "d"]`.

**Operations:**
|       Python Expression      |            Results           |
|:----------------------------:|:----------------------------:|
|        len([1, 2, 3])        |               3              |
|     [1, 2, 3] + [4, 5, 6]    |      [1, 2, 3, 4, 5, 6]      |
|           ['a'] * 4          |     ['a', 'a', 'a', 'a']     |   
|        3 in [1, 2, 3]        |             True             |
| for x in [1, 2, 3]: print x, |             1 2 3            |


| Python Expression |      Results      |           Description          |
|:-----------------:|:-----------------:|:------------------------------:|
|        list[2]       |       "c"       |      Offsets start at zero     |
|       list[-2]       |        "b"      | Negative: count from the right |
|       list[1:]       | ["b", "c", "d"] |    Slicing fetches sections    |

**Built-in functions:**
- `cmp(list1, list2)`
Compares elements of both lists.

- `len(list)`
Gives the total length of the list.

- `max(list)`
Returns item from the list with max value.

-	`min(list)`
Returns item from the list with min value.

-	`list(seq)`
Converts a tuple into list.

**Built-in methods:**

- `list.append(obj)`
Appends object obj to list

-	`list.count(obj)`
Returns count of how many times obj occurs in list

-	`list.extend(seq)`
Appends the contents of seq to list

-	`list.index(obj)`
Returns the lowest index in list that obj appears

-	`list.insert(index, obj)`
Inserts object obj into list at offset index

-	`list.pop(obj=list[-1])`
Removes and returns last object or obj from list

-	`list.remove(obj)`
Removes object obj from list

-	`list.reverse()`
Reverses objects of list in place

-	`list.sort([func])`
Sorts objects of list, use compare func if given
