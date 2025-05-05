# ITIS-6177 Assignment 12 - Product API with LoopBack 4

## API Overview
REST API for product management with full CRUD operations

## Tool Used
LoopBack 4 (https://loopback.io/)

## Features
- In-memory database
- OpenAPI 3.0 documentation
- Ready-to-use endpoints

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | /products | Create new product |
| GET    | /products | List all products |
| GET    | /products/{id} | Get product by ID |
| PUT    | /products/{id} | Replace entire product |
| PATCH  | /products/{id} | Update product fields |
| DELETE | /products/{id} | Delete product |
| GET    | /products/count | Count products |
| PATCH  | /products | Bulk update products |

## Setup Instructions
1. Install dependencies:
npm install