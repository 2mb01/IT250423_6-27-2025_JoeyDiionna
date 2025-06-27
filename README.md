# IT250423_6-27-2025_JoeyDiionna

5 Different learning points in this file

1. To create a Dos file using command prompt firstly we need to create a file
2. secondly i create a folder called work in my C: Drive and call it Work.
3. Then i create a text file in the folder and name it the name of my computer.
4.I then write text in the file to add size to the file.
5.then in command prompt i use different commands that help navigate the computer.


Microsoft Windows [Version 10.0.26100.4351]
(c) Microsoft Corporation. All rights reserved.

C:\Work>dir
 Volume in drive C is Windows
 Volume Serial Number is 8ED5-1D6C

 Directory of C:\Work

06/25/2025  12:28 PM    <DIR>          .
06/25/2025  12:27 PM                 0 pc_joey.txt
               1 File(s)              0 bytes
               1 Dir(s)  819,387,965,440 bytes free

C:\Work>notepad

C:\Work>notepad pc_joey.txt

C:\Work>notepad pc_joey.txt

C:\Work>type pc_joey.txt
This will contain information about this computer so I'm going.

second link:
C:\Work>systeminfo

Host Name:                     A221-PC021
OS Name:                       Microsoft Windows 11 Pro
OS Version:                    10.0.26100 N/A Build 26100
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Member Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              Windows user
Registered Organization:       PEC
Product ID:                    00331-10000-00001-AA020
Original Install Date:         3/24/2025, 5:58:05 PM
System Boot Time:              6/13/2025, 9:06:04 AM
System Manufacturer:           Dell Inc.
System Model:                  OptiPlex SFF Plus 7010
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 183 Stepping 1 GenuineIntel ~2100 Mhz
BIOS Version:                  Dell Inc. 1.23.0, 2/6/2025
Windows Directory:             C:\Windows
System Directory:              C:\Windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  en-us;English (United States)
Time Zone:                     (UTC-05:00) Eastern Time (US & Canada)
Total Physical Memory:         32,457 MB
Available Physical Memory:     17,317 MB
Virtual Memory: Max Size:      34,505 MB
Virtual Memory: Available:     19,495 MB
Virtual Memory: In Use:        15,010 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        networksupport.local
Logon Server:                  \\SRV01
Hotfix(s):                     6 Hotfix(s) Installed.
                               [01]: KB5056579
                               [02]: KB5048779
                               [03]: KB5050575
                               [04]: KB5060829
                               [05]: KB5059502
                               [06]: KB5062862
Network Card(s):               2 NIC(s) Installed.
                               [01]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 2
                                     DHCP Enabled:    No
                                     IP address(es)
                                     [01]: 192.168.56.1
                                     [02]: fe80::4749:236e:17ce:f2bc
                               [02]: Intel(R) Ethernet Connection (17) I219-LM
                                     Connection Name: Ethernet
                                     DHCP Enabled:    Yes
                                     DHCP Server:     192.168.221.1
                                     IP address(es)
                                     [01]: 192.168.221.155
                                     [02]: fe80::de12:2b93:2091:bf8
Virtualization-based security: Status: Running
                               Required Security Properties:
                                     Base Virtualization Support
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                                     APIC Virtualization
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                                     Hypervisor-Enforced Paging Translation
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Work>ipconfig/all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : A221-PC021
   Primary Dns Suffix  . . . . . . . : networksupport.local
   Node Type . . . . . . . . . . . . : Hybrid
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No
   DNS Suffix Search List. . . . . . : networksupport.local

Ethernet adapter vEthernet (Default Switch):

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Hyper-V Virtual Ethernet Adapter
   Physical Address. . . . . . . . . : 00-15-5D-B6-AB-0B
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::e630:f075:4db8:4a19%18(Preferred)
   IPv4 Address. . . . . . . . . . . : 172.20.160.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.240.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 301995357
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-B7-AB-CC-96-E5-36-D3-40
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter Ethernet:

   Connection-specific DNS Suffix  . : networksupport.local
   Description . . . . . . . . . . . : Intel(R) Ethernet Connection (17) I219-LM
   Physical Address. . . . . . . . . : CC-96-E5-36-D3-40
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::de12:2b93:2091:bf8%10(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.221.155(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : Thursday, June 19, 2025 12:46:05 PM
   Lease Expires . . . . . . . . . . : Saturday, June 28, 2025 12:25:24 AM
   Default Gateway . . . . . . . . . : 192.168.221.1
   DHCP Server . . . . . . . . . . . : 192.168.221.1
   DHCPv6 IAID . . . . . . . . . . . : 399283941
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-B7-AB-CC-96-E5-36-D3-40
   DNS Servers . . . . . . . . . . . : 192.168.2.203
                                       192.168.2.205
                                       192.168.2.155
   Primary WINS Server . . . . . . . : 192.168.2.203
   Secondary WINS Server . . . . . . : 192.168.2.205
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Physical Address. . . . . . . . . : 0A-00-27-00-00-06
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::4749:236e:17ce:f2bc%6(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.56.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 168427559
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-B7-AB-CC-96-E5-36-D3-40
   NetBIOS over Tcpip. . . . . . . . : Enabled

C:\Work>

Website that explains how to find the name and information about your computer https://www.youtube.com/watch?v=5gBSS5mHLF8. 
