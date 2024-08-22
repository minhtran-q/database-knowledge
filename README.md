# SQL Knowledge
## Optimize performance
<details>
  <summary>Avoid abusing SELECT DISTINCT</summary>
  <br/>
  
</details>

<details>
  <summary>Use index</summary>
  <br/>

+ Identify columns used frequently in WHERE, JOIN, and ORDER BY clauses, and create indexes can improve query performance.
+ Script used to identify missing indexes.
  
</details>

<details>
  <summary>Avoid SQL injection</summary>
  <br/>

+ Use parameterized queries to prevent SQL injection attacks.
  
</details>

<details>
  <summary>Avoid using implicit data type conversion</summary>
  <br/>

+ Use parameterized queries to prevent SQL injection attacks.
  
</details>

<details>
  <summary>Using NOT EXISTS instead of NOT IN</summary>
  <br/>
  
</details>

<details>
  <summary>Avoid arithmetic operators in the WHERE clause</summary>
  <br/>
  
</details>

<details>
  <summary>Avoid Function on the WHERE clause</summary>
  <br/>
  
</details>
<details>
  <summary>Use JOINS instead of Subqueries</summary>
  <br/>
  
</details>
<details>
  <summary>Use EXISTS over COUNT(*) to check if data exists</summary>
  <br/>
  
</details>
<details>
  <summary>Use UNION ALL instead of UNION</summary>
  <br/>
  
</details>
<details>
  <summary>Avoid using cursor</summary>
  <br/>
  
</details>
<details>
  <summary>View vs Stored procedure</summary>
  <br/>
  
</details>

## Locks in SQL - A deep dive
<details>
  <summary>How Locks Work in PostgreSQL</summary>
  <br/>

  Locks in PostgreSQL are mechanisms used to control concurrency and prevent data inconsistencies. They ensure that multiple transactions can access and modify data without interfering with each other.

  In PostgreSQL, locks are acquired automatically by the database system whenever a transaction accesses or modified.
  
</details>

<details>
  <summary>Locking Mechanisms:</summary>
  <br/>

  **Explicit Locking:** Manually acquiring and releasing locks using commands like `SELECT FOR UPDATE` and `SELECT FOR SHARE`.

  **Implicit Locking:** PostgreSQL automatically acquires and releases locks based on operations or queries performed.
  
</details>

### Table lock
https://postgres-locks.husseinnasser.com/
<details>
  <summary>Table level lock</summary>
  <br/>

  Table locks apply to entire tables and are used to prevent other transactions from accessing the table in conflicting ways.
  
</details>

<details>
  <summary>Type of locks</summary>
  <br/>

  + AccessShareLock
  + RowShareLock
  + RowExclusiveLock
  + ShareUpdateExclusiveLock
  + ShareLock
  + ShareRowExclusiveLock
  + ExclusiveLock
  + AccessExclusiveLock
  
</details>

<details>
  <summary>Examples</summary>
  <br/>

  
  
</details>

### Row locks
<details>
  <summary>Row level lock</summary>
  <br/>

  Row locks apply to individual rows within a table. They are used to prevent other transactions from modifying or deleting specific rows while they are being accessed.
  
</details>

<details>
  <summary>Type of locks</summary>
  <br/>

  + FOR KEY SHARE
  + FOR SHARE
  + FOR NO KEY UPDATE
  + FOR UPDATE
  
</details>

### Page locks



### Dead locks
