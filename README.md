Ping an IP from multiple juniper devices<br>
Requires inventory vars such as:

````
[ping]
device1
device2
device3
device...
```

```
[ping:vars]<br>
ansible_connection=netconf<br>
ansible_network_os=junos<br>
```
