# Data Structuring & Modeling Previous Projects

Probably, this is the first time that you've heard the term ***Data Structuring***:

> In computer science, a data structure is a data organization, management and storage format that enables efficient access and modification. More precisely, a data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data. [Source](https://en.wikipedia.org/wiki/Data_structure)

But we've been using it without realizing, for example:

**In the excuse generator** we used *String* to store each piece of the excuse like this:
```js
let who = ['the dog','my granma','his turtle','my bird'];
let what = ['eat','pissed','crushed','broked'];
let when = ['before the class','right in time','when I finished','during my lunch','while I was praying'];
```
Our data model was:
+ Who: *String*
+ What: *String*
+ When: *String*

**In the TODO list project** we used *Object* as our main data structure (we started with a simple *String* and then we changed to *Object*):
```js
{
  label: 'Do the replits',
  done: false
}
```

Each todo is an *Object* that contains the **label** (*String*) and **done** (*Bool*) keys. 

### But what about previous exercises?

We must always have a clear understanding of how we're storing our data, this way we're more organized and faster while coding. Think of this as knowing your kitchen: you can cook without knowing the kitchen but you'll be way faster if you know where the ingredients and tools are. 

## Instructions

Go through your previous exercises and find the implemented data structure(s). 

Previous projects you may have done:

- Domain name generator
- Random Card Generator 
- Seconds Counter
- Traffic Light
- Tic-Tac-Toe
- Media Player
- StarWars Blog
- Contact List

Node:

# Data Modeling

> DATA MODELS DESCRIBE BUSINESS ENTITIES AND RELATIONSHIPS
>
> Data models are made up of entities, which are the objects or concepts we want to track data about, and they become the tables in a database. Products, vendors, and customers are all examples of potential entities in a data model. Entities have attributes, which are details we want to track about entities—you can think of attributes as the columns in a table. If we have a product entity, the product name could be an attribute. [Source](https://www.credera.com/blog/technology-solutions/data-modeling-explained-in-10-minutes-or-less/)

One of the most important skills to develop in your coding career is to use [abstraction](https://en.wikipedia.org/wiki/Abstraction_(computer_science)) to translate from physical world to digital world.

Objects and Object Oriented programming are the best way to see this skill in action, we've seen this process happening when we represented cars in the digital world, not by their looks but by their data.

Just as almost all other subjects in coding/computer science there's a standard way to represent *data models*, it is called [UML](https://en.wikipedia.org/wiki/Unified_Modeling_Language) (Unified Modeling Language). Check this video that explains how to create a [UML Diagram](https://www.youtube.com/watch?v=UI6lqHOVHic&list=PLUoebdZqEHTxNC7hWPPwLsBmWI0KEhZOd)

## Exercise (2/2)

Create a UML Diagram of the popular platform: **Instagram**. Try to find 3 entities that represent the platform and are key for it to work. Try to include at least 5 *attributes* per entity (some are invisible for the regular user, but not for a coder).
