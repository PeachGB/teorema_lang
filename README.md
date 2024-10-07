# Axioma
**THIS LANGUAGE IS IN PROCESS! IS NOT JUST UNSTABLE BUT ANYTHING CAN CHANGE AT ANY MOMENT, USE IT AT YOUR OWN RISK**

Axioma is a functional programming language based on diverse mathematical notation and lamda calculus.
The intended final product aims to look like a fusion between Haskell and some [array programming languages like APL](https://en.wikipedia.org/wiki/APL_(programming_language))
Axioma uses only symbols and symbol combinations, except for Function names(not implemented).
## Build
as this is a rust program you can use cargo to compile the program
you just run it with an arg for the path of the textfile of the program, for now it can be any extention you want
## Milestones

- [ ] Turing Complete
- [ ] Compiled to native code 
- [ ] Self-hosted
- [ ] Std-lib  

## About The language
Axioma reads the program line by line,
the line statement ends with the new line so you dont have to put semicol or anything like that

for now this are the things you can do with Axioma 

Assign variables(variables are inmutable):
```axioma 
x := 34

h := 4 + x + y

h$    -- you print values with "Value$"
```
Conditional variable assignement
```axioma
h := 5 --h = 5 
7 > h -> x:= 6  -- if 7 > h then x = 6
```

## Sources
[Lamda Calculus](https://en.wikipedia.org/wiki/Lambda_calculus)
[APL](https://en.wikipedia.org/wiki/APL_(programming_language))
[Haskell](https://www.haskell.org/)


