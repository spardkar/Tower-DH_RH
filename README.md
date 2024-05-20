Tower disaster recovery:

Tower disaster recovery play book is used for restoring configuration incase AWX instance is lost. The Ansible play book gets configuration from config folder for each role and execute them sequentially. 


Main play book 


Main play book uses ansible collection. Each role uses config for specific function configured in yml. It then executes sequentially. Ansible collection uses REST API and process the request for specific role and build the configuration. 



Configuration 

All configurations are defined for each function. Config.  Files are written in yml and syntax is  used as defined by  Ansible collection. 




Ansible collection link: 

https://github.com/redhat-cop/tower_configuration
