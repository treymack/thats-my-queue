# That's My Queue!

Simple FIFO Queue Implemented as a SQL Server table.

### Benefits of using SQL Server to host a Queue

- Pushing to and Popping from the Queue can enlist in the same transaction as the rest of your database changes, when the data is in the same database. No need to escalate the transaction to a distributed one using MSDTC.
- You're already using SQL Server. One less piece of infrastructure to manage.

### Features

- Multiple worker processes operating on a Queue
- Named Queues
- Asynchronous API
- Processing 0..* messages in a particular queue simultaneously
- Dead Letter Queues
- Configurable number of failures for a given message
- Message serialization defaults with custom serialization available

### Not Included

- Message Routing
- Support for other databases
- Support for other messaging platforms
- Cross-platform


### Dependencies

- None