#config-service is on port 8888
# eureka-service is on port 8761
# test-service is on port 8080

Steps:
Start the eureka-service 
Start the config service 
Start the test-service

http://localhost:8761/
Verify all services registered
http://localhost:8888/eureka-service/master
Verify the config
http://localhost:8080/message
From the app file
http://localhost:8080/message1
From the global shared file

