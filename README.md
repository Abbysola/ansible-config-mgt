# ansible-config-mgtc

### checking

### checking changes with ansible config artifact

### Ansible dependencies
sudo apt install python3-pip
python3 -m pip --version
which pip3 
sudo ln -s /path/to/pip3 /usr/bin/pip3 #if its not located in /usr/bin/pip3
python3 -m pip install --upgrade setuptools
python3 -m pip install --upgrade pip
python3 -m pip install PyMySQL
python3 -m pip install mysql-connector-python
python3 -m pip install psycopg2==2.7.5 --ignore-installed

-For Postgresql Database
ansible-galaxy collection install community.postgresql

### switch to root
sudo su -
