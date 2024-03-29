# ECOMMERCE API DOCUMENTATION

Welcome to the eCommerce Backend API documentation. This API allows you to manage products, orders, and customers in your eCommerce platform programmatically.

## Endpoints and resources

$\color{yellow}{POST}$ register-user

> https://ecom-backend-hdop.onrender.com/api/v1/user/register

##### Body raw(json)

```JSON
{
    "firstname":"john",
    "lastname":"dave",
    "email":"abc@gmail.com",
    "password":"123456",
    "role":"admin"
}
```

#### $\color{yellow}{POST}$ User Sign-in

> https://ecom-backend-hdop.onrender.com/api/v1/user/login

##### Body raw(json)

```JSON
{
    "email":"abc@gmail.com",
    "password":"123456"
}
```


#### $\color{yellow}{POST}$  Forget-password

https://ecom-backend-hdop.onrender.com/api/v1/user/forget-password

##### Body raw(json)

```JSON
{
    "email":"abc@gmail.com"
}
```

#### $\color{yellow}{POST}$  Change-password

https://ecom-backend-hdop.onrender.com/api/v1/user/change-password

##### Body raw(json)

```javascript  Body
{
    "password":"123456",
    "newPassword":"1234"
}
```
```javascript Header
{ Authorization : "Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY1ZjgzZGFlYTliNjMyMzdhYTg2OTk2NyIsIm5hbWUiOiJzYW1pa3NoYSIsInJvbGUiOiJidXllciIsImVtYWlsIjoic2FtaWtzaGExM0BnbWFpbC5jb20iLCJleHAiOjE3MTE0NDI4ODksImlhdCI6MTcxMTQzOTI4OX0.xluWu86HSvJlhBYKgTGPXWU3ASIGdVOOsC2MPtNkQw8"}
```





   

    
