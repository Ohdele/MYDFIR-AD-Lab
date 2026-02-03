# MYDFIR Active Directory Lab

## Objective
Simulate lateral movement and credential dumping in an Active Directory environment, and detect it in real-time.

## Lab Setup
- Kali Linux: control & logging
- Windows 10 VM: AD user simulation

## Observations
Capture Security Event IDs 4624, 4625, 4648, 4672, 4688, 5140.

## Notes
Track all commands, outputs, and screenshots for GitHub showcase.
[View Output in lab-outputs.txt](lab-outputs.txt)


## Event Notes
- 4624: captured interactive logon by dele0
- 4625: no failed logon for dele0 on 2/3
- 4648: captured explicit credentials by dele0
- 4688: captured process creation (mmc.exe) by dele0
- 5140: captured network share access (IPC$) by dele0
- 4672: no event generated for dele0 on 2/3
