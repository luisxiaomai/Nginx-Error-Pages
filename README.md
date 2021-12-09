# nginx-error-pages
Nice error pages(4xx and 5xx) for Nginx

# Temp1---Chinese
![404 error page](https://github.com/luisxiaomai/Images/blob/master/Nginx-Error-Pages/temp1-404.png)

![500 error page](https://github.com/luisxiaomai/Images/blob/master/Nginx-Error-Pages/temp1-500.png)

# Temp2---English
![404 error page](https://github.com/luisxiaomai/Images/blob/master/Nginx-Error-Pages/temp2-404.png)

![502 error page](https://github.com/luisxiaomai/Images/blob/master/Nginx-Error-Pages/temp2-502.png)

## Installation

1. Navigate into Nginx's default document directory:
	```
    cd /usr/share/nginx/html
    ```
2. Clone the repository or download the files directly:
	```
    git clone https://github.com/luisxiaomai/nginx-error-pages.git
    ```

3. Include the  the custom error pages to the server's website configuration file:
	```
    server {
    ...
    include /usr/share/nginx/html/nginx-errors/nginx-errors-temp1.conf
    }
    ```
    or
    ```
    server {
    ...
    include /usr/share/nginx/html/nginx-errors/nginx-errors-temp2.conf
    }
    ```
4. Reload Nginx Server:
	  ```
    nginx -s reload
    ```
