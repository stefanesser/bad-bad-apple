# bad-bad-apple
A curated list of not properly fixed apple security bugs and attempts to influence disclosure

This list will be filled over the next weeks with instances that we know of.

Insufficiently patched iOS vulnerabilities
------------------------------------------

The following table is work in progress. It shows for every iOS versions (since iOS 6.0) what vulnerabilities
they were still vulnerable to because previous patches were incomplete. (MacOS and OSX table will follow)

| iOS Version    | CVE            | Description |
| -------------- | -------------- | ----------- |
| 6.0            |                | setattrlist() memory corruption (32 bit) 1st fix |
| 6.0.1          |                | setattrlist() memory corruption (32 bit) 1st fix<br />kext_request() infoleak |
| 6.1            |                | setattrlist() memory corruption (32 bit) 1st fix<br />kext_request() infoleak |
| 6.1.2          |                | setattrlist() memory corruption (32 bit) 1st fix<br />kext_request() infoleak |
| 6.1.3          |                | setattrlist() memory corruption (32 bit) 1st fix<br />kext_request() infoleak |
| 6.1.4          |                | setattrlist() memory corruption (32 bit) 1st fix<br />kext_request() infoleak |
| 6.1.6          |                | setattrlist() memory corruption (32 bit) 1st fix<br />kext_request() infoleak |
| 7.0            |                | setattrlist() memory corruption (32 bit) 2nd fix<br />kext_request() infoleak |
| 7.0.2          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />kext_request() infoleak |
| 7.0.3          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />kext_request() infoleak |
| 7.0.4          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />kext_request() infoleak |
| 7.0.6          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />kext_request() infoleak |
| 7.1            |                | setattrlist() memory corruption (32 bit) 2nd fix<br />kext_request() infoleak |
| 7.1.1          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />kext_request() infoleak |
| 7.1.2          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />kext_request() infoleak |
| 8.0            |                | setattrlist() memory corruption (32 bit) 2nd fix<br />mach_port_kobject() infoleak<br />kext_request() infoleak |
| 8.0.1          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />mach_port_kobject() infoleak<br />kext_request() infoleak |
| 8.0.2          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />mach_port_kobject() infoleak<br />kext_request() infoleak |
| 8.1            |                | setattrlist() memory corruption (32 bit) 2nd fix<br />mach_port_kobject() infoleak<br />kext_request() infoleak |
| 8.1.1          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />mach_port_kobject() infoleak<br />kext_request() infoleak |
| 8.1.2          |                | setattrlist() memory corruption (32 bit) 2nd fix<br />mach_port_kobject() infoleak<br /> kext_request() infoleak |
| 8.1.3          |                | setattrlist() memory corruption (32 bit) 2nd fix |
| 8.2            |                | setattrlist() memory corruption (32 bit) 2nd fix |
| 8.3            |                | setattrlist() memory corruption (32 bit) 2nd fix |
| 8.4            |                | setattrlist() memory corruption (32 bit) 2nd fix |
| 8.4.1          |                | setattrlist() memory corruption (32 bit) 2nd fix |
| 9.0            |                |                                          |
| 9.0.1          |                |                                          |
| 9.0.2          |                |                                          |
| 9.1            |                |                                          |
| 9.2            |                |                                          |
| 9.2.1          |                |                                          |
| 9.3            |                |                                          |
| 9.3.1          |                |                                          |
| 9.3.2          |                |                                          |
| 9.3.3          |                |                                          |
| 9.3.4          |                |                                          |
| 9.3.5          | CVE-2016-4655  | PEGASUS Infoleak (actual bug unfixed just one trigger killed) |
| 10.0.1         | CVE-2016-4655  | PEGASUS Infoleak (actual bug unfixed just one trigger killed) |
| 10.0.2         | CVE-2016-4655  | PEGASUS Infoleak (actual bug unfixed just one trigger killed) |
| 10.1           |                |                                          |
| 10.1.1         |                |                                          |
| 10.2           |                |                                          |
| 10.2.1         |                |                                          |
| 10.3           |                |                                          |
| 10.3.1         |                |                                          |
| 10.3.2         |                |                                          |
| 10.3.3         |                |                                          |


Your help wanted
----------------

However we would love to hear from you what instances you know of (with sources) that should be added to the list.
You can either do this in public via GitHub or send a private e-mail to badbadapple@antid0te.com .
