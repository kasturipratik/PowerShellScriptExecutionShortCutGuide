# powerShellShortCutDirectoryChange
Short cut function implementation for power-shell shortcut

Steps to do to create power shell short cut for easier folder navigation or command execute.

1. Locate the folder where windows powershell is installed.

  > ***For Example -- this is where powershell is installed in my computer.*** <br/>
  > C:\Users\ **UserName** \Documents\WindowsPowerShell
   
2. Create a file inside this folder 
  > Microsoft.PowerShell_profile.ps1 -- this is what I named
3. Open the newly created file in notepad++ or any editor to edit.
4. Create java script functions to create short cut navigation or script execution

> **For Example** <br/>
> *Change directory*
``` 
function cngDir{
  cd C:\Users\Default\Documents
} 
```
5. Save the file and now you can use the function name as shortcut to be used to <br/> change driectory from any directory to C:\Users\Default\Documents
  
