# OPS sysmon

- - - Install Sysmon + mimikatz.exe:

Launch CMD with administrator privileges in the Sysmon folder and install the file with the following command:
```cmd
Sysmon64.exe -accepteula -i sysmon.xml
Sysmon64.exe -i sysmon.xml
```
# Uninstall
```cmd
cd C:\path\of\your\sysmon\source>
Sysmon64.exe -u
```
