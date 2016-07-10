About Shell Detect
Shell Detect is the FREE tool to detect presence of Shell Code within a file or network stream. You can either provide raw binary file (such as generated from Metasploit [Reference 4]) or network stream file as input to this tool.

These days attackers distribute malicious files which contains hidden exploit shell code. On opening such files, exploit shell code get executed silently, leading to complete compromise of your system . This is more dangerous when the exploit is 'Zero Day' as it will not be detected by traditional signature based Anti-virus solutions.

In such cases ShellDetect may help you to identify presence of shell code (as long as it is in raw format) and help you to keep your system safe.

 
shelldetect
 
Though the new version is more stable than past releases, we recommend running this tool in Virtual Environment (using VMWare, VirtualBox [Reference 2,3]) as it may cause security issues on your system if the input file is malicious.

Currently ShellDetect tool is in experimentation stage and works on Windows XP (with SP2, SP3) only.

 
 
Requirements
ShellDetect requires following components 
Python - Install latest version [Reference 1]
Vmware/VirtualBox (optional) [Reference 2,3]
 
 
Using ShellDetect
Here is the simple usage instructions [refer to screenshot below]
 
Usage: ShellDetect.py file_name
 
You can provide input file as raw binary file or network stream data. Here are the possible examples.
Eg 1: Generate shellcode from Metasploit [Reference 4] in "raw" format and save it in a file. Then feed that file as input to ShellDetect.py.
Eg 2: Send exploit to any server on FTP and capture the traffic using tcpdump/wireshark, save the traffic in binary format and then feed that file to ShellDetect.py
Alternatively you can also download the sample files (password: securityxploded) and play around with the tool.

We recommend running it in Virtual Environment (using VMWare, VirtualBox [Reference 2,3]) as it may cause security issues on your system if the input file is malicious.