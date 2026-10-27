TASK:-  NEED TO CREATE A REST SERVICE WHICH --> RETURN USER  ALREADY HAVE THE ORDERED (SUBSCRIBE/CHOICE SELECETD) AND THE OPTION AVAILIBLE FOR SUBCRIPTION TO THE USER 

IMPLEMEATTAION -  SUMMARY
endpoint :- GET http://localhost:8080/api/v1/orders/overview?userId=101
request : userId
response :userid , existingOrders, availibleOrder
classes required for in memory response
controller
service
dtos
GET http://localhost:8080/api/v1/orders/overview?userId=102`
- `GET http://localhost:8080/api/v1/orders/overview?userId=999` exception user not found  condition
