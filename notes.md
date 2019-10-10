# Requirements

A client has hired you to track zoo animals.
For each individual animal, you must track that their name, species, and all zoos in which they have resided (including zoo name and address).

Determine the database tables necessary to track this information.

Label any relationships between table.

# Notes
 
 ## a good data model
 - captures ALL the information the system needs
-  captures ONLY the information the system needs <--- Abstraction
- reflects reality (from the point of view of the system)
- is flexible, can evolve with the system
- guarantees data integrity, without sacrificing performance <--- using constraints
- is driven by the way we access the data

## components 
- entities (nouns: zoo, animal, species), like a resource --> tables,
- properties --> columns or fields.
- relationships --> Foreign Keys

## Workflow

-identify entities
- identify properties
- identify relationships

## Relationships
- one to one: rare
- one to many: this is it!
- many to many: a trick!!

## mantras

-every table must have a primary key
- one to many relationship requires a foreign key
- the foreign key goes on the many side
- many to many needs a third table
- theird table cna have other information
- work on two or three entities at a time