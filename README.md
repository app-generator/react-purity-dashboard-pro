# [Full-Stack React Purity PRO](https://appseed.us/product/purity-dashboard-pro/full-stack/react/)

[Full-Stack React Purity PRO](https://appseed.us/product/purity-dashboard-pro/full-stack/react/) is built with over 300 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining. All components can take variations in color, which you can easily modify using JSS files and classes. 
The product comes with a simple JWT authentication flow: **login/register/logout** powered by a [Node JS API Server](https://github.com/app-generator/api-server-nodejs). 

- 👉 [Full-Stack React Purity PRO](https://appseed.us/product/purity-dashboard-pro/full-stack/react/) - product page
- 👉 [Full-Stack React Purity PRO](https://fullstack-react-purity-dashboard.appseed-srv1.com/#/auth/authentication/sign-in/basic) - LIVE Demo

<br />

> Features

- ✅ Innovative Chakra UI Design - Creafted by [Creative-Tim](https://bit.ly/3fKQZaL)
- ✅ React, Redux, Redux-persist
- ✅ Authentication: JWT Login/Register/Logout
- ✅ Full-stack ready using **[Node JS API Server](https://github.com/app-generator/api-server-nodejs)** (open-source project)
  - Features: Typescript / SQLite / TypeORM / Joy (validation) / Passport library - `passport-jwt` strategy.

<br />

![Full-Stack React Purity PRO - Full-stack product built in React and Node JS by AppSeed and Creative-Tim.](https://user-images.githubusercontent.com/51070104/205429093-33d14286-3500-4489-b4cb-214f998d150d.png)

<br />

## How to use it

To use the product Node JS (>= 12.x) is required and GIT to clone/download the project from the public repository.

> 👉 **Step 1** - Download the ZIP from the official product page

```bash
$ unzip react-purity-dashboard-pro.zip
$ cd priv-react-purity-dashboard-pro
```

<br >

> 👉 **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> 👉 **Step 3** - Edit the `.env` using the template `.env.sample`. 

```env

REACT_APP_BACKEND_SERVER='http://localhost:5000/api/'

```

<br />

> 👉 **Step 4** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

## Backend Integration

> The backend API server address is saved in `src/config/constant.js`.

```javascript
export const API_SERVER = "http://localhost:5000/api/";
```

<br />

> Frontend api has been created at `src/api/auth.js`.

```javascript
const axios = Axios.create({
    baseURL: `${baseURL}/api`,
    headers: { "Content-Type": "application/json" },
});
```    

<br />

> Register implementation:

- Frontend method with call to backend
- Form validation
- Error handling

<br />

> Login implementation:

- Frontend method with call to backend
- Form validation
- Error handling

<br />

> Logout implementation:

- Frontend method with call to backend

<br />

> User Context:

- The user account is now saved both to the React.Context wrapper and localStorage

<br />

> Protected routes:
 
- The user cannot access protected routes like /admin, /rtl without being logged in.
- Example of 3 different routes:

```javascript
    <ProtectedRoute path="/admin" component={AdminLayout} />
    <ProtectedRoute path="/rtl" component={RtlLayout} />
    <Route path="/auth" component={AuthLayout} />
```

<br />

> **API Server Descriptor** - POSTMAN Collection

The API Server definition is provided by the [Nodejs API Server](https://github.com/app-generator/api-server-nodejs)

- [API POSTMAN Collection](https://github.com/app-generator/api-server-nodejs/blob/master/media/api.postman_collection.json) - can be used to mock (simulate) the backend server or code a new one in your preferred framework. 

<br />

## [Node JS API Server](https://appseed.us/boilerplate-code/nodejs-starter/)

The product is also open-source and cis already configured to work with Berry Dashboard Template.

- [Node JS API](https://github.com/app-generator/api-server-nodejs) - `source code`
- [Node JS API Server](https://appseed.us/boilerplate-code/nodejs-starter/) - `product page`

> Features:

- ✅ Nodejs / Express server
- ✅ JWT authentication (`passport-jwt` strategy)
- ✅ Persistence
  - `SQLite`
  - `MongoDB` (another product) 

<br />

![Node JS API - Open-source API server built on top of Express Nodejs Framework.](https://user-images.githubusercontent.com/51070104/124934824-c210a700-e00d-11eb-9d01-e05bd8bfb608.png)

<br />

---
[Full-Stack React Purity PRO](https://appseed.us/product/purity-dashboard-pro/full-stack/react/) - Provided by [Creative-Tim](https://bit.ly/3fKQZaL/) and `AppSeed`. 
