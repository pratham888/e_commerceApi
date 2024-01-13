
# e_commerceApi

To run the project "npm start"

Design an API for an ecommerce platform admin to manage product inventory
- Tech Stack: Node.js &amp; Mongo DB
- Test The API’s using Postman
- Models/Schemas:
- Products [fields: id, name, quantity]
- API to add products to the database
URL [POST]: /products/create

//request
product: {
name: laptop,
quantity: 10
}
//response
data: {
product: {
name: laptop,
quantity: 10
}
}


data: {
products: [
{
id: 1,
name: laptop
quantity: 10
},
{
id: 2,
name: camera
quantity: 5
},

{
id: 3,
name: smartwatch
quantity: 8
},
]
}

{
id: 3,
name: smartwatch
quantity: 8
},
]
}
- API to delete products


// response
data: {
message: “product deleted”
}

hosting link https://ecommerce-api-pratham.onrender.com
