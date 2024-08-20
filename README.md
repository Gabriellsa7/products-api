# Product API

## Description

This project is an API for managing products developed with Java and Spring Boot 3. The API allows for creating, reading, updating, and deleting products.

## Features

- **Create Products:** Add new products to the system.
- **List Products:** View all products in the system.
- **Product Details:** Retrieve detailed information about a specific product.
- **Update Products:** Modify the information of an existing product.
- **Delete Products:** Remove products from the system.

## Technologies Used

- **Java 17**
- **Spring Boot 3**
- **Spring Data JPA**
- **H2 Database (or another database of your choice)**
- **Maven/Gradle (depending on the build system used)**

## Endpoints

### Create Product

`POST /products`

### List Products

`GET /products`

### Get Product

`GET /products/{id} `

### Update Product

`PUT products/{id}`

### Delete Product

`DELETE /products/{id}`

#### Request Body

```json
{
  "name": "Product Name",
  "price": 100.00
}
