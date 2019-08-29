WooliesX assignment have been uploaded  to the following URL on Azure  as a Cloud Service:

http://wooliesxassignment.cloudapp.net/

1) Following is the endpoint for exercise 1

http://wooliesxassignment.cloudapp.net/api/WooliesX/user/


2) Following is the endpoint for exercise 2

For sort option low 

http://wooliesxassignment.cloudapp.net/api/WooliesX/products/sort?sortOption=low


For sort option high 

http://wooliesxassignment.cloudapp.net/api/WooliesX/products/sort?sortOption=high


For sort option ascending

http://wooliesxassignment.cloudapp.net/api/WooliesX/products/sort?sortOption=ascending

For sort option descending

http://wooliesxassignment.cloudapp.net/api/WooliesX/products/sort?sortOption=descending


For sort option descending

http://wooliesxassignment.cloudapp.net/api/WooliesX/products/sort?sortOption=descending

For sort option recommended

http://wooliesxassignment.cloudapp.net/api/WooliesX/products/sort?sortOption=recommended


3) Following is the end point for exercise 3

http://localhost:61592//api/WooliesX/products/trolleyTotal


and the body request 


{
  "products": [
    {
      "name": "Test A",
      "price": 230
    }
  ],
  "specials": [
    {
      "quantities": [
        {
          "name": "Test A",
          "quantity": 2
        }
      ],
      "total": 2
    }
  ],
  "quantities": [
    {
      "name": "Test A",
      "quantity": 1
    }
  ]


Code has been uploaded to git with out packages, which can be restored using nuget packages. 