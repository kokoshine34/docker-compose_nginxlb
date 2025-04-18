# NGINX Load Balanced Web Server Cluster

This project sets up a simple load-balanced cluster of NGINX web servers using Docker Compose. It includes:

- 🌀 A load balancer (NGINX)
- 🌐 Three NGINX-based web servers
- 🔁 Round-robin traffic distribution

## 📁 Project Structure

![image](https://github.com/user-attachments/assets/21e3da08-2888-45d6-8643-24019f13aa2e)


## Design
![image](https://github.com/user-attachments/assets/5016c78f-57f8-4a4d-864d-be1709cc14a3)

---------------------------------------------------------------------------------------------------------
## 🚀 Getting Started

### 1. Clone the Repo

git clone [https://github.com/yourusername/nginx-loadbalancer.git](https://github.com/kokoshine34/docker-compose_nginxlb.git)

cd nginx-loadbalancer

### 2. Run the Stack
docker compose up --build

### 3. Test It
Open your browser and go to:
http://localhost

--------------------------------------------------------------------------------------------------------------
📦 Requirements
Docker

----------------------------------------------------------------------------------------------------------------
Docker Compose

📌 Notes
Each web server has its own simple index.html page for identification.

This is a basic example and not intended for production use.
