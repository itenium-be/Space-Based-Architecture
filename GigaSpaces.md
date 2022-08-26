GigaSpaces
==========

Update `gs-license.txt` in the `Runtime` dir.


```ps1
cd C:\temp\gigaspaces\Runtime\bin
.\gs.bat host run-agent --auto
.\gs.bat container create --count=2 localhost
.\gs.bat space deploy --partitions=2 myDataGrid
```

Management Console: http://localhost:8099/  
Ops Manager: http://localhost:8090/
