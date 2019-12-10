# Task 3 - ASCII Art Compression

Ms. Adriaan loves to make ASCII art, but hates how much data her creations use.

She has designed a way to compress her images by writing each line as a pattern of numbers then symbols. Each line of the image is stored as an element in an array.

For example:
```
INPUT:

image_data = ["2L","4F","6C"]
```
```
OUTPUT:

LL
FFFF
CCCCCC

```

A more complex example would be:
```
INPUT:

image_data = ["11-", "2-1{1}3-1{1}2-", "11-", "3-1@3-1@3-", "4-3@4-", "11-"]
```
```
OUTPUT:

-----------
--{}---{}--
-----------
---@---@---
----@@@----
-----------

```


An *even more* complex example would be...
```
INPUT:

image_data = ["27B", "1B1|1B21-1B1 1B", "3B21-3B", "3B21-3B", "3B21-3B", "3B21-3B", "3B21-3B", "27B", "5B15-6B", "5B2-5B9-6B", "5B2-5B9-6B", "5B2-5B9-6B", "5B15-6B"]
``` 
```
OUTPUT:

BBBBBBBBBBBBBBBBBBBBBBBBBBB
B|B---------------------B B
BBB---------------------BBB
BBB---------------------BBB
BBB---------------------BBB
BBB---------------------BBB
BBB---------------------BBB
BBBBBBBBBBBBBBBBBBBBBBBBBBB
BBBBB----------------BBBBBB
BBBBB--BBBBB---------BBBBBB
BBBBB--BBBBB---------BBBBBB
BBBBB--BBBBB---------BBBBBB
BBBBB----------------BBBBBB
```

Write the algorithm that will convert Ms. Adriaan's arrays of data into the correct ASCII images.

## Bonus - Save the art!

Bonus points are available if your code automatically saves the created ASCII images as a .txt file
