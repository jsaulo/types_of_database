**Team:** Saulo Acevedo, Hans Pech, Ulises Mis.
--------------------------
# Types of Databases.

## 1. Document.


## 2. Key-value.


## 3. Ledger.
A ledger database is log-centric, in comparison to non-ledger databases which are table-centric. 

“Log” is a storage abstraction, used to refer to an append-only, totally ordered sequence of records, ordered by time. 

Currently, the only commercial ledger database available is the Amazon Web Service Quantum Ledger Database (QLDB for short).

The main concept behind Ledger databases is that they “remember the past”: when working with a non-ledger DB, if you want to update a record, the new record will overwrite the previous one, and the old data will be lost. On ledger DB, each update is stored as its own record, therefore giving this type of DB the ability to “explore the past”.

There are 3 key characteristics of ledger DBs:
  1.	Immutable. Writes cannot be changed once stored.
  2.	Transparent. Past or overwritten data can be accessed.
  3.	Verifiable. History of changes can be accessed, and it is possible to verify its authenticity.