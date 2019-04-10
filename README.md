# Swift-Cheat-Sheet
Swift Cheat Sheet for Coding Interviews

**Fetching Character for ASCII Values and vice-versa**
```
var a: Character = "a"
a.asciiValue #outputs: 97
Character(UnicodeScalar(a.asciiValue!-32)) #outputs: "A"

```


