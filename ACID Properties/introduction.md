# introduction
A transaction is a single logical unit of work that interacts with the database, potentially modifying its content through read and write operations. To maintain database consistency both before and after a transaction, specific properties, known as ACID properties must be followed.
ACID is an acronym...A for atomicity,C for constitency,I for isolation and D for durability.

The properties are essential for ensuring data consistency, integrity, and reliability during database transactions.
## Atomicity
The entire trascation takes place at once or doesn't happen at all.
## Constitency
The database must be constitent bbefore and after transaction.
## Isolation
Multi transactions occurs independently without interference.
## durability
The changes of a successful trascations occurs even if the system failure occurs.