# Cache-Controller-Design
Using JAVA, Designed a 4-way set associative memory with a page size of 4KB for a computer with a main memory size of 4GB.
The CPU has a data width of 32 bytes with the same cache line size.

The cache controller performing the following reads to the main memory has been written in Java.

Each Read will show a miss in the cache first and then be stored in the cache at the appropriate location

Read 1 to Page 3, set 3
Read 2 to Page 2, set 3
Read 3 to Page 0, set 3
Read 4 to Page 10, set 3
Read 5 to Page 25, set 0
Read 6 to Page 30, set 1
