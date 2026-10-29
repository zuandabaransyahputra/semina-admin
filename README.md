# Semina Admin

Admin dashboard for the Semina event ticketing platform. Organizers and admins manage events, speakers, ticket categories, payment methods and orders through the [Semina API](https://github.com/zuandabaransyahputra/semina-api).

**Live demo:** [semina-admin-gamma.vercel.app](https://semina-admin-gamma.vercel.app/)

Built as part of a full-stack bootcamp.

## Features

- Sign in with role-based access from the API
- **Dashboard** overview
- CRUD screens for **categories**, **talents** (speakers), **events** and **payment methods**
- **Orders** list with pagination and date filtering
- Debounced search, select inputs and confirmation dialogs
- Global state with Redux Toolkit and Redux Thunk for API calls

## Tech stack

React, React Router, Redux Toolkit, Redux Thunk, Axios, React Bootstrap, React Select, SweetAlert2, Moment.

## Getting started

```bash
git clone https://github.com/zuandabaransyahputra/semina-admin.git
cd semina-admin
npm install
cp .example.env .env   # set REACT_APP_HOST_DEV to the API URL, e.g. http://localhost:9000/api/v1/cms
npm start
```

Requires a running [Semina API](https://github.com/zuandabaransyahputra/semina-api).
