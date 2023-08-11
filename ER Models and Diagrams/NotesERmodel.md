### Entity Relationship model

1. Entity - object that can be uniquely identify (Nouns)

2. Attributes - feature of an entity
    1. key attributes {cusId}
    2. Multi valued attributes {phoneNumber, credit card }
    3. Derived attributes {age}
    4. Compound attributes {name,address}
    5. 

3. Relationship

 
Participation
    1. Total Participation 
    2. Partial Participation


Cardinality of Relationships
    1. one to one
    2. one to many
    3. many to one
    4. many to many 

Constructing table from ER Diagram
    1. Minimize the number of tables
    2. Primary Key is a must
    3. Each cell must have only one value

                Number Of Tables
 1(P) : 1(P)    2 tables
 1(P) : 1(T)
 1(T) : 1(P)
 1(P) : 1(T)

 1(P) : M(P)
 1(P) : M(T)
 1(T) : M(P)
 1(T) : M(T)


 M : 1
 M : N


 Self-referential relations