# chatapp api

## Installation

clone the repository and run the following command to install the dependencies

`npm install`

Running the server

run the following command to start the server

`npm run serve`

## Database and env setup

Create a `.env` file in the root directory and add the following variables

```
PORT=3000
DB_CONNECTION_STRING=
JWT_SECRET=
OPENAI_API_KEY=
```

## API Endpoints

### Register

`POST /api/register`

Request Body

```json
{
  "username": "test",
  "password": "test",
  "email": "test@mail.com"
}
```

`POST /api/login`

Request Body

```json
{
  "username": "test",
  "password": "test"
}
```

`GET /fetchUserList`
