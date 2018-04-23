Data (fictitious) collected for 6 months:  5/2017 - 10/2017

device_info.csv (~156k records)
* Fields: id, date, user, pc, activity (connect/disconnect)
* Tracks use of removable storage media (e.g. thumb drives)
* Some connect(s) may be missing disconnect(s), since machine may be turned off without a proper disconnect. 

email_info.csv (~370k records)
* Fields: id, date, to, from, size (bytes), attachment_count
* Emails can have multiple recipients

employee_info.csv (~6k records)
* Fields: month, employee_name, user_id, email, role, supervisor
* Record of who is employed at the beginning of each month, approximately 1000 employees

HTTP_info.csv (~860k records)
* Fields: id, date, user, pc, url
* Web pages visited

logon_info.csv (~313k records)
* Fields: id, date, user, pc, activity (Logon/Logoff)
* Logoff requires preceding logon
* Screen unlocks are recorded as logons. Screen locks are not recorded.
* Each user has an assigned machine, but can share with others.
* Some machines are shared in a computer lab room. 
* Some of the users are IT administrators and access many machines.

Additional Note:
Field ids are unique within a .csv file but are not necessarily unique across all files.


