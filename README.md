# PFE Tools

Tools and resources used by PFEs

<https://aka.ms/pfe/tools>

## Downloads

* [PerfView](https://github.com/microsoft/perfview/releases)
* [DebugDiag](https://www.microsoft.com/en-us/download/details.aspx?id=49924)
* [SysInternals](https://download.sysinternals.com/files/SysinternalsSuite.zip) - [Docs](https://docs.microsoft.com/en-us/sysinternals/)
  * [ProcessExplorer](https://download.sysinternals.com/files/ProcessExplorer.zip) - [Docs](https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer)
  * [ProcMon](https://download.sysinternals.com/files/ProcMon.zip) - [Docs](https://docs.microsoft.com/en-us/sysinternals/downloads/procmon)
  * [ProcDump](https://download.sysinternals.com/files/ProcDump.zip) - [Docs](https://docs.microsoft.com/en-us/sysinternals/downloads/procdump)
  * [TCPView](https://download.sysinternals.com/files/TCPView.zip) - [Docs](https://docs.microsoft.com/en-us/sysinternals/downloads/tcpview)
* [Log Parser Studio](https://gallery.technet.microsoft.com/Log-Parser-Studio-cd458765)
* [Performance Analysis of Logs (PAL) tool](https://github.com/clinthuffman/PAL/releases)

## [Chocolatey](https://chocolatey.org/)

* Install

    ```powershell
    Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
    ```

* Allow Global Confirmation

    ```powershell
    choco feature enable -n=allowGlobalConfirmation
    ```

* Install [packages](https://chocolatey.org/packages)

    ```powershell
    choco install sysinternals
    choco install cmder
    choco install vscode
    ```