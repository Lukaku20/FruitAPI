# 🍏 Fruit API

Welcome to the **Fruit API**! This RESTful web service is designed to manage a collection of fruits, allowing users to perform various operations easily.

## 🌟 Key Features
- **CRUD Operations**: Create, Read, Update, and Delete fruit entries.
- **Data Management**: Store information about fruits, including their name, color, and nutritional value.
- **Swagger Documentation**: Easily explore and test API endpoints through integrated Swagger UI.

## 📡 Endpoints

### **1. GET /api/fruits**
Retrieve a list of all fruits.

### **2. GET /api/fruits/{id}**
Retrieve a specific fruit by its ID.

### **3. POST /api/fruits**
Create a new fruit entry.  
**Example Payload**: A JSON object containing the fruit's name, color, and nutritional value.

### **4. PUT /api/fruits/{id}**
Update an existing fruit by its ID.  
**Example Payload**: A JSON object with updated information for the fruit.

### **5. DELETE /api/fruits/{id}**
Delete a specific fruit by its ID.

## 🚀 Usage Example
- To retrieve all fruits, send a **GET** request to `/api/fruits`.
- To add a new fruit, send a **POST** request with the fruit data to `/api/fruits`.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

## 📫 Contact
For questions, please contact [Lukaku](mailto:lucascarballo8819@gmail.com).
