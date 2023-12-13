# troubleshoot mysql

Create a mysql pod and exec into it:
```
kubectl run mysql-client --image=mysql:8.0 -it --rm --restart=Never -- /bin/bash
```