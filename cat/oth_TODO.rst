=====
To Do
=====

TODO: incorporate these links: 

https://sqlsailor.com/2016/11/07/agdisksector/ 

http://www.sqlskills.com/blogs/erin/trace-flag-information-in-query-plans/ 

https://blogs.msdn.microsoft.com/bobsql/2016/11/08/how-it-works-it-just-runs-faster-non-volatile-memory-sql-server-tail-of-log-caching-on-nvdimm/

TODO: catch up on latest hotfixes (for 2014 SP2 CU2), any other releases, TF 2389 additions (see my email), and BWard's 2016 Hekaton slides

TODO: Evaluate combining the following 3 categories since they are all so tightly coupled. Use a special division of flags found only for this super-category.

These categories still need to be pulled in from the Word doc TODO: SQL 2000 Optimization/Query Performance Fixes TODO: SQL 2000 Query Execution TODO: Pre-SQL 2000 Flags TODO: TF 4199 and related TODO: Non-TF4199 Query Performance/Execution fixes TODO: Mis-labeled, unable to find links, Other

Remove these files from my repo, never used OLD: Query Compilation (Info only) and Stats Object-related OLD: Query Compilation Behavioral (Cardinality Estimation only)

Review these links:

https://support.microsoft.com/en-us/kb/3189645

https://support.microsoft.com/en-us/kb/3194716 

https://support.microsoft.com/en-us/kb/3195813 

https://support.microsoft.com/en-us/kb/3199171 

https://support.microsoft.com/en-us/kb/3194717 

https://support.microsoft.com/en-us/kb/3182545 

https://support.microsoft.com/en-us/kb/3164398 

https://support.microsoft.com/en-us/kb/3194718 

https://support.microsoft.com/en-us/kb/3194714 

https://support.microsoft.com/en-us/kb/3194722 

https://sqlperformance.com/2016/11/sql-server-2016/big-deal-sp1 

I need to check out the release services link. Also, smoewhere there is a list of TFs and the new USE HINT options they map to, that I need to record.

https://blogs.msdn.microsoft.com/sqlreleaseservices/sql-server-2016-service-pack-1-sp1-released/

https://blogs.msdn.microsoft.com/sql_server_team/query-progress-anytime-anywhere/

https://support.microsoft.com/en-us/kb/3210239?sd=rss&spid=17645

http://sql-sasquatch.blogspot.com/2016/12/retrieve-recent-sql-server-stats-update.html

https://sqlserverscotsman.wordpress.com/2016/12/05/trace-flag-4199-query-optimiser-hotfixes/

https://support.microsoft.com/en-us/kb/3198846

https://blogs.msdn.microsoft.com/sqlcat/2016/12/08/improve-query-performance-on-memory-optimized-tables-with-temporal-using-new-index-creation-enhancement-in-sp1/



TF 3459 disables parallel redo according to Anthony Nocentino. (I have a screenshot of the Twitter exchange in my "bolex")

https://support.microsoft.com/en-us/help/4010261/sql-server-2016-improvements-in-handling-some-data-types-and-uncommon-

Fantastically-good article (that mentions TF 3656) by Andreas Wolter on diagnosing slow perf with advanced analysis using XEvents, WinDbg, and Wireshark.
http://www.sqlservercentral.com/blogs/andreas-wolter-sql-server-bi-blog-english-german/2017/02/02/where-is-that-preemptive-wait-coming-from-database-ownership-and-performance-a-journey-through-sql-server-internals-with-xevents-windbg-and-wireshark/


Good demonstration of TF 2453:
https://www.brentozar.com/archive/2017/02/using-trace-flag-2453-improve-table-variable-performance/

Review Konstantin Taranov's post on SSC:
http://www.sqlservercentral.com/articles/trace-flag/152989/?utm_source=SSC&utm_medium=pubemail

TF 139:
https://justdaveinfo.wordpress.com/2017/02/27/sql-server-2016-upgrading-to-compatability-level-130trace-flag-139-and-additional-one-off-dbcc-checks/

https://blogs.msdn.microsoft.com/bobsql/2017/05/23/how-it-works-sql-server-deadlock-trace-flag-1222-output/

TF 176 (disables computed column expansion along with some other nuanced behavior). Great Paul White article.
https://sqlperformance.com/2017/05/sql-plan/properly-persisted-computed-columns

https://www.sqlskills.com/blogs/erin/query-store-trace-flags/
