# hept_syntax_convention
*a gentle fusion of familiarity and a concise unique structure, this syntax and naming convention was born out of passion for languages and minimal code golfing; trying to hit a balance between performance, form, and function.*

-------
## convention & system rules/requirements:
  1.  ***always lower_snake_case*** *for all naming of* ***variables, functions, systems***
  2.  ***open-source code*** *so that* ***access is simple*** *while learning*
  3.  ***function complexity*** *corresponds to* ***name verbosity and_segments***
  4.  ***minimal code repetition*** *to allow* ***legible source code*** *unless logically required*
  5.  ***hierarchical importance action*** *before* ***subset or connected function*** *when naming*
  6.  ***automated memory allocation*** *and* ***safe data accessing*** *for anxiety free code*
  7.  ***library files are independent*** *and are* ***individual entities***

-------
## syntax example:
```c
void object_set( object o, int x, int y) // 'set' is happening to 'object'
{
  o.x = x;
  o.y = y;
}
//
object new_object( int x, int y ) // 'new' before 'object' because of rule 5.
{
  object o;
  object_set( o, x, y ); // layered functions for rule 4.
  return o;
}
//
bool object_move_random( object o ) // long name for rule 3.
{
  /*
  * lots of code
  */
}
```
