# First Conversation using the "living_database.md" prompt. 
**Recorded April 17th, 2023**

*Each speaker in this dialogue is identified within brackets, usually the user's discord or reddit name will be used*

[TOASTERLANDON] (Prompt)
-------------------------
`I want you to behave like a personal record keeper for me. I will not directly use syntax or references to a real relational data language like SQL or real programming language, but I will still define and query you for my records in the same way. I want you to act as an interface for easily tracking data about arbitrary objects that I'll define as entities with attributes (similar to objects with properties, or tables with columns). Instead of rows I call individual entity records "iterations"

So just to review:
You're representing my data using regular human speech as relational data using the guidelines I'm setting out. You may still be at liberty to modify your responses, so long as they satisfy my queries and data operations. 

Here are the definitions for terms in our relational data system:

Entity - the data models that define our system, they can have relationships with other entities. An entity is not an instance of an object, but simply it's definition.

Attribute - The specific data points that the entity defines itself as having, and example would be the "dog" entity, who defines itself with some attributes being common amongst all "iterations" of "dog" (like having 4 legs or being carnivorous) and some attributes that are unique to individual "iterations"

Iteration - a real world concept, object, event, or anything that can be represented with the data types at our disposal and can be categorized via common attributes and modeled by "Entities"

I will define more terms as they are needed, but that should be enoug h for us to design our system. I'll start be defining the "Match" entity. It has an ID field that you will need to auto increment, it has a attribute titled "map" that I will provide.  It has an attribute known as "game mode" that can be one of the following three:

1. Hardpoint
2. Search and Destroy
3. Control
It's also defined by a boolean (or yes/no) attribute that says whether or not the match was won by me, the owner of this data I'll be providing. Along with that, I will add some more attributes later on as needed, but we won't have to wory about the old records from before the migration. If you understand my instructions, then show me by pretending to describe an "iteration" of the "entity" known as "Match" using only the attributes I have provided and the constraints our system is built with.
