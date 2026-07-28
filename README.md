wdk-playground
==============
<kbd>[**vscode-web-action**](https://github.com/dirkarnez/vscode-web-action/actions/workflows/vscode-web.yml)</kbd><br>

Based on [manurautela/findwdk-simple: Simple driver using FindWdk for building windows driver with cmake from cmdline.](https://github.com/manurautela/findwdk-simple)
- [building windows driver with cmake and wdk from cmdline - let’s start walk @CR3](https://manurautela.github.io/driver,/wdk,/cmake,/build,/windows/building-windows-driver-with-cmake-and-wdk-cmdline)

### Commands
- `winget install -e --id Microsoft.WindowsSDK.10.0.26100`
- `winget install -e --id Microsoft.WindowsWDK.10.0.26100`
- `msbuild /t:clean /t:build .\xxx.sln /p:Configuration="Debug" /p:Platform=x64 /p:TargetVersion="Windows10"`

### WDK
- [Install the WDK using NuGet - Windows drivers | Microsoft Learn](https://learn.microsoft.com/en-us/windows-hardware/drivers/install-the-wdk-using-nuget)

### Tutorials
- [Write a Hello World Windows Driver (Kernel-Mode) - Windows drivers | Microsoft Learn](https://learn.microsoft.com/en-us/windows-hardware/drivers/gettingstarted/writing-a-very-small-kmdf--driver)
- [From Sample Code to Production Driver - What to Change in the Samples - Windows drivers | Microsoft Learn](https://learn.microsoft.com/en-us/windows-hardware/drivers/gettingstarted/from-sample-code-to-production-driver)
- [Write a UMDF 2 Based on a Template - Windows drivers | Microsoft Learn](https://learn.microsoft.com/en-us/windows-hardware/drivers/gettingstarted/writing-a-umdf-driver-based-on-a-template)
- [Write a Universal Windows Driver (KMDF) Based on a Template - Windows drivers | Microsoft Learn](https://learn.microsoft.com/en-us/windows-hardware/drivers/gettingstarted/writing-a-kmdf-driver-based-on-a-template)
- [使用EWDK编译windows driver - maojun1998 - 博客园](https://www.cnblogs.com/maojun1998/p/13685779.html)
