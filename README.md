# nwconsole
Redirect console.log calls to a basic log file for node webkit applications.

# Motivation
'console' in nw application can easily get mixed between node & webkit environnement.
In nw, nwconsole, will enforce output in a simple, unique, temporary file for both nodejs & webkit context.
If used in a raw nodejs environnement, nwconsole falls back to the native 'console'.

# Installation
```
npm install nwconsole
```

# Dependencies
none, full code source is 10 lines, give it a look.

# Usage example
```
console = require('nwconsole');
console.log("This behave '%d', "43", "Exactly as console should");
```

