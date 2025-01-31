Which language should I choose?
===============================
**The one most relevant to what you want to be doing.**

It's up to you.  Each has its good and bad sides,
and not everyone likes to express ideas in the same way.

Language is a tool to express ideas, programming languages
are no different.  And like with usual spoken languages,
it becomes easier and easier to learn new ones after the first.

There are very few programmers who can only write in one
programming language.

**Don't stress too much about the choice, you can
switch later if you think something else suits you better,
it won't go to waste either way**

If you absolutely have zero clue, 3 of the more usual
starting languages are [Python](#python), [Javascript](#javascript)
and [C](#c)

Languages in this page are listed in alphabetical order


For teachers
------------
Hopefully this is useful to teachers as well as a resource to
decide what language they want to keep their course in


C
=
The lingua franca of programming languages, your toaster can
probably run software built with C.

Helps you understand what your computer hardware actually does
when you instruct it to do something

Usual usage
-----------
- Operating systems
- UNIX system layer
- Embedded
- Lingua franca to combine software written in other languages

Pros
----
- Quite simple feature set
- Common as dirt
- Need to understand nuts/bolts of what is going on
- A lot of languages are heavily inspired by C

Cons
----
- Extremely easy to make mistakes
- Long time to get anything flashy going (can get boring)
- Need to understand nuts/bolts of what is going on
- Not necessarily the hottest language to advertise for headhunters

Recommended when
----------------
- You are more interested in the journey than the end result
- You want to learn computer internals
- You are interested in systems programming

Materials
---------


C#
==
Usual usage
-----------
- Games (scripting Unity, XNA)
- Web applications

Pros
----
Cons
----
Recommended when
----------------
Materials
---------

C++
===
Started as a way to reduce perceived complexity of the C programs while
keeping compatibility to C code.  Has since diverged significantly from
the original "C with classes"

Internet tutorials for this language are almost always total garbage and
actively harmful, so requires either a teacher or a good book and a cabin
without Internet.

Protip:  *do not try to learn C to learn C++, it's a trap and you'll need
to unlearn a lot of C to be good at C++*

Usual usage
-----------
- Automation (vehicles, industrial, flight control...)
- Autonomous machines
- Embedded
- Game engines
- Low-level or performance-critical functionality for other languages
- CAD/Graphics software
- High-frequency trading

Pros
----
- Useful across the board
- Allows access to nuts and bolts of the system without requiring it

Cons
----
- Complex
- May take a long time to get anything flashy going (can get boring)
- Absolutely requires a good teacher or really good self-discipline plus a good book
- Most online courses are decades old and don't reflect the current best practices

Recommended when
----------------
- You want performance
- You want to learn the nuts and bolts
- You are interested in systems programming

Materials
---------


Python
======
Quite simple language originally written with the explicit goal
of teaching programming.  Used in plethora of things because of
its apparent simplicity

Usual usage
-----------
Pros
----
Cons
----
Recommended when
----------------
Materials
---------


Java
====
Usual usage
-----------
Pros
----
Cons
----
Recommended when
----------------
Materials
---------


Javascript
==========
Originally created for interactive components for web pages,
has spread to plethora of different uses

Usual usage
-----------
- Web development (frontend and backend)

Pros
----

- The most used language, so there are many learning resources available
- Dynamically typed: one less thing to worry about for starters

Cons
----
- Due to backwards compatibility, there are obsolete ways to write JS that should be avoided
- Dynamically typed: bad for serious projects

Recommended when
----------------
- You want to do anything web, but aren't ready to jump into TypeScript yet

Materials
---------
- [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)
- [JS for C & Python programmers](https://www.wooji-juice.com/blog/javascript-article.html)

Lua
==========
A light, somewhat verbose Python-like language where indentation doesn't matter and almost everything is a table. Also, indexing starts from one. Typically, the Lua VM sits on top of a lower-level engine, providing an easy-to-use scripting interface.

Usual usage
-----------
- video game scripting & modding
- game development (Love2D, Pico-8, TIC-80)
  
Pros
----

- tiny & portable
- short learning curve
- fast, especially when using the JIT compiler
- powerful table system supports multiple key & value types
  - ...and can be further extended with metatables
- functions:
  - inline functions don't have a confusing lambda syntax (looking at you, Python)
  - can be tail called, recursed & passed around easily
  - multi-value return & variable number of function parameters
- coroutines!

Cons
----
- the Lua package ecosystem is a mess
- the community is split between different Lua versions
- pattern-matching that is almost regex, but not quite
- tiny size has downsides (depends on who you ask):
  - for a language obsessed with tables, you'd think there were more table-specific features built in (like printing a table)
  - no object oriented features out of the box
  - limited unicode support

Recommended when
----------------
- you want to add lightweight scripting on top of a video game engine
- you want to quickly piece together a tiny game or prototype

Materials
---------
- [Learn Lua in 15 minutes](http://tylerneylon.com/a/learn-lua/)
- [How to LÖVE](https://sheepolution.com/learn/book/contents)
  - learning Lua for making games with the Love2D framework
