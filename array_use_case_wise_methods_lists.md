
---

### **Array Creation and Initialization**

- **`array()`**

  - Creates an array.
  - syn: `array(key => value, ...)`

- **`range()`**

  - Creates an array containing a range of elements.
  - - syn: `range(start, end, step)`

- **`array_fill()`**

  - Fills an array with values.
  - syn: `array_fill(start_index, num, value)`

- **`array_fill_keys()`**

  - Fills an array with values, specifying keys.
  - syn: `array_fill_keys(keys, value)`

- **`array_pad()`**
  - Pads an array to a specified length with a value.
  - syn: `array_pad(array, size, value)`

---

### **Array Manipulation**

- **`array_push()`**  
  Pushes one or more elements to the end of an array.

  - syn: `array_push(array, value1, value2, ...)`

- **`array_unshift()`**

  - Prepends one or more elements to the beginning of an array.
  - syn: `array_unshift(array, value1, value2, ...)`

- **`array_pop()`**

  - Pops the last element off an array.
  - syn: `array_pop(array)`

- **`array_shift()`**

  - Shifts the first element off an array.
  - syn: `array_shift(array)`

- **`array_replace()`**

  - Replaces the values of the first array with values from subsequent arrays.
  - syn: `array_replace(array1, array2, ...)`

- **`array_replace_recursive()`**
  - Recursive version of `array_replace()`.
  - syn: `array_replace_recursive(array1, array2, ...)`

---

### **Array Sorting**

- **`sort()`**

  - Sorts an array in ascending order.
  - syn: `sort(array, sort_flags)`

- **`rsort()`**

  - Sorts an array in descending order.
  - syn: `rsort(array, sort_flags)`

- **`asort()`**

  - Sorts an array in ascending order while maintaining key association.
  - syn: `asort(array, sort_flags)`

- **`arsort()`**

  - Sorts an array in descending order while maintaining key association.
  - syn: `arsort(array, sort_flags)`

- **`ksort()`**

  - Sorts an array by key in ascending order.
  - syn: `ksort(array, sort_flags)`

- **`krsort()`**

  - Sorts an array by key in descending order.
  - syn: `krsort(array, sort_flags)`

- **`usort()`**

  - Sorts an array by values using a user-defined comparison function.
  - syn: `usort(array, comparison_function)`

- **`uksort()`**

  - Sorts an array by keys using a user-defined comparison function.
  - syn: `uksort(array, comparison_function)`

- **`uasort()`**

  - Sorts an array by values with a user-defined comparison function, maintaining key association.
  - syn: `uasort(array, comparison_function)`

- **`array_multisort()`**
  - Sorts multiple or multi-dimensional arrays.
  - syn: `array_multisort(array1, array2, ...)`

---

### **Array Keys and Values**

- **`array_keys()`**

  - Returns all the keys of an array.
  - syn: `array_keys(array, search_value, strict)`

- **`array_values()`**

  - Returns all the values of an array.
  - syn: `array_values(array)`

- **`array_flip()`**
  - Exchanges all keys with their associated values.
  - syn: `array_flip(array)`

---

### **Array Counting**

- **`count()`**

  - Counts the number of elements in an array.
  - syn: `count(array, mode)`

- **`sizeof()`**

  - Alias of `count()`.
  - syn: `sizeof(array, mode)`

- **`array_count_values()`**
  - Counts the occurrences of each distinct value in an array.
  - syn: `array_count_values(array)`

---

### **Array Inspection**

- **`is_array()`**

  - Checks if a variable is an array.
  - syn: `is_array(var)`

- **`array_key_exists()`**

  - Checks if a key exists in an array.
  - syn: `array_key_exists(key, array)`

- **`in_array()`**
  - Checks if a value exists in an array.
  - syn: `in_array(value, array, strict)`

---

### **Array Filtering**

