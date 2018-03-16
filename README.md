# AOPandTransactionsExercises

Spring AOP

1) Create a logging aspect. Create a pointcut to log all methods Of services .
2) Add a logging statement before and after the method ends
3) Log all the methods which throw IOException
4) Log all the methods annotated with @Deprecated Annotation
5) Apply execution, within, args, this and bean expressions on the before and after advice of service bean.
6) Demonstrate the use of pointCut @Pointcut annotation and Reuse the expression created
7) Access the properties of the JoinPoint in before advice. Print Signature of method being called and its arguments

 

Spring Transaction

1) Create User Account table with name,balance fields
2) Create CRUD operation in Account Service (Add/Get/Delete/Update amount in User Account table)
3) Transfer amount from "user1" to "user2". Using Programmatic Transaction
4) Transfer amount from "user1" to "user2". Using Declarative(Annotation Based) Transaction
5) Provide Appropriate Readonly attribute as per Method Behaviour.
6) Create account_transaction table with sender,receiver, balance_transferred fields.
Save values in this table on transfer amount. Even If any error occurs while saving values in transaction table,account table should get updated.
