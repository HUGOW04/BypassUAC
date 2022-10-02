# BypassUAC

User Account Control (UAC) is a mandatory access control enforcement feature introduced with Microsoft's Windows Vista and Windows Server 2008 operating systems, with a more relaxed version also present in Windows 7, Windows Server 2008 R2, Windows 8, Windows Server 2012, Windows 8.1, Windows Server 2012 R2, Windows 10, and Windows 11. It aims to improve the security of Microsoft Windows by limiting application software to standard user privileges until an administrator authorises an increase or elevation. In this way, only applications trusted by the user may receive administrative privileges and malware are kept from compromising the operating system. In other words, a user account may have administrator privileges assigned to it, but applications that the user runs do not inherit those privileges unless they are approved beforehand or the user explicitly authorises it.

UAC uses Mandatory Integrity Control to isolate running processes with different privileges. To reduce the possibility of lower-privilege applications communicating with higher-privilege ones, another new technology, User Interface Privilege Isolation, is used in conjunction with User Account Control to isolate these processes from each other. One prominent use of this is Internet Explorer 7's "Protected Mode".

Operating systems on mainframes and on servers have differentiated between superusers and userland for decades. This had an obvious security component, but also an administrative component, in that it prevented users from accidentally changing system settings.

Early Microsoft home operating-systems (such as MS-DOS, Windows 95-98 and Windows Me) did not have a concept of different user-accounts on the same machine. Subsequent versions of Windows and Microsoft applications encouraged the use of non-administrator user-logons, yet some applications continued to require administrator rights. Microsoft does not certify applications as Windows-compliant if they require administrator privileges; such applications may not use the Windows-compliant logo with their packaging.

## How it works
BypassUAC uses the attack method — an elevated COM interface. The registry key HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\UAC\COMAutoApprovalList contains a list of CLSIDs that tell UAC to not prompt for elevation when creating an interface from any of the listed CLSIDs.

## Legal warning
Software can by use only to educationals targets. If you will use this like real virus, you could go to jail. Author do not responsible for the misuse of the software by others.
