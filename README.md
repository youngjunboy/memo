# memo

(base) C:\Users\user>sqlplus

SQL*Plus: Release 11.2.0.2.0 Production on 금 3월 22 11:08:09 2024

Copyright (c) 1982, 2014, Oracle.  All rights reserved.

Enter user-name: system
Enter password:1234
ERROR:
ORA-28002: the password will expire within 7 days



Connected to:
Oracle Database 11g Express Edition Release 11.2.0.2.0 - 64bit Production

SQL> alter user hr
  2  identified by hr
  3  account unlock;

User altered.

SQL> conn hr/hr;
Connected.
SQL>
