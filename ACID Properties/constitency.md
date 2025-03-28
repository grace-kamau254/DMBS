# Constitency
Consistency ensures that a database remains in a valid state before and after a transaction. It guarantees that any transaction will take the database from one consistent state to another, maintaining the rules and constraints defined for the data.
Referring to the example above,
The total amount before and after the transaction must be maintained.
Total before T occurs = 500 + 200 = 700 .
Total after T occurs = 400 + 300 = 700 .
Therefore, the database is consistent . Inconsistency occurs in case T1 completes but T2 fails