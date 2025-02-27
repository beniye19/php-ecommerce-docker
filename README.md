### **PHP E-Commerce Web App with Docker Compose 🚀**

A simple **PHP E-Commerce web app** built with **Docker Compose**, **Nginx**, and **MariaDB**.

📌 Project Overview
-------------------

This project demonstrates how to deploy a PHP-based e-commerce web app using Docker containers. The app uses **Nginx** as the web server, **PHP-FPM** for backend logic, and **MariaDB** for the database.

🛠️ Tech Stack
--------------

*   **PHP 7.0**
    
*   **MariaDB**
    
*   **Nginx**
    
*   **Docker & Docker Compose**
    
*   **Bootstrap**
    
*   **jQuery**
    

📂 Folder Structure
-------------------

```
.
├── docker-compose.yml       # Docker Compose configuration
├── nginx                   # Nginx configuration and Dockerfile
│   ├── default.conf        # Nginx virtual host configuration
│   └── Dockerfile          # Docker image setup for Nginx
├── php_code                # PHP application code
│   ├── Dockerfile          # Docker image setup for PHP-FPM
│   ├── index.php           # Main PHP file
│   ├── css                 # Stylesheets
│   ├── js                  # JavaScript files
│   └── img                 # Images
└── db-load-script.sql      # SQL script to populate the database
```

🚀 How to Run the Project
-------------------------

### **Prerequisites**

*   Docker
    
*   Docker Compose
    

### **Steps**

1.  
```
 git clone https://github.com/yourusername/php-ecommerce-docker.git
 cd php-ecommerce-docker
```
2. 
```
docker compose up -d
```  
3.  
```
http://localhost
```    
4.  
```
docker exec -it mariadb -u root -pmariadb < db-load-script.sql
```    

🔐 Environment Variables
------------------------

```
**Environment Variables**
- `MYSQL_ROOT_PASSWORD`: MariaDB Root Password *(Default: mariadb)*
- `MYSQL_DATABASE`: Database Name *(Default: ecomdb)*
```
🎯 Future Improvements
----------------------

*   Implement **CI/CD Pipelines** using **GitHub Actions**
    
*   Add **SSL Certificates** using **Certbot**
    
*   Deploy to **Cloud Providers** with **Terraform & Ansible**
    
*   Set up **Centralized Logging** using **ELK Stack**
    
*   Add **Monitoring & Alerts** with **Prometheus & Grafana**
    

📌 Connect with Me 🌐
---------------------

*   **LinkedIn:** \[Your LinkedIn URL\]
    
*   **GitHub:** \[Your GitHub URL\]
    
*   **Twitter:** \[Your Twitter URL\]
    

Let's **build something great together!** 🔥
