# Product Catalog API Documentation

This project provides documentation for a sample RESTful Product Catalog API.  
The API allows applications to create, retrieve, update, and delete product information.

---

## Project Objective

This project demonstrates the design and documentation of a RESTful Product Catalog API.

The API supports complete CRUD operations such as creating products, retrieving product details, updating product information, partially modifying product fields, and deleting products.

The documentation includes request examples, response formats, authentication requirements, HTTP status codes, and common error scenarios to help developers understand how to integrate and use the API effectively.

---

## Features Covered

- RESTful API documentation for Product Catalog Management
- CRUD operations support (GET, POST, PUT, PATCH, DELETE)
- Bearer Token Authentication handling
- Request and response JSON examples
- HTTP status code documentation (200, 201, 204, 400, 401, 404)
- Path parameters and query parameters usage
- Pagination support in product listing
- Error response handling scenarios

---

## API Endpoints Summary

| Method | Endpoint | Description |
|--------|---------|------------|
| GET | /products | Retrieve list of products |
| GET | /products/{id} | Retrieve product details |
| POST | /products | Create a new product |
| PUT | /products/{id} | Update complete product details |
| PATCH | /products/{id} | Partially update product fields |
| DELETE | /products/{id} | Delete a product |

---

## Authentication

All API endpoints require authentication using a Bearer Token.

Clients must include the following header in every request:

Authorization: Bearer <access_token>

If the token is missing or invalid, the API will return a *401 Unauthorized* response.

---

## Common Error Responses

The API may return the following error responses:

- *400 Bad Request* – Invalid or missing request data  
- *401 Unauthorized* – Missing or invalid authentication token  
- *404 Not Found* – Requested product resource does not exist  

These error responses help developers understand possible failure scenarios during API integration.

---

## Tools and Technologies Used

- Postman (API testing and documentation publishing)
- REST API principles
- JSON data format
- GitHub (documentation hosting and version control)
- HTTP methods and status codes

---

## Key Learning Outcomes

- Understanding RESTful API architecture and endpoint design
- Writing developer-friendly API documentation
- Documenting request parameters and response structures
- Handling authentication and authorization concepts
- Explaining HTTP status codes and error scenarios
- Publishing API documentation using Postman
- Managing documentation projects using GitHub

---

## Project Purpose

This project demonstrates how to design and document a RESTful API using Postman.
The documentation includes authentication, request parameters, response examples, and common error responses.

---

## Tools Used

- Postman (API testing and documentation)
- GitHub (documentation hosting)
- REST API principles

---

## Base URL

https://api.example.com/v1

---

## Authentication

This API uses *Bearer Token Authentication*.

All requests must include the following header:

Authorization: Bearer <access_token>

---

## API Endpoints

### Get All Products
GET /products

Returns a list of products.

Example query parameters:

page – Page number  
limit – Number of products per page

---

### Get Product by ID
GET /products/{id}

Returns details of a single product.

---

### Create Product
POST /products

Creates a new product in the catalog.

---

### Update Product
PUT /products/{id}

Updates an existing product completely.

---

### Update Product (Partial)
PATCH /products/{id}

Updates specific fields of a product.

---

### Delete Product
DELETE /products/{id}

Deletes a product from the catalog.

---

## Full API Documentation

Postman Documentation:

https://documenter.getpostman.com/view/49265967/2sBXcKCy5s

---

## API Documentation Screenshots

### API Overview
![Overview](Overview-SS.png)

### Endpoint Structure
![Endpoints](Endpoint-list-SS.png)

### Create Product Example
![Create Product](Post-create-product-example.png)

---
