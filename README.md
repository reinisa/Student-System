# Student System

## Setup Instructions

### **Prerequisites**
Ensure you have the following installed on your system:
- **Java 17+;**
- **IntelliJ IDEA** (or any Java supporting IDE);
- **Node.js & npm;**
- **MySQL** (via **XAMPP** or a standalone installation);
- **MySQL Database Driver** (included in dependencies).

### **Backend Setup**
1. **Clone the repository**
    ```
    git clone https://github.com/reinisa/Student-System.git
   
    cd student-system # Navigate to the root directory
    ```
2. **Set up the MySQL database**
   - Open **XAMPP** and start `Apache` & `MySQL`
   - Create a database named `studentsystem`
   - Update `application.properties` with your MySQL credentials if needed:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/studentsystem
     spring.datasource.username=root
     spring.datasource.password=
     ```
3. **Run the Main Application file**
    ```
    Open StudentSystemApplication.java and run it.
   
    - The backend will start on `http://localhost:8080`
    ```

### **Frontend Setup**
1. Navigate to the frontend directory:
    ```
    cd studentfrontend
    ```
2. Install dependencies:
    ```
    npm install
    ```
3. Start the React development server:
    ```
    npm start
   
    - The frontend will be accessible at `http://localhost:3000`
    ```
