# upstart.conf
Upstart script file to run a NodeJS server as a system service

1. Edit thie file accordingly and copy this file to ```/etc/init/<your-service-name>.conf```

2. Reload system initctl configurations

  ```sudo initctl reload-configuration```

3. Now your NodeJs server can be run as a system service.

  => To start: ```sudo <your-service-name> start```  
  => To stop: ```sudo <your-service-name> stop```  
  => To check status: ```sudo <your-service-name> status```  
