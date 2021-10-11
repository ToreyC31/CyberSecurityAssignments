
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
without the the user's knowledge. This is a big deal especially when installing OS's. or other
files in which the outside world should not have access to.

A few example CVE's would include:
- CVE-2005-1941 "Executables installed world-writable"
- CVE-2002-1713 "Home Directories installed world-readable"
- CVE-2001-1550 "World-writable log files allow information loss; world-readable file has cleartext passwords."
- CVE-2002-1711 "World-readable Directory" 

I have some personal experiances with this CWE. In which relates to one of our previous projects
when we were working with teammates. When I was creating files that other's could see, it somehow got created
all to have read/write and execute access. I didn't learn until after submitting files to check on steps that
this issue had occured. If this was a different scenerio, in which was not in a controled environement for school,
this could have lead to a bigger issue, pending the time it took to notice the issue.

This was a mix of user and file creation error. When creating the code, i could have verified that the permissions
were set when building the script. This would make sure that the file would be set upon creation. Chmod'ing the file
after creation even with the permissions being set during creation would help prevent this issue as well. Testing code
before making live is also a big item that i personally could have worked on before running. That way if something does
not work to par, it can be caught and fixed before running to mitigate an issue such as files being world-readable,
occurs

```
