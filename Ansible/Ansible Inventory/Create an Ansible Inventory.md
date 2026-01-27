#### ***Use To*** build an inventory file for your ansible control node 

#### Prerequisites
- [[Installing Ansible|Install Ansible]]
- **Create an Ansible Project directory on your control node**
#### Additional References
1. [Building An Inventory - Ansible Docs][1]
 
[1]: https://docs.ansible.com/projects/ansible/latest/getting_started/get_started_inventory.html#get-started-inventory
#### See Also
- [[How to Create Ansible Playbooks]]
- [[Ansible inventory.ini vs inventory.yaml]]
****
### *Info*
##### Inventories organize managed nodes in centralized files that provide Ansible with host information and network locations. <sup>[1]</sup>

### Create a Simple Ansible Inventory.ini from the Command Line

#### 1. Create an inventory.ini file in your project root directory

```ad-pscode
collapse: true
	New-Item -ItemType File -Name "<project root dir>\inventory.ini"
```
#### **-OR-**

```ad-bash
collapse: true
	touch <project directory>/inventory.ini 
```

