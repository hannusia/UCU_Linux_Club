### Week 6 Regular Expressions Homework

### This is a template for the report of 21 problems on [this site](http://regextutorials.com/excercise.html).

### Fork this repository, change this file and send us the link for grading.

### We recommend you (re)watch our presentation, and use a [cheatsheet](./cheatsheet.md) while working on the following problems.

### If you are having problems with figuring out the correct solution, skip it for later, and if you are completely lost, use the hints and try to understand them.

---

### Problem 1: Floating point numbers
```
\d\.\d+
```
### Problem 2: Years before 1990
```
[2-7](\s\w*)*\,*\:*(\s\w*)*\(19[0-8]\d\)
```
### Problem 3: Hexadecimal colors
```
#(\d|\w){6}
```
### Problem 4: Grayscale colors
```
#([0-9a-fA-F]{1,2})\1\1
```
### Problem 5: Too long lines
```
.+[o.]{12,16}.+
```
### Problem 6: Remove repeating words
```
(\"*\w+\"*\-*\w*\'*\w*\s)\1 replace with $1
```
### Problem 7: Match HTML tags
```
</*!*\w*\s*\w*>
```
### Problem 8: Cut numbers two digits after floating point
```
(\d\.\d{2})\d* replace $1
```
### Problem 9: Digit commas formatting
```
insert your pattern here
```
### Problem 10: Match lowercase function declarations
```
\w{8}\s[a-z]\w*\(\w*\)
```
### Problem 11: Change date formats
```
(\d{4})-(\d{2})-(\d{2}) replace with $3.$2.$1
```
### Problem 12: Validate 24h time format
```
((0|1)\d|2[0-3]):[0-5]\d
```
### Problem 13: Validate AM/PM time format
```
(\s\w); replace with $1,
```
### Problem 14: Pascal style to C-style parameters
```
#not finished yet 
var\s+\w*\s=\snew
```
### Problem 15: Change variable initialization
```
insert your pattern here
```
### Problem 16: IPv6 adresses
```
(.{0,4}:){7}.{0,4}
```
### Problem 17: Validate 32 or 24 bit hexadecimal colors
```
insert your pattern here
```
### Problem 18: Replace operators with function calls
```
insert your pattern here
```
### Problem 19: Extract query string from URL
```
insert your pattern here
```
### Problem 20: Extract host from URL
```
insert your pattern here
```
### Problem 21: Strings not containing word
```
insert your pattern here
```