- **`array_filter()`**
  - Filters elements of an array using a callback function.
  - syn: `array_filter(array, callback, flag)`

---

### **Array Searching**

- **`array_search()`**

  - Searches for a value in an array and returns its key.
  - syn: `array_search(value, array, strict)`

- **`array_keys()`**

  - Searches and returns keys for a given value.
  - syn: `array_keys(array, search_value, strict)`

- **`array_key_exists()`**
  - Alias of `key_exists()`.
  - syn: `array_key_exists(key, array)`

---

### **Array Mapping and Transformation**

- **`array_map()`**

  - Applies a callback function to the elements of an array.
  - syn: `array_map(callback, array1, array2, ...)`

- **`array_walk()`**

  - Applies a callback function to the elements of an array, including their keys.
  - syn: `array_walk(array, callback)`

- **`array_walk_recursive()`**

  - Recursively applies a callback function to elements of an array.
  - syn: `array_walk_recursive(array, callback)`

- **`array_reduce()`**
  - Iteratively reduces an array to a single value using a callback function.
  - syn: `array_reduce(array, callback, initial)`

---

### **Array Merging and Combining**

- **`array_merge()`**

  - Merges one or more arrays.
  - syn: `array_merge(array1, array2, ...)`

- **`array_merge_recursive()`**

  - Recursively merges arrays.
  - syn: `array_merge_recursive(array1, array2, ...)`

- **`array_combine()`**
  - Combines two arrays: one for keys, the other for values.
  - syn: `array_combine(keys, values)`

---

### **Array Chunking and Splitting**

- **`array_chunk()`**

  - Splits an array into chunks.
  - syn: `array_chunk(array, size, preserve_keys)`

- **`array_slice()`**

  - Extracts a portion of an array.
  - syn: `array_slice(array, offset, length, preserve_keys)`

- **`array_splice()`**
  - Removes and replaces a portion of an array.
  - syn: `array_splice(array, offset, length, replacement)`

---

### **Array Flipping and Reversing**

- **`array_reverse()`**

  - Reverses the order of elements in an array.
  - syn: `array_reverse(array, preserve_keys)`

- **`array_flip()`**
  - Exchanges all keys with their associated values.
  - syn: `array_flip(array)`

---

### **Array Intersecting and Differencing**

- **`array_intersect()`**

  - Computes the intersection of arrays by values.
  - syn: `array_intersect(array1, array2, ...)`

- **`array_intersect_key()`**

  - Computes the intersection of arrays by keys.
  - syn: `array_intersect_key(array1, array2, ...)`

- **`array_intersect_assoc()`**

  - Computes the intersection of arrays by keys and values.
  - syn: `array_intersect_assoc(array1, array2, ...)`

- **`array_diff()`**

  - Computes the difference of arrays by values.
  - syn: `array_diff(array1, array2, ...)`

- **`array_diff_key()`**

  - Computes the difference of arrays by keys.
  - syn: `array_diff_key(array1, array2, ...)`

- **`array_diff_assoc()`**
  - Computes the difference of arrays by keys and values.
  - syn: `array_diff_assoc(array1, array2, ...)`

---

### **Array Utilities**

- **`array_unique()`**

  - Removes duplicate values from an array.
  - syn: `array_unique(array, sort_flags)`

- **`array_column()`**

  - Returns the values from a single column in a multi-dimensional array.
  - syn: `array_column(array, column_key, index_key)`

- **`array_rand()`**

  - Picks one or more random keys from an array.
  - syn: `array_rand(array, num)`

- **`shuffle()`**
  - Shuffles the elements of an array.
  - syn: `shuffle(array)`

---

### **Array Traversing and Access**

- **`current()`**  
  Returns the current element

  - in an array.
  - syn: `current(array)`

- **`next()`**

  - Advances the internal pointer of an array.
  - syn: `next(array)`

- **`prev()`**

  - Moves the internal pointer backward in an array.
  - syn: `prev(array)`

