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
- Download for Windows XP
```url
https://github.com/gentilkiwi/mimikatz/releases/
```
The first event to be matched will be the process creation event. Executing the mimikatz.exe binary generates that event, and it can be seen in the EventViewer application in the Sysmon section `(Applications and Services Logs/Microsoft/Windows/Sysmon/Operational)`:
