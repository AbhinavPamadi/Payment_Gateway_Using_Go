# Payment_Gateway_Using_Go

![Go](https://img.shields.io/badge/language-Go-00ADD8.svg)
![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)

## Project Overview

This project consists of:  
- A **Go-based backend** implementing a payment gateway API for processing payments  
- A **static product-site frontend** where visitors can view products and make purchases  

The backend handles payment creation, authorization, capture, refund, and webhook notifications. The frontend allows browsing products, adding to cart, and launching payments via the Stripe API.

## Getting Started

### Prerequisites  
- Go 1.20+  
- Node.js or tools for frontend  
- Payment gateway sandbox account (e.g. Stripe)
- Replace your stripe api key in server.go in backend.

### Installation and Running

1. Clone repo
```bash
git clone https://github.com/AbhinavPamadi/Payment_Gateway_Using_Go.git
cd Payment_Gateway_Using_Go
```
2. Backend
```bash
cd Go_ProductWebsite_backend
go run server.go
```

3. Frontend
```bash
cd Go_ProductWebsite_frontend
npm run dev
```


