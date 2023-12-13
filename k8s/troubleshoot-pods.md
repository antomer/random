# MySQL DB

```
kubectl run mysql-client --image=mysql:8.0 -it --rm --restart=Never -- /bin/bash
```
connect to db:
```
mysql -h$host -p$port -D$db -u$user -p$pw
```

# Network
```
kubectl run network-tools --image=nicolaka/netshoot -it --rm --restart=Never -- /bin/bash
```