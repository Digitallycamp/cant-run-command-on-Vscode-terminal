# cant-run-command-on-Vscode-terminal

# ERROR : 
PS C:\Users\USER\Desktop\React folder\React> npx create-react-app laura-app
npx : File C:\Desktop\nodejs\npx.ps1 cannot be loaded because running scripts is disabled on this system. For more information, see 
about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:1
+ npx create-react-app laura-app
+ ~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException  
    + FullyQualifiedErrorId : UnauthorizedAcces

# SOLUTION STEP BY STEP



## Run power shell as admin

    -  Windows Start
    -  Search for "Windows Powershell"
    -  Right click Windows Powershell
    -  Click Run as Administrator (Grant in "User Account Control" if shows up)
    -  Type `set-executionpolicy remotesigned`
    -  Select/Type yes [Y]


  
  
