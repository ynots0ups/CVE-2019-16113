# CVE-2019-16113

This is a python implementaiton PoC for the Bludit Directory Traversal Image File Upload Vulnerability

CVE-2019-16113
Bludit 3.9.2 allows remote code execution via bl-kernel/ajax/upload-images.php because PHP code can be entered
with a .jpg (or .png) file name, and then this PHP code can write other PHP code to a ../ pathname.

Original credit:
christasa - Original discovery
sinn3r - Metasploit Module

https://www.exploit-db.com/exploits/47699
