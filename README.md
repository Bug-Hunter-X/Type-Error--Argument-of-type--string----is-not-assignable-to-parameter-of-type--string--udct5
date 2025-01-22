# Type Error: Argument of type 'string[]' is not assignable to parameter of type 'string'
This bug demonstrates a common type error in TypeScript when passing an array to a function expecting a string. The function `greeter` is defined to accept a string, but the code attempts to pass an array of strings. This results in a type error.

The solution involves modifying the function signature or the data passed to it to match the expected type.