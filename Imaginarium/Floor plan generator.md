Constraint-based floor plan generator for built spaces
===================

This project is to build a system to build floor plans for build spaces (homes, office buildings, etc.) that would allow a TTRPG player to quickly generate floor plans for different genres of buildings (homes, churches, restaurants, etc.).

What's the project?
----------
The basic idea here is to let someone author different templates for floor plans for different kinds of buildings.  These would then be importanted into a program that ignores the exact positions of walls but instead recognizes relationships between walls (e.g. this on is to the left of that one) and constraints on their spacing (e.g. this corridor has to be 6-12 feet wide).  There should also be mechanisms for applying constraints to rooms (the kitchen should be at lease 200 sq. feet, no room should have an aspect ratio bigger than 5:1, etc.)  The player could then say "give me a 1200 square foot apartment" or "give me a 60x80 foot restaurant," and the system would then choose a relevant template and solve the necessary constraints to make an appropriate floor plan.


What is the primary kind of work you'll be doing?
----------
This would probably have three components
- Choosing some way of authoring a template, e.g. as an SVG file or perhaps making a custom editor.
- Writing C# code to import a template either into a CatSAT problem or a custom constraint solver
- Solving the constraints (if using CatSAT, that will hopefully solve it for you)
- Displaying the result, ideally inside *Imaginarium*. 

What knowledge do you need to be able to do it?
-------------
- C# and UI programming
- CS 376 might be helpful
- CS 348 might be helpful

What kind of person will find it interesting?
-----------
Somebody who is interested in research and likes search-based AI.

What will you learn from it?
------------
You'll learn how constraint solvers work and how to do research.

Can I publish this in a conference or journal?
-------
Yes, this would probably be good for at least an EXAG paper and maybe an AIIDE paper.

