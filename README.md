# OCP
OCP Ceritification 
# Rule 1 #
#If there is an exact match between the number and types of arguments specified in the method call and the method signature of an overloaded method then that is the method that
 will be invoked.
 # Rule 2 #
#Primitive types can be widened (e.g. a byte can widen to an int).
# Rule 3 #
#Objects can be widened (e.g. an Integer can be widen to an Object).
# Rule 4 #
#Wrapper types cannot be widened to another wrapper type (e.g. a Byte cannot widen to an Integer).
# Rule 5 #
#Primitive types can (since Java 5) be boxed (e.g. an int can be boxed as an Integer).
# Rule 6 #
#Primitive types can be boxed and then widened (e.g. an int can be boxed as an Integer and then widened to an Object).
# Rule 7 #
#Primitive types cannot be widened and then boxed (e.g. a byte cannot widen to an int and then be boxed as an Integer).
# Rule 8 #
#Wrapper types cannot be unboxed but not then widened (e.g. an Integer can be unboxed to an int).
# Rule 9 #
#Wrapper types cannot be unboxed and widened (e.g. a Byte can be unboxed to a byte and then widened to an int).
# Rule 10 #
#Widening a primitive type will be chosen ahead of boxing (e.g. widening a byte to an int will be chosen ahead of boxing to a Byte).
# Rule 11 #
#Unboxing an object will be chosen ahead of widening (e.g. e.g. unboxing an Integer to an int will be chosen ahead of widening to a Object, but I have experienced the following 
Integer to an Object will be chosen ahead of unboxing to an int).
# Rule 12 #
#A primitive type will be widened to the smallest available primitive (e.g. widening a byte to an int will be choosen ahead of widening to a long).
# Rule 13 #
#A method using varargs will only be chosen if is there is no other overloaded version that is applicable.
