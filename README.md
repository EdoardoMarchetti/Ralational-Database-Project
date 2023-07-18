# Ralational-Database-Project
Exam project for "Basi di Dati" at Unisveristy of studies of Perugia

The pdf file contains the all the design and realization processes needed for the definition of the database.

The data reported in the examples are syntactic data generated thanks to [mockaroo](https://mockaroo.com/)

## CONCEPTUAL DESIGN
* **Collection of requirements**: The collection of requirements means the complete identification of the problems that the database to be created must solve and the characteristics that this database must have following the querying of the client of the database.
* **Specification analysis**: The analysis of the specifications consists in the clarification and organization of the information collected during the interview. The document is decomposed into groups of homogeneous sentences, relating to the same concepts.
* **Glossary of main terms**: The glossary of terms that is presented is intended to facilitate the understanding and decomposition of the specifications as well as the identification of the concepts of greatest interest.
* **List of operations**: The list of main operations for the database completes the preliminary phase of the conceptual design. The information and the frequency with which these operations are carried out become decisive in the logical design phase in terms of optimizing the information to be represented.
* **Entity-Relationship Scheme**: The conceptual design of a database consists in the construction of an Entity-Relationship scheme able to describe the specifications collected during the preliminary phase. The next steps also aim to refine the representation of the primary concepts.
* **Unexpressible constraints**: Sometimes it is impossible to express all the information present in the data specifications in the conceptual schema. The information that cannot be represented with the constructs of the E - R model are then listed separately and cataloged as non-expressible constraints. However, this information must be taken into account in the subsequent phases.
* **Data Dictionary (Entity and Relationships)**

## LOGIC DESIGN
* **Volume table**
* **Table of operations**
* **Redundancy analysis**: A redundancy, in a conceptual scheme, consists in the presence of a datum that can be derived from other data through a series of operations. The analysis of redundancies, based on costs in terms of space and time, is necessary to understand whether a given redundancy involves an overall advantage or a disadvantage.
* **Elimination of generalizations**: Generalizations are not directly representable in traditional database management systems. For this reason, at this stage, it is often necessary to transform this construct through the exclusive use of natural implementations, or entities and relationships.
* **Merging / Partitioning of Relationships**: The merging (reverse partitioning operation) is an operation usually performed on associations with one-to-one cardinality that leads to the merging of two different entities. Horizontal partitioning (reverse merger operation) is a relationship decomposition operation between two entities into two (or more) relationships between the same entities.
* **Choice of primary identifiers**: The choice of primary identifiers is essential to translate the E-R schema into the relational model, since in this model the keys are used to establish links between data in different relationships.
* **Ristrutturazione dello schema E-R**
* **Relational Model**: Starting from the restructured E – R scheme, an equivalent logic scheme is built that can represent the same information. This scheme, called the relationship model, is the result of the logical design.**
* **Normalization**: To evaluate the quality of the database, its normalization is carried out, verifying that the functional dependencies include only key terms of the relations as implicating (Boyce and Codd Normal Form).

## IMPLEMENTATION OF THE OPERATIONS
* **Creation of the tables**
* **Creation of queries**

## EXECUTION OF THE MAIN OPERATIONS
You can find same execution examples.
