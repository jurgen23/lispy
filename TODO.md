### TODO
- [ ] add tests
- [X] extract some function to modules
- [ ] check memory leaks via lldb
- [X] Add the operator `^`, which raises one number to another. For example ^ 4 2 is 16
- [X] Add the function `min`, which returns the smallest number. For example min 1 5 3 is 1
- [X] Add the function `max`, which returns the biggest number. For example max 1 5 3 is 5
- [ ] Extend parsing and evaluation to support decimal types using a double field.
- [ ] Add a builtin function `cons` that takes a value and a Q-Expression and appends it to the front.
- [ ] Add a builtin function `len` that returns the number of elements in a Q-Expression.
- [ ] Add a builtin function `init` that returns all of a Q-Expression except the final element.
- [ ] Write a function for printing out all the named values in an environment.
- [ ] Add a specific boolean type to the language with the builtin variables `true` and `false`
- [ ] Define in Lisp logical operator functions such as `or`, `and` and `not`
- [X] Adapt the builtin function `join` to work on strings.
- [X] Adapt the builtin function `head` to work on strings.
- [X] Adapt the builtin function `tail` to work on strings.
- [ ] Create a builtin function `read` that reads in and converts a string to a Q-expression.
- [ ] Create a builtin function `show` that can print the contents of strings as it is (unescaped).
- [ ] Create a special value `ok` to return instead of empty expressions ().
- [ ] Add functions to wrap all of C's file handling functions such as `fopen` and `fgets`.
- [ ] Add Lispy standard library
- [ ] Write some example programs using your standard library, for users to learn from.
- [ ] Add User Defined Types (aka struct in C)
- [ ] Add list literal `[1 2 3]` equals `list 1 2 3`
- [ ] Add operating system interaction. Wrappers for `fread`, `fwrite`, `fgetc` etc.
- [ ] Variable Hashtable
- [ ] Pool allocation
- [ ] Garbage Collection
- [ ] Tail Call Optimisation
- [ ] Lexical Scoping
- [ ] Static Typing
- [ ] replace `mpc` with hand rolled parser
