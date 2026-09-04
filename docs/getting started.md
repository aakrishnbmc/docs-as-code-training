# Getting started
Add content for Getting started.

## Explain SQL statements
Remove space.

In SQL Explorer, running an **Explain** job explains the steps that the Db2 optimizer must take to execute the relevant SQL statements. You can run an Explain job to see an explanation of any of the following types of statements:

- All explainable SQL statements in a plan or package
- SQL statements stored outside the Db2 catalog (referred to as a DBRM library Explain, or DBRMLIB Explain)
- A single SQL statement (online or in batch mode)

The Explain option includes the cost and filter factor for each process step of the SQL statement. This capability enables the DBA or developer to quickly determine which part of the query is estimated to consume the most resources.

## Compare SQL statements

The **Compare** option compares versions of plans or packages through historic baselines (Explain results) that you created with the Explain option. Running a Compare job compares the Explain results for two different versions of a plan or package.
