in 1.0
------

This function, inserted by an

  #include "in.cpp"
  
offers a routine to do input of numbers.

The datatype of the numbers to be entered is

  int
  
Just use like

  #include "in.cpp"

  int a;
  
  a = in();
  
  ...
  
  
This should save bytes in code size compared to a full scanf()- call every
time a number has to be entered.



Version history
---------------

Version 1.0

Initial version

