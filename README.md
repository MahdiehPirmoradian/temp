# temp

After installing the 5gs on each virtual machine by running the code: 

```
systemctl status open5gs*
```

We chech if its activated and which functions are installed on it.



then in the core plane by running this code:

```
journalctl -u open5gs--mmed -f
```

I can check if mmed is initialized and if nnating is working.

