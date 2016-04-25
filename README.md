# https://github.com/krkrz/krkrz/issues/226 test script

## contents

* startup.tjs  
  an entry point of test scripts
* TestClass.tjs  
  define a base class for general test
* TestForSyntax.tjs  
  main test class for #226

## how to run
If your directories are like:
```
./
 └ krkrz
    ├ bin
    │  └ win32
    │     └ tvpwin32.exe
    └ test_scripts
       └ issue226
          ├ startup.tjs
          ├ TestClass.tjs
          └ TestForSyntax.tjs
```
then you can run test:
```
$ krkrz/bin/win32/tvpwin32.exe ../../test_scripts/issue226
```
(you need to pass relative directory path from executable file).
