We learned about physical and logical structures hat are in place in any database system.

The different types of database system, as well as the CAP problematic, which says that a system can either be:
* consistency 
* partition tolerance 
* availability 

Generally, the instance which is created for a user/dev to interact with a buffer, has a shared data pool and a buffer, for any changes that will be made.
One does need CHECKPOINTS tho, at which the changes are applied to the database.
We went over the general architecture and how the mechanical and logical problems that come with storing and manipulating data.

Parallelity for example, describes processes that are simultanious and codependant, concurrency the independent parallel calculation.
