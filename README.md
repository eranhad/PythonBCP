# PythonBCP
Python bulk copy program to export data from SQL Server databases to csv

example code:
```
python pybcp.py servername databasename tablename D:\filename -p <progress indicator> -s <number of lines per file>


python pybcp.py localhost stackoverflow PostHistory D:\output -p 10000000 -s 10000000
```

![image](https://user-images.githubusercontent.com/77159509/142869448-71ac1331-b4f7-41f5-bb9a-0d2772c029ff.png)
