## Attempt to estimate a size of Python object  
Originally published: 2013-02-01 11:57:14  
Last updated: 2013-02-02 12:09:23  
Author: Andrew   
  
This function is built on assumption, that no custom types was implemented. Function traversing the tree of given object and summing sizes of pointers and basic-types objects got with sys.getsizeof() function.