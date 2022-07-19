# UNIX commands

Here are the list of UNIX commands that I have learned through experience and from senior developers.

Get the current user
```console
mikebernal@laptop10:~$ whoami
mikebernal
```

Display the amount of available disk space for file systems.
```console
mikebernal@laptop10:~$ df -h
Filesystem            Size  Used Avail Use% Mounted on
C:/Program Files/Git  477G  167G  311G  35% /

```
Enter an elevated secured shell
```console
mikebernal@laptop10:~$ sudo -s
root@laptop10: 
```

Allow user to gain disk usage information quickly of the current directory
```console
mikebernal@laptop10:~$ du -sh
mikebernal
```

Display available disk space starting from the current directory down to its subdirectories
```console
mikebernal@laptop10:~$ du -sh *
mikebernal
```

Find the largest directories in order:

```code
sudo du -a /var/lib/docker | sort -n -r | head -n 10
```
