# info
Analytics site for Soroswap

## Configure

1. Copy the example environment file:
  ```sh
  cp .env.example .env
  ```

2. Edit the environmental variables in the `.env` file as needed.

>[!NOTE] 
> To get MERCURY_EMAIL & MERCURY_PASSWORD, you need to create a new account on [Mercury](https://main.mercurydata.app/).

Once created an account fill the email and password in the `.env` file for mainnet and testnet.

3. Run the Docker setup script:
  ```sh
  bash docker/run.sh
  ```

4. Install the necessary dependencies:
  ```sh
  yarn
  ```

5. Start the development server:
  ```sh
  yarn dev
  ```

6. Open your browser and navigate to [http://localhost:3100](http://localhost:3100) to view the application.
