# 🏠 Book My PG

A Java-based **PG (Paying Guest) Management System** that allows tenants to book PG accommodations, landlords to manage rooms, and admins to monitor the system.  

## 🚀 Features
- Tenant registration and booking
- Landlord room management
- Secure payments
- Feedback system
- SQL Database integration
- Doubly Linked List & Queue implementations

## 🛠️ Technologies Used
- Java
- SQL (Database schema provided in `pg.sql`)

## 📂 Project Structure
- `BookMyPG.java` → Main program
- `Tenant.java`, `Landlord.java`, `User.java` → Entity classes
- `Database.java` → Database connection handling
- `Payment.java` → Payment system
- `Feedback.java` → Feedback management
- `pg.sql` → SQL schema

## ⚙️ How to Run
1. Clone repo:
   ```bash
   git clone https://github.com/themeetshah/Book-My-PG.git
   cd Book-My-PG
   ```

2. Import the `pg.sql` file into your SQL database.

3. Compile the Java file:
   ```bash
   javac *.java
   ```

4. Run the program:
   ```bash
   java BookMyPG
   ```

## 🤝 Contributing
- [**Pull requests**](https://github.com/themeetshah/book-my-pg/pulls) are welcome! Open an [issue](https://github.com/themeetshah/book-my-pg/issues) to suggest changes.

## 📜 License
- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.