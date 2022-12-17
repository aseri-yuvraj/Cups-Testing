# ADDING COMMENTS AND PRINTING THEM
I added some notes to the cupsFilePrintf() function, which was located in the scheduler's log.c file. I marked the function with a note. Following the modification of the file. Enter the make and make install commands once again.
```
make
make install
```
then start the cups service again by using
```
sudo service cups start
```
## Here is modified accesslog

```
 localhost - - [17/Dec/2022:21:09:13 +0530] "POST / HTTP/1.1" 401 91 CUPS-Get-Devices successful-ok
Yuvraj contributed this remark  
 localhost - - [17/Dec/2022:21:09:13 +0530] "POST /admin/ HTTP/1.1" 401 60 - -
Yuvraj contributed this remark  
 localhost - - [17/Dec/2022:21:09:13 +0530] "POST /admin/ HTTP/1.1" 200 60 - -
Yuvraj contributed this remark  
 localhost - - [17/Dec/2022:21:14:18 +0530] "POST /admin/ HTTP/1.1" 401 279 CUPS-Add-Modify-Printer successful-ok
Yuvraj contributed this remark  
 localhost - yuvraj [17/Dec/2022:21:14:18 +0530] "POST /admin/ HTTP/1.1" 200 279 CUPS-Add-Modify-Printer successful-ok
Yuvraj contributed this remark  
 localhost - - [17/Dec/2022:21:15:29 +0530] "POST / HTTP/1.1" 401 75 CUPS-Get-Devices successful-ok
Yuvraj contributed this remark  
 localhost - yuvraj [17/Dec/2022:21:15:29 +0530] "POST / HTTP/1.1" 200 1760 CUPS-Get-Devices -
Yuvraj contributed this remark  
 localhost - - [17/Dec/2022:21:16:03 +0530] "POST / HTTP/1.1" 200 5294480 CUPS-Get-PPDs -
Yuvraj contributed this remark    
```
