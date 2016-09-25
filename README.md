# CrashRpt
forked from http://crashrpt.sourceforge.net/

Only minor modifications at the moment as we have moved away from our heavily modified version at
https://code.google.com/archive/p/crashrptex/ after the orignal allowed for continuation and added many
other valuable features.

CrashRptEx also contained dealing with exceptions being swallowed in 32bit applications running on
64bit platforms (see http://support.microsoft.com/kb/976038 and http://tinyurl.com/gmkpdgr for details).
It checked for the presence of the hotfix and enabled it and provided means to wrap the MFC windows 
prodecure to catch exceptions prior to "Dr. Watson" or prior to it being silently discarded by the 
original Windows Procedure. 
CrashRptEx is now an unintruisive "addition" to the original CrashRpt.


