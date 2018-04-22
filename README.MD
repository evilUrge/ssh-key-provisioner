# SSH Key provisioner  
---  
Simple python tool for provisioning ssh keys.

## How to install and start?  
---  
    pip install -r requirements.txt
    python run.py --help
  
### Arguments  
---  
1. ```-i``` _OR_ ```--identity_file``` - Location of the machine identity file(private key).  
2. ```-k``` _OR_ ```--keys_file``` - Set the location for the key json file(default in the same folder).  
3. ```-s``` _OR_ ```--hosts_file``` - Set the location for the hosts json file(default in the same folder).


#### COMING SOON
---
 - Support in fetching list of droplets from DigitalOcean and Vultr.
 - Providing password instead of the user private key.

---

> _disclaimer: I know that you can use Ansible to provision ssh keys; this is just a fast simpler way_
