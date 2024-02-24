# Calculator API

This is a simple calculator API built with Express.js.

## Endpoints

### 1. Addition
   - **Endpoint:** `/api/topla/:num1/:num2`
   - **Description:** Adds two numbers.
   - **Example:** `/api/topla/5/3` returns `8`.

### 2. Multiplication
   - **Endpoint:** `/api/carp/:num1/:num2`
   - **Description:** Multiplies two numbers.
   - **Example:** `/api/carp/4/2` returns `8`.

### 3. Division
   - **Endpoint:** `/api/bol/:num1/:num2`
   - **Description:** Divides two numbers.
   - **Example:** `/api/bol/8/2` returns `4`.

   - **Note:** Division by zero is handled, and an appropriate error message is returned.

### 4. Subtraction
   - **Endpoint:** `/api/cikar/:num1/:num2`
   - **Description:** Subtracts two numbers.
   - **Example:** `/api/cikar/5/3` returns `2`.

   - **Note:** If the second number is greater than or equal to the first number, an error message is returned.

#### Install dependencies:
npm install

#### Run the server:
npm start
The server will be running at http://localhost:3000.
