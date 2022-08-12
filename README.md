This repository contains a set of object and library files that can be used to
reproduce a hang issue in Microsoft link.exe (from Visual Studio 2019 or 2022).

To reproduce the hang, ensure `vcvars.bat` has been run to setup the compiler
and linker environment variables, then run either `reproduce.bat`, or:

```
link @reproduce.rsp
```
