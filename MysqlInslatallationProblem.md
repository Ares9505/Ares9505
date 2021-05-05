# mysqlclient INSTALLATION ERROR SOLUTION:


## Error 1/ OSError: mysql_config not found
```shell
$ sudo apt-get install libmysqlclient-dev -y
```

## Error 2/ unable to execute ‘x86_64-linux-gnu-gcc’: No such file or directory
```shell
$ sudo apt-get install gcc -y
```

## Error 3/ MySQLdb/_mysql.c:46:10: fatal error: Python.h: No such file or directory
```shell
sudo apt-get install python3-dev -y
```
