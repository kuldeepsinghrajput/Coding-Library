What is a suffix array.
Consider a string s.
S=ababba

Let's write all its suffixes in lexicographical order. We get this an array of strings.

a
ababba
abba
ba
babba
bba

This sequence of suffixes is called the suffix array. How will we store it? 
If you store it as strings, then it will occupy O(n2) memory. To keep it smaller,
let's notice that the suffix can be identified by the index of the first character.
In our example, suffixes will have these numbers.
