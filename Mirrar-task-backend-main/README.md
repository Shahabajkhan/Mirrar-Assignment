# Your Backend E-Commerce Application

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Welcome to the backend of our e-commerce application. This repository contains the server-side implementation that powers our online store, with CRUD operations for managing products. Please follow this guide to set up, configure, and use the backend services.

## Run

- npm i
- npm start
  
## Usage

API Endpoints

Get All Products

- Endpoint: /products
- Method: GET
- Description: Retrieve a list of all products.
- Endpoint http://localhost:9000/products
- {
  - "name": "Product Name",
  - "price": "29.99",
  - "description": "Product Description",
  - "category": "Electronics"
  - "quantity":8"
- }

Create a New Product

- Endpoint: /products/create
- Method: POST
- Description: Create a new product.
- Endpoint http://localhost:9000/products/create
- {
  - "name": "Product Name",
  - "price": "29.99",
  - "description": "Product Description",
  - "category": "Electronics"
  - "quantity":8"
- }

Update a Product

- Endpoint: /products/:id
- Method: PUT
- Description: Update a product by its ID.
- Endpoint http://localhost:9000/products/:id
- {
  - "name": "Product Name",
  - "price": "29.99",
  - "description": "Product Description",
  - "category": "Electronics"
  - "quantity":8"
- }


Delete a Product

- Endpoint: /products/:id
- Method: DELETE
- Description: Delete a product by its ID.
- Endpoint http://localhost:9000/products/:id
- {
- }

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Configuration](#configuration)
  - [Database Setup](#database-setup)
- [Usage](#usage)
  - [API Endpoints](#api-endpoints)
    - [Get All Products](#get-all-products)
    - [Create a New Product](#create-a-new-product)
    - [Get a Product by ID](#get-a-product-by-id)
    - [Update a Product](#update-a-product)
    - [Delete a Product](#delete-a-product)
  - [Authentication](#authentication)
  - [Data Models](#data-models)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (version X.X.X or higher)
- [npm](https://www.npmjs.com/) (version X.X.X or higher)
- [MongoDB](https://www.mongodb.com/) (version X.X.X or higher)

## Getting Started

### Installation

1. Clone this repository:

   ```bash
   gh repo clone NeeraJkumarkondabattula/Mirrar-task-backend
