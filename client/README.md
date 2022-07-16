## Contributing

1. Fork the repo
   ```sh
   git@github.com:ruchidh/BharatUdyog_1.0.git
   ```
2. Take a pull before starting to contribute to make sure you are update with the latest code.
   ```sh
   git pull origin staging
   ```
3. Checkout to new new branch on you local machine
   ```sh
   git checkout -b <feature-name> Ex. user-registration-setup
   ```
4. Writing commit message for contribution done
   ```sh
   git commit -m "updated user profile pic upload to support new image formats"
   ```
5. Check if the build is successfully created
   ```sh
   npm run build
   ```
6. Creating PR

   ```sh
   git push origin <local-branch-name>
   ```

7. Target branch to merge will be <b>beta</b>

## Start Server

1.  Installing dependencies
    ```sh
    npm i
    ```
2.  Start the application
    ```sh
    npm run start
    ```

## CSS conventions we follow

1. Use rem for <code>font-size</code> , <code>line-height</code> , em for <code>letter-spacing</code> and px for other properties

## ESlint configuration

1. We use ESlint along with Prettier in our project. Before you start to contribute on the project please make sure to configure the linters.

2. Install `ESLint by Dirk Baeumer` and `Prettier by Prettier` from Extensions

3. Make sure that you have <label style="color: red;">Prettier</label> as your default document formatter.
