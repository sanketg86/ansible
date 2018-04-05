# ansible
- Ansible Setup on xxx.xxx.xxx.xxx.
- Create cut the VM from template and Setup as below requirment. 

                - Web Server
                                - Apache Configuration
                                - Info Sec proposed settings
                                - IT proposed Settings
                                - Add Server in ICINGA for monitoring
                                
                - APP Server
                                - User Management ( sanket1 / sanket )
                                - Configure application ( Tomcat / Wildfly )
                                - Configure JAVA
                                - Info Sec proposed settings
                                - IT proposed Settings
                                - Add Server in ICINGA for monitoring
                                
                - DB Server
                                - User Management
                                - Configure Oracle
                                - Info Sec proposed settings
                                - IT proposed Settings
                                - Add Server in ICINGA for monitoring
                                
- Just need to run below script and follow the instructions.  Server will cut from template and configure as instructed. 
                ansible-setup
