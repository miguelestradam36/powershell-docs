# Windows Batch Files
## Overview :hammer:

Windows Batch Files for *Windows system automation* and *Automation of different processes execution*.

---

| Developer | Action |
| ----------- | ----------- |
| Miguel Estrada Murillo | Windows Batch Files Quick Overview|

![Windows Bat file icon](img/bat-file-icon.png)

From **CMD** commands to running different languages, tests or applications in a single click. 


    The following documentation is a brief summarry upon what can be done with Windows Batch Files.

---

## Example :mag:

Before starting...

    To check your Windows version and build number, select Windows logo key + R, type winver, select OK. You can update to the latest Windows version by selecting
    
`Start > Settings > Windows Update > Check for updates.`

Step by step guide:
1. Run the following command on Powershell under **admin** priviliges: `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux`
2. Then, under the same environment, run `wsl --install`

#### You should be good to go... but if not

    The above command only works if WSL is not installed at all, if you run wsl --install and see the WSL help text, please try running:

`wsl --list --online` to see a list of available distros and run `wsl --install -d <DistroName>` to install a distro.