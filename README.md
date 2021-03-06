# Apex-Classes

##

Apex uses Java-like syntax and acts like database stored procedures.  Apex enables developers to add business logic to system events, such as button clicks, updates of related records, Visualforce pages, etc.

As a language, Apex is:
 * Hosted - Apex is saved, compiled, and executed on the server - the Force.com platform.
 * Automatically upgradeable - Because compiled code is stored as metadata in the platform, Apex is automatically upgraded as part of Salesforce releases.
 * Object oriented - Apex supports classes, interfaces and inheritance.
 * Strongly typed - Apex validates references to objects at compile time.
 * Multitenant aware - Because Apex runs in a multitenant platform, it guards closely against runaway cod by enforcing limits, which prevents code from monopolizing shared resources.
 * Integrated with the database - It is straightforward to access and manipulate records.  Apex provides direct access to records and their fields, and provides statements and query languages to manipulate those records.
 * Data focused - Apex provides transactional access to the database, allowing you to roll back operations.
 * Apex is based on Java idioms (a construction or expression of one language whose parts correspond to elements in another language).
 * Easy to test - Apex provides built-in support for unit test creation, execution, and code coverage.  Salesforce ensures that all custom Apex code works as expected by executing all unit tests prior to any platform upgrades.
 * Versioned - Custom Apex code can be saved against different versions of API.

<img src="https://4.bp.blogspot.com/-swofQLY36Is/V3YYOVJGw6I/AAAAAAAAANc/FLR4_IyWCHMHod5avyQMMW0oQqe3q1d6ACLcB/s640/202.png" align="center" width="1000">

## Apex Language Highlights

Like other object-oriented programming languages, Apex supports constructs like single inheritance, interfaces, and some template support.  

 Execution Context has two characteristics:
   - It defines the scope and lifetime of statics variables.
   - It defines the context for those governor limits that are reset between execution contexts.
   
 Key facts:
   - Static variables are maintained throughout an execution context, and are unique to an execution context.
   - Many (but not all) limits are reset between execution context.  For example, if governor limits restrict you to 100          database queries in an execution context, each execution context can have 100 database queries.  
   - You can know when execution context start.  Generally, you dont know when it ends.


## Quick Links
 * [Advanced Apex Programming](http://advancedapex.com/samplecode/)
