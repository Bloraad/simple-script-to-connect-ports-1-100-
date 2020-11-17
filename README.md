# simple-script-to-connect-ports-1-100-
### Write a simple script to connect from ports 1 - 100:
```bash
#!/bin/bash
for port in {1..100}
do
    nc 10.10.10.10 -p $port
done
```
### script for ssh
```bash
#!/bin/bash
for port in {2500..4500}
do
    ssh -i id_rsa hades@10.10.10.10 -p $port
done
```
