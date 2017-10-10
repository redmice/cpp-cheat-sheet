# Associative containers (C++ 11)

|                 |                  | set           | multiset      | map           | multimap      | unordered_set    | unordered_multiset  | unordered_map    | unordered_multimap  |
|-----------------|------------------|---------------|---------------|---------------|---------------|------------------|---------------------|------------------|---------------------|
| Headers         |                  | \<set>         |               | \<map>         |               | \<unordered_set>  |                     | \<unordered_map>  |                     |
|                 | constructor      | set           | multiset      | map           | multimap      | unordered_set    | unordered_multiset  | unordered_map    | unordered_multimap  |
|                 | destructor       | ~set          | ~multiset     | ~map          | ~multimap     | ~unordered_set   | ~unordered_multiset | ~unordered_map   | ~unordered_multimap |
|                 | assignment       | operator=     | operator=     | operator=     | operator=     | operator=        | operator=           | operator=        | operator=           |
| iterators       | begin            | begin         | begin         | begin         | begin         | begin            | begin               | begin            | begin               |
|                 | end              | end           | end           | end           | end           | end              | end                 | end              | end                 |
|                 | rbegin           | rbegin        | rbegin        | rbegin        | rbegin        |                  |                     |                  |                     |
|                 | rend             | rend          | rend          | rend          | rend          |                  |                     |                  |                     |
| const iterators | cbegin           | cbegin        | cbegin        | cbegin        | cbegin        | cbegin           | cbegin              | cbegin           | cbegin              |
|                 | cend             | cend          | cend          | cend          | cend          | cend             | cend                | cend             | cend                |
|                 | crbegin          | crbegin       | crbegin       | crbegin       | crbegin       |                  |                     |                  |                     |
|                 | crend            | crend         | crend         | crend         | crend         |                  |                     |                  |                     |
| capacity        | size             | size          | size          | size          | size          | size             | size                | size             | size                |
|                 | max_size         | max_size      | max_size      | max_size      | max_size      | max_size         | max_size            | max_size         | max_size            |
|                 | empty            | empty         | empty         | empty         | empty         | empty            | empty               | empty            | empty               |
|                 | reserve          |               |               |               |               | reserve          | reserve             | reserve          | reserve             |
| element access  | at               |               |               | at            |               |                  |                     | at               |                     |
|                 | operator[]       |               |               | operator[]    |               |                  |                     | operator[]       |                     |
| modifiers       | emplace          | emplace       | emplace       | emplace       | emplace       | emplace          | emplace             | emplace          | emplace             |
|                 | emplace_hint     | emplace_hint  | emplace_hint  | emplace_hint  | emplace_hint  | emplace_hint     | emplace_hint        | emplace_hint     | emplace_hint        |
|                 | insert           | insert        | insert        | insert        | insert        | insert           | insert              | insert           | insert              |
|                 | erase            | erase         | erase         | erase         | erase         | erase            | erase               | erase            | erase               |
|                 | clear            | clear         | clear         | clear         | clear         | clear            | clear               | clear            | clear               |
|                 | swap             | swap          | swap          | swap          | swap          | swap             | swap                | swap             | swap                |
| operations      | count            | count         | count         | count         | count         | count            | count               | count            | count               |
|                 | find             | find          | find          | find          | find          | find             | find                | find             | find                |
|                 | equal_range      | equal_range   | equal_range   | equal_range   | equal_range   | equal_range      | equal_range         | equal_range      | equal_range         |
|                 | lower_bound      | lower_bound   | lower_bound   | lower_bound   | lower_bound   |                  |                     |                  |                     |
|                 | upper_bound      | upper_bound   | upper_bound   | upper_bound   | upper_bound   |                  |                     |                  |                     |
| observers       | get_allocator    | get_allocator | get_allocator | get_allocator | get_allocator | get_allocator    | get_allocator       | get_allocator    | get_allocator       |
|                 | key_comp         | key_comp      | key_comp      | key_comp      | key_comp      |                  |                     |                  |                     |
|                 | value_comp       | value_comp    | value_comp    | value_comp    | value_comp    |                  |                     |                  |                     |
|                 | key_eq           |               |               |               |               | key_eq           | key_eq              | key_eq           | key_eq              |
|                 | hash_function    |               |               |               |               | hash_function    | hash_function       | hash_function    | hash_function       |
| buckets         | bucket           |               |               |               |               | bucket           | bucket              | bucket           | bucket              |
|                 | bucket_count     |               |               |               |               | bucket_count     | bucket_count        | bucket_count     | bucket_count        |
|                 | bucket_size      |               |               |               |               | bucket_size      | bucket_size         | bucket_size      | bucket_size         |
|                 | max_bucket_count |               |               |               |               | max_bucket_count | max_bucket_count    | max_bucket_count | max_bucket_count    |
| hash policy     | rehash           |               |               |               |               | rehash           | rehash              | rehash           | rehash              |
|                 | load_factor      |               |               |               |               | load_factor      | load_factor         | load_factor      | load_factor         |
|                 | max_load_factor  |               |               |               |               | max_load_factor  | max_load_factor     | max_load_factor  | max_load_factor     |
