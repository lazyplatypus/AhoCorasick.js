AhoCorasick.js
======

This is a JavaScript implementation of the Aho-Corasick String Matching algorithm invented by Alfred V. Aho and Margaret J. Corasick on  [Wikipedia](https://en.wikipedia.org/wiki/Aho%E2%80%93Corasick_algorithm).

This version of the algorithm presents several imporvements, including modifications to reduce memory space and computational intensity. This includes replacing the more traditional Linked List Trie (LLT) with the Double Array Trie (DAT). By using two linear arrays to determine the state transition, it eliminates the need to allocate memory space to the unecessary step. This API allows for both "Multi-Pattern Search", which is the combination of the classic Aho-Corasick (AC) with the Double Array Trie (DAT), and the "exact match search" which only utilizes the Double Array Trie (DAT). 
