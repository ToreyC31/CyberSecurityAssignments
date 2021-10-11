Choose 1 of the top 25 that you have personally put in code you used/submitted. 
 Do a deep dive on  that CWE (read all about it).
Write up (at least) three paragraphs on the CWE, 
how your code was vulnerable to it, and how you could have changed the code to not be vulnerable.  
  
* Be sure to include: 
  * What it is, in your own words
  * Some example CVEs
  * What your personal experience is with it
  * How you could have fixed it (what would you need to have done to not implement this weakness in your code)


Name of CWE:
```
CWE-276: Incorrect Default Permissions
```
How were you vulnerable to it?
How could you have changed what you did to not be vulnerable to it?

```
Incorrect Deault Permissons is a very big weakness in today's day. Incorrect Default
Permissions CWE is when you are installing a package and/or file, and the 
permissions of the file are enabled to allow world-wide edit and/or reading.
This allows hackers or malicous users to be able to read and write to such files
without the the user's knowledge. This is a big deal especially when installing OS's. or other files in which the outside world should not have access to.

A few example CVE's would include:
- CVE-2005-1941 "Executables installed world-writable"
- CVE-2002-1713 "Home Directories installed world-readable"
- CVE-2001-1550 "World-writable log files allow information loss; world-readable file has cleartext passwords."
- CVE-2002-1711 "World-readable Directory" 

