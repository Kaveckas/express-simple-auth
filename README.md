# Express Simple Auth

Setup
-
- Install required dependencies `npm install`
- Set the environmental variables:

  - **Windows**:
    - `set MONGO_STORE_URI=mongodb://localhost/test`
    - `set MONGO_STORE_SECRET=secret`
    - `set PORT=1337` *(optional)*
  - **Linux / OS X**:
    - `export MONGO_STORE_URI=mongodb://localhost/test`
    - `export MONGO_STORE_SECRET=secret`
    - `export PORT=1337` *(optional)*

- Run the application `npm start`
- Go to `http://127.0.0.1:3001`