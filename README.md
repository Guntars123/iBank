# iBank Project Setup

Welcome to the iBank project! This document provides step-by-step instructions to help you set up and run the project on your local machine.

## Prerequisites
Before you begin, ensure that you have the following prerequisites installed on your system:
- PHP (>= 7.3)
- Composer
- MySQL
- CoinMarketCap API Key (sign up at https://coinmarketcap.com/api/)

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/ibank.git

2. Navigate to the project directory:
    ```bash
    cd ibank
3. Install the project dependencies:
    ```bash
    composer install
4. Create a copy of the `.env.example` file and rename it to `.env`:
    ```bash
   
5. Open the .env file and set the following variables:

- DB_DATABASE: Your MySQL database name.
- DB_USERNAME: Your MySQL database username.
- DB_PASSWORD: Your MySQL database password.
- COINMARKETCAP_API_KEY: Your CoinMarketCap API key.

6. Generate an application key:
    ```bash
    php artisan key:generate
   
7. Run the database migrations:
    ```bash
    php artisan migrate
   
## Running the Application

1. Start the local development server:
    ```bash
    php artisan serve
   
2. Open the application in your browser!

   
## Additional Information
The iBank project is built using Laravel, a powerful PHP framework. It leverages Laravel Breeze for user registration and authentication.
The project uses MySQL as the database to store user and financial data.
To fetch cryptocurrency data, the project integrates with the CoinMarketCap API. Make sure to provide your valid CoinMarketCap API key in the .env file.
Enjoy using the iBank project and managing your finances seamlessly!

