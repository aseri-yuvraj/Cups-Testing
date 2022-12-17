# ADDING PRINTERS & CREATING PRINT QUEUES
I used the lpadmin command to create printers.
```
lpadmin -p t -E -v test file:/dev/null
```
I then used the lp command to generate print jobs.
```
lp -d  test <file_name>
```
