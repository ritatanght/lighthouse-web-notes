# pure functions
- Produce a function with no side effects and also does not rely on side effects from other code (doesn't read global bindings)
- when called with the same arguemnts, it always produces the same value

# Function - Best Practice
1. Give your functions precise verb/action based names
2. Use camelCasedNames (like this one)
3. Properly indent the function code
4. Functions should focus on a single task: returning a value or causing a side effect. Break your function into additional smaller functions if you find it doing two or more things
    * One single task could be to compute and return a value 
    * Another single task could be to perform a side effect such as logging a message to the screen
5. Data needed by Functions should be passed in as parameters/arguments (i.e. local scope) instead of being accessed directly.
   * Functions that take in parameters are more reusable, since they are less dependent on their surroundings, (i.e. their outer scope).