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

## Table locks - A deep dive

<details>
  <summary>How Locks Work in PostgreSQL</summary>
  <br/>

  In PostgreSQL, locks are acquired automatically by the database system whenever a transaction accesses or modified.
  
</details>
