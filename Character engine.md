Character engine
===================

This project involves writing the support code for Unity or Godot that would allow a higher-level AI system to control an NPC as it moves through a tile world

What is the primary kind of work you'll be doing?
----------
C# programming within either Unity or Godot

What knowledge do you need to be able to do it?
-------------
- CS376 or equivalent

What kind of person will find it interesting?
-----------
Somebody who likes game programming, C# programming, etc.

What will you learn from it?
------------
You'll get experience with building software for a user other than yourself

Can I publish this in a conference or journal?
-------
This is more infrastructure for research and/or than research itself.  You could likely get a demo or possibly software-track publication at the AIIDE conference, but this isn't research in the sense of inventing new algorithms.

What's the project?
----------
This project would involve building the C# infrastructure for allowing characters to move about an RPGmaker-style tile world.

The system should allow characters to:
- Navigate (go to specified objects in the world without bumping into things)
- Pick up and drop items from/to container objects in the world (tables, refrigerators, boxes, whatever)
- Sit on objects (Chairs, beds) and stand up
- Talk to other characters (pop up speech bubbles)
- Initiate the above commands
- Be informed when they complete
- Be informed of events such as collisions or other characters saying things
- Otherwise sense the environment

In addition, the designer should be able to
- Lay out the floor/wall/door/etc. tiles in a level
- Place objects in the environment
- Specify information about the objects (this one is a container, this one can be turned on/off, this one can be opened/closed, etc.)

