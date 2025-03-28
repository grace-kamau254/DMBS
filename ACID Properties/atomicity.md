# Atomicity
By this, we mean that either the entire transaction takes place at once or doesn’t happen at all. There is no midway i.e. transactions do not occur partially. Each transaction is considered as one unit and either runs to completion or is not executed at all. It involves the following two operations:
###### Abort 
 If a transaction aborts, changes made to the database are not visible.
 ###### Commit
 If a transaction commits, changes made are visible.
 Atomicity is also known as the ‘All or nothing rule’.

Consider the following transaction T consisting of T1 and T2 : Transfer of 100 from account X to account Y .

atomicity
Example

If the transaction fails after completion of T1 but before completion of T2 ( say, after write(X) but before write(Y) ), then the amount has been deducted from X but not added to Y . This results in an inconsistent database state. Therefore, the transaction must be executed in its entirety in order to ensure the correctness of the database state.