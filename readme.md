## 🚀 How To Run MySQL On Docker Desktop WSL Ubuntu
1. 📂 **Navigate to the `main-1` folder:**
    ```sh
    cd main-1
    ```

2. 🛠️ **Build and start the containers with Docker Compose:**
    ```sh
    docker compose up -d --build
    ```

3. 🐬 **Access the MySQL bash:**
    ```sh
    docker exec -it mysql mysql -u root -p
    ```
    🔑 **Password:** `123`

## 🌐 How To Connect Using Navicat

1. 🆕 **Create a new connection and select MariaDB.**
2. 📝 **Name your connection, e.g., `prakDB`.**
3. 🏠 **Set the host to `localhost`.**
4. 🔌 **Change the port to `31238`.**
5. 🔑 **Enter the password: `123`.**
6. ✅ **Test the connection to ensure it is working.**