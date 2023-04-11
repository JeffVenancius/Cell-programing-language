# DoLanguage
A fake programing language.

That's a lexycal exercise, to be an actual language it would need a parser, compiler, etc...

## Philosophy
You are the wheelman. You do not say what to do, you do.
You are the computer, take the passive aproach and prioritize an active one.
This is a language, it comunicates and, as such, tries to get closer to the human logic.
Think like a human, a human computer.

## Do a barrel roll

Or, as we say, "hello world".
```
(parenthesis are comments, as we do when writing other stuff. 
howTo is the keyword you'll use to define a function, as you
tell yourself how to do stuff. I'll keep calling them functions
just so it'll be easier to explain.)

howTo start: (start is the first thing a program do.)
- write with "hello world". (you usually use () to call a function and pass arguments.
                             Here instead, you'll use "with" to call them and a end stop 
                             to "close" it.
                             Instead of tabs or spaces, indentation is made with hyphens.
                             the last one needs a space.
                             Am I reinventing the wheel? Yeah, but this is just an exercise.
                             Do I have reasons to do so? Yeah, but it doesn't matter.
                             As long you don't really close the parenthesis, everything after 
                             will be considered as it.
                             Comments are smart, though, so it respects the idea that every opened 
                             parenthesis should have a closed one.
                             )
- foo.                      (notice it that to call a function without args you'll just need a dot)

howTo foo:
- write with "bar rel roll"
- passAFunctionAsAArgument with oneMore with "one more"..

howTo  passAFunctionAsAArgument with arg:
- write with parameter.

howTo oneMore with arg:
- give arg (give is like the return keyword)

howTo StaticTypeThings with int//integerType: (/ is used as a way to put the variable into an umbrela.
                                               // means typyng a variable, /  is.like.that
                                               or as we're gonna say it here: is/like/that
                                               )
- item foo: 'nothing'
- item str//bar: 'still nothing, but statically typed.'
- ignore (ignore doesn't do anything.)

```

### Ignore this for now, they're just ideas.

|Instead of|use this|or this|
|---|---|---|
|function|howTo
|if|is|?|
|else if|then is|??|
|else|then|...|
|for|do in||
|while|keep as|as long as|
|switch|what|itemName:|
|return|give|
|var|item
|const|const
|class|kind
|object|being
|(|with
|)|.



## About "use this"

- howTo - When you define a function, you're actually giving instructions, when you call a function, you ask the computer to follow them.
- is - Think of yourself as the computer instead of the master, sometimes it makes more sense to think in the first person.
- then is - Same idea.
- do in - Giving priority to action here.
- keep as - As long as statement is true;
- what - What is the statement equal to? Then look for what to do in the instructions.
- give - more informal than return. Action asks for informality.
- item - phisical aproach.

## About "or this"
- ? - He's just asking.
- ?? - He's just asking again.
- ... - He gave up.
- itemName: - That's it, I believe you don't need to actually say it is a switch statement as long as it looks like a duck, if you know what I mean (duck typing is what I mean).

## Typing

This language is dinamically typed with optional static typing but, if you gonna static type your "items" and "howTos", you better do it all the way: with ranges.

Let's declare a item:
```
# this is a comment, by the way
item foo =  10 # dinamically
item foo2 := 10 # fixed, but let the "compiler" define  what it's gonna be.
item foo3 : number(INT) = 10 # normally fixed, you can use all the datatypes from c++, but do it in all caps as they are actually constant values.
item foo4 : number([0,10]) = 10 # with a range
```
Now with text:
```
item foo = "text"
item foo2 : text(STR) = "text"
item foo3 : text([0, 126]) = "text" # range based on the ANSI table, which is to say that I'll only use ASCII here
item foo4 : text([[65,126]) = "text" # or maybe I just want to use A to ~, you know.
```
I'm basing all this is gdcript and python, as you might have guessed.

The thing is though, if you can define so easily the range in memory you're gonna need, than you can save a lot of space if you implement it right.

As I've said, this is just a lexycal exercise, it's not better or worse than any other language - after all, it's not a language at all, and even at that it doesn't have all the basics.