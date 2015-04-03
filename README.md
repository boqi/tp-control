Boqi's Tasks Pool 
=================

This is a tasks pool controler for _.mtd-tasks-daemon__.

Each git tree entry represents one or more tasks, read

by __MyPlace::Tasks::Center::Git__.


File entry syntax
-----------------

* normal text
  
  passed as 1 function argument

     >>hello world
     >>
     >>=>"hello world"
  
* __\t__, __:__ or __>__ separated text

  passed as separate function arguments
  
     >>hello \t world
     >>
     >>=>"hello" "world"

* text begin with __>__

  will be ignored


