# Notice

The original 64-bit exploit creator is ExodusIntel.
I just converted to 32 bit.  
The following description is the original description.

# Chrome Issue 992914 Sealed/Frozen Element Kind Type Confusion RCE Exploit

This script exploits a type confusion issue in Google Chrome. Tested on Windows 10 x64, Chrome version 76.0.3809.100 and 76.0.3809.132.

* Start chrome with the --no-sandbox argument
* Running the exploit requires hosting the contents of this directory and visiting `exp.html` in Chrome. Shellcode can be replaced by modifying  the `shellcode.js` file. Currently shellcode length is limited to 4KiB.
