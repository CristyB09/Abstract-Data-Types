                                 # Abstract-Data-Types
                          1) Introduction to Abstract Data Types; 
      • A more specific definition:
Abstract Data Types
An Abstract Data Type (ADT) is a specification for a group of values and the operations on
those values that is defined conceptually and independently of any programming
language.
(a data structure is an implementation of an ADT within a programming language) 

• You may have already seen (and been been using) the implementation of an ADT when
manipulating string values
Abstract Data Types
• Java’s String data type is an ADT that
allows programs to manipulate strings
• A String is a sequence of Unicode
characters
• The API for String provides an interface
for the ADT

• Remember we can use an ADT without knowing the underlying implementation details

• When using data types, you need to know:
• Its name (capitalized in Java)
• How to construct new objects (instantiation)
• How to apply operations on to a given object (invoke methods)
Abstract Data Types
• To construct a new object:
• Use keyword new to invoke a constructor
• Use data type name to specify the type of the object
• To apply an operation:
• Use object name to specify which object
• Use the dot operator to indicate an operation
is to be applied

String str;
str = new String(“Hello world”);
str = str.substring(0, 5);
System.out.println(str);








2) The Bag ADT; 



3) Array Implementation of Bag;
