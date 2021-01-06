# JavaScript-Built-in-Functions

Not an exhaustive list
Definitions from https://www.tutorialspoint.com/javascript/javascript_builtin_functions.htm
Examples from https://www.w3schools.com/jsref

## Number Methods
- `toFixed()` Formats a number with a specific number of digits to the right of the decimal
  - Ex. `var num = 5.56789; var n = num.toFixed(2)`
- `toString`  Returns the string representation of the number's value
  - Ex. `var num = 15; var n = num.toString();`
  
## String Methods
- `indexOf()` Returns the index within the calling String object of the first occurrence of the specified value, or -1 if not found.
  - Ex. `var str = "Hello world, welcome to the universe."; var n = str.indexOf("welcome"); // n = 13`
- `length()` Returns the length of the string.
  - Ex. `var str = "Hello World!"; var n = str.length; //n = 12`
- `replace()` Used to find a match between a regular expression and a string, and to replace the matched substring with a new substring.
  - Ex. `var str = "Visit Microsoft!"; var res = str.replace("Microsoft", "W3Schools");`
- `search()` Executes the search for a match between a regular expression and a specified string.
  - Ex. `var str = "Visit W3Schools!"; var n = str.search("W3Schools"); //n = 6` CHECK THIS
- `slice()` Extracts a section of a string and returns a new string.
  - Ex. `var str = "Hello world!"; var res = str.slice(0, 5); //res = "Hello"`
