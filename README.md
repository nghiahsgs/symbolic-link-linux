# symbolic-link-linux
symbolic link linux


## Create symbolic link (test002 from test001)
```
ln -s test001 test002
```

## Show symbolic link
```
ls -l
```

```
total 8
drwx------ 3 root root 4096 May 25 03:49 snap
drwxr-xr-x 2 root root 4096 Jun 11 02:59 test001
lrwxrwxrwx 1 root root    8 Jun 11 03:01 test002 -> test001/
```

## remove symbolic link
```
unlink test002
rm test002
```
