Abstraction is a key concept in programming that helps us to filter away unncessary details so as to let us focus on the primary problem. Here is an example for incrementing a value by one:

_inc(x) = x + 1_

Having _inc(x)_ function provided as an abstraction, one can increment a value, say 10, by using _inc(10)_ without worrying how it is done everytime.  We can also provide abstractions such as

- _isDivisible(x,2)_ to test if x is divisible by 2 (i.e. with no remainder)
- _add(x,y)_ to add the values of _x_ and _y_
- _rem(x, y)_ to find the remainder after dividing _x_ by _y_,
- _max(x, y)_ gives the larger of two values x and y,
- etc.

With these abstractions are provided, we need not worry about how they work each time they are used, just that they will work whenever they are used!