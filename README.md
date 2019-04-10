# Swift-Cheat-Sheet
Swift Cheat Sheet for Coding Interviews

**Fetching Character for ASCII Values and vice-versa**
```
  var a: Character = "a"
  a.asciiValue #outputs: 97
  Character(UnicodeScalar(a.asciiValue!-32)) #outputs: "A"

```

**Generating Random number in a given range**
```
  var v = Int.random(in: low...high)
  var w = Double.random(in: low...high)

```
