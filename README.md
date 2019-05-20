Ping an IP from multiple juniper devices<br>
Requires inventory vars such as:

````
[ping]
device1
device2
device3
device...



[ping:vars]
ansible_connection=netconf
ansible_network_os=junos

