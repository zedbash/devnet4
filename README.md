DEVNET Project 4


Tree:

├── ansible.cfg - Ansible configuration

├── backups - Backups from config backup playbook

├── documentation

│   ├── network_diagram.md

│   └── testing_results.md

├── inventory.ini - Inventory of devices under routers and switches section

├── playbooks

│   ├── 01_verify_connectivity.yml - verifies connectivity between router and switch

│   ├── 02_basic_config.yml - configures hostname, domain name, and SSH on router and switch

│   ├── 03_vlan_config.yml - Configures vlan 10 and 20 on switch

│   └── 04_backup_config.yml - backups configurations to backups folder above

└── README.md
