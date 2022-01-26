 1. Open regedit
 2. Goto ```Computer\HKEY_CURRENT_USER\Software\Classes\CLSID```
 3. Create key ```{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}```
 4. Select the newly created key
 5. Create key ```InprocServer32```
 6. Select the newly created key
 7. Dbl click on DefaultValue
 8. Click enter The value should change from unset to empty
 9. Open task manager
 10. Right click on "Windows Explorer"
 11. Select "Restart"