- **`reset()`**

  - Rewinds the internal pointer to the first element of an array.
  - syn: `reset(array)`

- **`end()`**

  - Advances the internal pointer to the last element of an array.
  - syn: `end(array)`

- **`key()`**
  - Returns the current key of an array.
  - syn: `key(array)`

---

### **Array Serialization**

- **`serialize()`**

  - Serializes an array to a storable representation.
  - syn: `serialize(value)`

- **`unserialize()`**

  - Converts a serialized string back to an array.
  - syn: `unserialize(serialized_string)`

- **`json_encode()`**

  - Encodes a PHP array or object into a JSON string.
  - syn: `json_encode(value, options, depth)`

- **`json_decode()`**
  - Decodes a JSON string into a PHP array or object.
  - syn: `json_decode(json, assoc, depth, options)`

---

### **Support Callback**

- **`array_all()`**

  - Checks if all array elements satisfy a callback function.
  - syn: `array_all(array, callback)`

- **`array_any()`**

  - Checks if at least one array element satisfies a callback function.
  - syn: `array_any(array, callback)`

- **`array_filter()`**

  - Filters elements of an array using a callback function.
  - syn: `array_filter(array, callback, flag)`

- **`array_map()`**

  - Applies a callback function to the elements of an array.
  - syn: `array_map(callback, array1, array2, ...)`

- **`array_reduce()`**

  - Iteratively reduces an array to a single value using a callback function.
  - syn: `array_reduce(array, callback, initial)`

- **`array_walk()`**

  - Applies a callback function to the elements of an array, including their keys.
  - syn: `array_walk(array, callback)`

- **`array_walk_recursive()`**

  - Recursively applies a callback function to elements of an array.
  - syn: `array_walk_recursive(array, callback)`

- **`usort()`**

  - Sorts an array by values using a user-defined comparison function.
  - syn: `usort(array, comparison_function)`

- **`uasort()`**

  - Sorts an array by values with a user-defined comparison function, maintaining key association.
  - syn: `uasort(array, comparison_function)`

- **`uksort()`**

  - Sorts an array by keys using a user-defined comparison function.
  - syn: `uksort(array, comparison_function)`

- **`array_replace_recursive()`**

  - Recursive version of `array_replace()`, replacing the values of the first array with values from subsequent arrays.
  - syn: `array_replace_recursive(array1, array2, ...)`

- **`array_intersect_ukey()`**

  - Computes the intersection of arrays by keys using a user-defined comparison function.
  - syn: `array_intersect_ukey(array1, array2, comparison_function)`

- **`array_diff_uassoc()`**

  - Computes the difference of arrays by values and keys using a user-defined comparison function.
  - syn: `array_diff_uassoc(array1, array2, comparison_function)`

- **`array_udiff()`**

  - Computes the difference of arrays by values using a user-defined comparison function.
  - syn: `array_udiff(array1, array2, comparison_function)`

- **`array_udiff_assoc()`**

  - Computes the difference of arrays by keys and values using a user-defined comparison function.
  - syn: `array_udiff_assoc(array1, array2, comparison_function)`

- **`array_udiff_uassoc()`**

  - Computes the difference of arrays by values and keys using a user-defined comparison function.
  - syn: `array_udiff_uassoc(array1, array2, comparison_function)`

- **`array_uintersect()`**

  - Computes the intersection of arrays by values using a user-defined comparison function.
  - syn: `array_uintersect(array1, array2, comparison_function)`

- **`array_uintersect_assoc()`**

  - Computes the intersection of arrays by keys and values using a user-defined comparison function.
  - syn: `array_uintersect_assoc(array1, array2, comparison_function)`

- **`array_uintersect_uassoc()`**
  - Computes the intersection of arrays by values and keys using a user-defined comparison function.
  - syn: `array_uintersect_uassoc(array1, array2, comparison_function)`

---
