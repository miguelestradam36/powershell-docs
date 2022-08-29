# Windows Batch Files Documentation :book:
## Overview :dart:
---

| Developer | Action |
| ----------- | ----------- |
| Miguel Estrada Murillo | Description of what Batch Files are and how Powershell can be used. |

    The following documentation is a brief summarry upon what can be done with the Powershell and Batch files.

Before starting:

**Windows Batch Files** are used for the following:.

- [x] Scripting in the Windows Operating System
- [x] Scripting in DOS
- [x] Run a single command or multiple commands at a time
- [x] Execute series of tasks on the local or remote machines
- [x] Run a single command or multiple commands at a time

![Windows Batch File icon](img/batch-file.jpg)

Even though **PowerShell** and **Batch** are different languages, both can be integrated into each other and helps to call and execute each other tasks

---

To call the PowerShell script from the Batch file we can use the below syntax in the Batch file: `Powershell.exe -ExecutionPolicy Unrestricted -command "PowerShell file path"`