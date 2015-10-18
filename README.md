# css-to-js
Sublime text plugin to convert css formatting to javascript object literal formatting

## Why ?
Writting your css in JavaScript is becoming a thing, copy pasting from dev tools and manualy reformating was a pain.
I don't like the idea of yet another pre processor to handle this, JS is fine and more powerfull than any preprocessor i have used, so let's simply salvage this power intead of relying on another tool to compile our JS.

![alt tag](http://i.imgur.com/Bdb5me0.gif)

nothing really fancy.
### known issues :
  - remove last line return if it's an empty line
  - ??

### ToDo :
  - check if it's the last element of the object instead of always adding the comma, (I don't care, it fit my coding style)
  - fix indent while were at it
  - handle multiline stuff
