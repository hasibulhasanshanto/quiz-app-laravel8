# Laravel Online Quiz Application (based on Laravel 8.x)

-   Application to manage and take the quiz online.
-   Students can apply for the test and view results

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)

## Admin login

```
email: admin@app.com
password : password
```

## User login

```
email: user@app.com
password : password
```

# Installation

1. **Clone or download this Repository.**

    ```
    git clone https://github.com/hasibulhasanshanto/quiz-app-laravel8
    ```

2. **Run the command**

    ```
    composer install
    ```

3. **Create `.env` file by copying the `.env.example`, or run the following command**

    ```
    cp .env.example .env
    ```

4. **Update the database name and credentials in `.env` file**

    ```
     DB_CONNECTION=mysql
     DB_HOST=127.0.0.1
     DB_PORT=3306
     DB_DATABASE=quiz_app
     DB_USERNAME=root
     DB_PASSWORD=
    ```

5. **Run the following command**
    ```
    php artisan key:generate
    ```
6. **To migrate database and seed the datas to DB**
    ```
    php artisan migrate --seed
    ```
7. **Run npm install command**
    ```
    npm install
    ```
8. **Run the command to compile the theme**
    ```
    npm run dev
    ```
9. **Finally run the application**
    ```
    php artisan serve
    ```

# Screenshots

## Admin side

![image](https://user-images.githubusercontent.com/70872374/147752562-9648c490-8a0e-4376-b555-5cec9cf6ee57.png)
![image](https://user-images.githubusercontent.com/70872374/147752630-a807a527-ab18-4b0a-885b-90bab9dd3a42.png)

## Student side

![image](https://user-images.githubusercontent.com/70872374/147752771-66b63a55-69bb-41d2-93df-138991287b67.png)
![image](https://user-images.githubusercontent.com/70872374/147752807-4fb59934-f1f7-4be0-8a10-a150f175dd36.png)
