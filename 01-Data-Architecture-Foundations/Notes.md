
# Database Framework 

<p> <br>

| Term | Definition |
| -------- | ------- |
| Relational DB | A structured DB that is designed to operate based on the relationships between database objects |
| Data Model | Abstract model created to structure data into a format that can be used to define a real-workd object or concept|
| Schema | Physical blueprint of a DB design |
| Normalization | Process of organizing data into a format that can be used to define a real-world object or concept |
| 3rd Normal Form | A common level of data normalization foiund in transactional relation databases | 

**Data model**
* We need *entities*, *attributes* and *relationships* to build a relational model. Entities are concepts or items we wasnt to collect data on. An entity has many attributes. The entities would be connected via relationships
* The three most common levels of relational modelling are conceptual, logical, and physical.
  * The *conceptual* model focuses slowly on entites and how entites relate
  * The *logical* model focuses on entites, attributes and relationships
  * The *physical* model adds data types, use computer-friendly naming conventions and address relationships

 **Schema**
 * The schema is the physical blueprint of the database. This is not the physical model, although they look similar. On paper, they may actrually look the same. But the schema is what happens when you take the physical data model,
   pull it from the abstract, and turn it into a physical database.
 * For this reason - a schema is created with a single databse management system in mind (e.g. MS SQL Server, Oracle, etc.), while a physical data model can be applied to any system.

**Normalization**
* Data normalization is a method of **reorganizing data** for use in a relational database.
* It is the most preferred choice fro transactional-based work, given that increased writing speed and saves memory, enforcing data ointegrity.
* Normalizing data to the *3rd Normal Form (3NF)* is the most common normalization form when working with transactional data.
* To get to data normalized to the 3NF, the steps are:
  *  Data need to be in 1NF:
    * Use entities (tables)
    * Each cell in an attribute (column) has an atomic value (a single value)
    * No repeated groupings as attributes
    * No duplicate rows 
  *  Data need to be in 2NF:
    * Entity (table in 1NF)
    * Ensure Data Integrity, through the use of unique IDs: all columns depend on the unique ID. This means to identify dependent columns which need to be brought out in a new table
  * Entity (table in 1NF)
  * Remove **transitive** dependencies among attributes through new entities tables
  
# Relational Data Design 
 

















