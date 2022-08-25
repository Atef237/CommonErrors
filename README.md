# CommonErrors
Error recording and how to solve it


# title of error
### The error is currently visible
```
the error
```
###### sample brief of the error 
solution of error
<br>
1- ................
<br>
2- ................
<br>
3- ................

<br>

# Error in image upload using PHP GD Library
### The error is currently visible
```
PHP Warning:  PHP Startup: Unable to load dynamic library '/usr/lib/php5/20090626/gd.so' - /usr/lib/php5/20090626/gd.so: cannot open shared object file: No such file or directory in Unknown on line 0
```

###### The reason for this problem is that part of the php.ini file is not activated and this solution works with windows

1- enable gd in php.ini - search for:
```
;extension=php_gd2.dll
```
2- shut down your pc
<br>
3- Turn on your computer
