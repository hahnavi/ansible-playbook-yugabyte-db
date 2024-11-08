# Ansible Playbook to setup YugabyteDB Cluster

## Prerequisites

* Ansible
* Python 3
* 3 or more servers with Ubuntu

## Run Playbook

1. Clone the repository:
   ```bash
   git clone https://github.com/hahnavi/ansible-playbook-yugabyte-db.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd ansible-playbook-yugabyte-db
   ```
3. Edit the `inventory.ini` file to specify the IP addresses of your servers.
4. Run the playbook:
   ```bash
   ansible-playbook playbook.yml
   ```
