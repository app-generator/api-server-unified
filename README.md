# Unified API Definition

This document describes the **[unified defintion](https://docs.appseed.us/boilerplate-code/api-unified-definition)** used by all API servers provided by AppSeed. This internal standard is used by all full-stack products, despite the UI or backend technology. 

<br />

> API Servers aligned to use it: 

- [API Server Django](https://github.com/app-generator/api-server-django) - free product
- [API Server Flask](https://github.com/app-generator/api-server-flask) - free product
- [API Server FastAPI](#) - free product / **Work in progress**
- [API Server Node JS](https://github.com/app-generator/api-server-nodejs) - free product
- [API Server Node JS PRO](https://github.com/app-generator/api-server-nodejs) - commercial product
 
 <br />

> UI Products aligned to use it:

- [React Berry Dashboard](https://appseed.us/product/react-node-js-berry-dashboard) - free product
- [React Datta Able](https://github.com/app-generator/react-datta-able-dashboard) - free product
- [React Datta Able PRO](https://appseed.us/product/react-node-js-datta-able-pro) - commercial product

<br />

> For more information or support please access the [AppSeed](https://appseed.us/) platform or chat directly with support team on [Discord](https://appseed.us/support).

<br />

## API Information

> Interface descriptor - [POSTMAN collection format](https://github.com/app-generator/api-unified-definition/blob/main/api.postman_collection.json)

- USERS API: 
  - `/api/users/register`: create a new user
  - `/api/users/login`: authenticate an existing user
  - `/api/users/logout`: delete the associated JWT token 
  - `/api/users/checkSession`: check an existing JWT Token for validity
  - `/api/users/edit` - edit the information associated with a registered user

<br />

---
[Unified API Definition](https://docs.appseed.us/boilerplate-code/api-unified-definition) - Internal API Interface definition used by AppSeed [App Generator](https://appseed.us) 
