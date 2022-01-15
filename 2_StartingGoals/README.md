# Starting Goals

## Get three characters running
This can be done by opening another window (type `/window` in chat), or launching a character via `start_character(character_name, code_slot)`

## Make your code work for everything
A big thing to focus on when developing your code is making sure that regardless of the character or class, your code will work. For example, instead of doing something like:
```
if(character.name == "MyPriest"){
    heal(target)
}
```
Do the following:
```
if(character.ctype == "priest"){
    heal(target)
}
```
