
## About Laravel
 - Sử dụng PHP 7.1.3
 - Laravel sử dụng composer để quản lý các gói thư viện sử dụng. Các gói thư viện sử dụng chứa trong thư mục vendor, sau khi gọi lệnh composer update để lấy  về.
 - Kiểm tra các Route đang có: 

    ```
    php artisan route:list
    ```

## Run Project
 - Step 1: Setup ban dau: 
    - Cài đặt thư viện

        ```
        composer update
        ```
    - Thêm database

        ```
        php artisan migrate 
        ```
 - Step 2: Run server:
    ```
    php artisan serve
    ```