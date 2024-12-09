### Below are the steps for how one can use this project for further improvisation

### **1. Download and Unzip the Project Files**
1. **Download the Project**: Obtain the zipped file containing the project.
2. **Extract Files**: Unzip the downloaded file to your local system. You will find a folder named `library` containing all the necessary files for the project.

---

### **2. Move the Project Folder**
1. Locate the extracted `library` folder.
2. Copy and paste the `library` folder into your server’s root directory:
   - For **XAMPP**, place it in the `htdocs` folder (`C:/xampp/htdocs/`).
   - For **WAMP**, place it in the `www` folder (`C:/wamp/www/`).

---

### **3. Configure the Database**
1. **Start Your Local Server**:
   - Open your XAMPP or WAMP control panel and start the **Apache** and **MySQL** services.

2. **Access phpMyAdmin**:
   - Open your web browser and go to `http://localhost/phpmyadmin`.

3. **Create the Database**:
   - Click on the **Databases** tab.
   - Create a new database named `library`.

4. **Import the Database File**:
   - Open the newly created `library` database.
   - Click the **Import** tab.
   - Select the `library.sql` file from the project folder (this file is included in the downloaded zip package).
   - Click **Go** to import the database structure and data.

---

### **4. Running the Application**

#### **For Users**
1. **Access the User Interface**:
   - Open your web browser and navigate to:
     ```
     http://localhost/Online-Library-Management-System-PHP/library/index.php#ulogin
     ```

2. **Log In as a User**:
   - Use the following credentials to log in:
     - **Username**: `test@gmail.com`
     - **Password**: `Test@123`

#### **For Admins**
1. **Access the Admin Panel**:
   - Open your web browser and navigate to:
     ```
     http://localhost/Online-Library-Management-System-PHP/library/adminlogin.php
     ```

2. **Log In as Admin**:
   - Use the following credentials to log in:
     - **Username**: `admin`
     - **Password**: `LMS_BMS`

---

### **Project Features**

- **User Dashboard**: Users can browse books, manage borrowing records, and view available library resources.
- **Admin Panel**: Admins can manage books, users, and other library resources effectively.
- **Database Management**: All data related to books and users is stored in the `library` database.

---

### **Important Notes**
- Ensure your local server (XAMPP/WAMP) is running whenever you access the application.
- Verify that the imported database (`library.sql`) matches the project requirements.
- Use the provided login credentials for initial access. You can later add or modify users and admins from the admin panel.

By following the above steps, your Library Management System will be set up and ready to use on your local machine.
