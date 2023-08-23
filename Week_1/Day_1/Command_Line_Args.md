`process.argv` array in Node.js is the global object that you can use without importing any additional libraries.

* The first element of the `process.argv` array will always be a file system path pointing to the node executable.

* The second element is the name of the JavaScript file that is being executed.

* The third element is the first argument that was actually passed by the user.

```
$ [runtime] [script_name] [argument-1 argument-2 argument-3 ... argument-n]

Example:
$ node script.js arg1 arg2
```