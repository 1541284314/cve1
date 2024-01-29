[https://github.com/CouchCMS/CouchCMS](https://github.com/CouchCMS/CouchCMS/releases/tag/v2.4)    github address

CouchCMS-2.4 vulnerability details
Invoke this enhanced user interface
The total number of permissions is super admin
           administrator
           Admin User (Special)
           Admin users
I'm going to show you some examples
Vertical hyperextension
Test User (Admin Privileges) Maliciously Using Admin (Super Admin Privileges) Add Admin Privileges to Create Peer test1 (Admin Privileges)
The first step is to add test1 with admin
Get the request body and discard the request packet
![image](https://github.com/1541284314/cve1/assets/115146404/a696b3dc-aba1-4bf8-8820-6353c96ee810)
The second step is to use test to add users of the same level as test1
and use the request body that just got admin
![image](https://github.com/1541284314/cve1/assets/115146404/5f6a092e-38de-4a58-9918-3df1e7a6bf25)
The status code of the response packet is sometimes 302 and sometimes 200, but it does not affect the result.
![image](https://github.com/1541284314/cve1/assets/115146404/dcc127d8-047e-47ee-8e9e-b575b8483568)

