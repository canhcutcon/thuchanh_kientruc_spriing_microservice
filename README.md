# thuchanh_kientruc_spriing_microservice
create - department service
create - user service

create - service registry with port 8761
confid application
run localhost: 8761
change link in userservices
localhost:8080 ==> DEPARTMENT-SERVICE
add @LoadBalanced to file UserServiceApplication

API GATEWAY
create api gateway service
run registry-service
run api gateway
run department service
run user service
test postman 
change port department: 8080 to port of apigateway -> 8082 en tet
 
SRPING-CONFIG SERVER
create reponsitory
create config-server 
add file boottrap


thu tu chay file service-registry -> clound-config -? api-gateway -> user || depaartment
