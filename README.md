# 🛢️ GoShop MySQL Service

This is the dedicated **MySQL database service** for the GoShop e-commerce platform. It provides and manages the relational data structure used across various microservices in the platform.



## 📦 Features

- 🗄️ **Relational Database** using MySQL
- 📁 **Schema Management** via `.sql` migration files
- 🔁 **Centralized Database** for categories, products, users, orders, etc.
- 🧩 **Easy Integration** with GoShop microservices



## 🧰 Tech Stack

| Component  | Technology |
|------------|------------|
| Database   | MySQL 8+   |
| Schema     | SQL (.sql files) |




## 🧪 Database Initialization

To create the GoShop schema manually:

```bash
mysql -u <username> -p < database_name < schema.sql
```

To load seed data:

```bash
mysql -u <username> -p < database_name < seed.sql
```



## 📌 Notes

- Ensure you have MySQL 8+ installed and running.
- The schema is designed to support core GoShop services like catalog, product, and image management.


## ✨ Author
Made with ❤️ by Vamsi Rayapati

