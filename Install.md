# INSTALLING CUPS
The first step to clone the cups repository through the following command:

``` 
git clone https://github.com/OpenPrinting/cups.git
```

Once the project was cloned, I moved into the cups directory and configured CUPS for my system through the usual "configure" script in the main CUPS source directory, using the following command:
```
./configure
````
After configuration, wrote the make command. Tested it and installed the same using:
```
make 
sudo make install
```
Start the CUPS service using:
```
sudo service cups start
```
