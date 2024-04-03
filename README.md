# Product Data Management Node Application

## Description

This Node.js application serves as an interface to interact with and retrieve product-related data from a MySQL database. It is designed to handle REST API requests to efficiently provide data to users.

## Installation

1. Run `npm i` to install the required dependencies.
2. Set up a `.env` file with the necessary configuration details.

## Usage

1. Navigate to the `develop` folder.
2. Access MySQL by entering `mysql -u 'username' -p` in the command line and providing your password.
3. Once in MySQL, execute the following commands:
   - `SOURCE db/schema.sql`
   - `USE db/schema.sql`
4. Exit MySQL by typing `quit`.
5. Run `npm run seed`.
6. Start the application by running `npm start`.

For a detailed tutorial, refer to this [video tutorial](https://drive.google.com/drive/folders/1Y_mJekRzv4mFgv2lKRTntgsHdwCcGqPB).
