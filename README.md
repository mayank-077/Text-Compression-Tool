# TextFileCompression
Huffman Coding (Greedy Algorithms) in Java

* Implemented Huffman Coding in Java
* Implemented function to automatically generate .dot file for Graphviz software to visualize the Huffman Tree
* Tested the code with Unix's words file (/usr/share/dict/words)
* Get the result of data compression rate

## Key techniques used
* Greedy Algorithms
* HashMap
* PriorityQueue (Min Heap)
* Nested Class
* Recursion

## Requirements
Graphviz software is required to visualize the Huffman Tree. 
Please download it on [here](http://www.graphviz.org)

1. Prepare your own text file
Create a text file named "original.txt" under /files with any contents.

2. Run the test code
"Test.java" automatically loads the original.txt, then test encoding/decoding the given text, and will show the result of text compression.

3. Visualize the tree with Graphviz
Run below command and it will create test.pdf which visualized the Huffman Tree built for the test
$ dot -Tpdf test.dot -o test.pdf
It will create a pdf file.

Each circle represents a tree node with below properties.
* Unique ID of a node
* Weight of a node
* Character (leaf nodes only)
