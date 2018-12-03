# ansible-ise
Variety of small Ansible and ISE playbooks

##
The script deletes an endpoint and shuts down the port of that endpoint.
You must put the MAC address and switchport into the playbook
The inventory contains one IOS switch and one ISE node
It does a REST query of the MAC to get the endpoint ID, and then deletes the endpoint
 
