# PetStore API - Postman Collection

This repository contains a Postman collection for the **PetStore API**, a sample API that demonstrates a typical RESTful API for managing pets in a store.

---

## 📝 **Contents**

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Endpoints](#endpoints)
- [Importing the Collection](#importing-the-collection)
- [Contributing](#contributing)
- [License](#license)

---

## 🚀 **Overview**

The PetStore API allows users to:

- Manage pets (add, update, delete, retrieve).
- View store inventory.
- Place orders for pets.
- Manage user accounts.

This collection organizes the API's requests into folders for easier navigation and testing.

---

## 🛠️ **Getting Started**

1. **Install Postman**:
   - Download and install Postman from the [official website](https://www.postman.com/).

2. **Clone this Repository**:
   ```bash
   git clone https://github.com/AlnagKunnappilly/Postman_PetStore.git
   cd Postman_PetStore

3.**Import the Postman Collection**:
    Open Postman.
    Click on File > Import.
    Select the PET_STORE.postman_collection.json file from this repository.
  
4.**Set Up the Environment**:
  If an environment file is provided (PET_STORE.postman_environment.json), import it under Environments in Postman.
  Update the base URL and other variables (if needed).

---

**🔗 Endpoints**

### **Pet Endpoints**
| Method   | Endpoint        | Description                   |
|----------|-----------------|-------------------------------|
| `POST`   | `/pet`          | Add a new pet to the store    |
| `PUT`    | `/pet`          | Update an existing pet        |
| `GET`    | `/pet/{petId}`  | Get details of a specific pet |
| `DELETE` | `/pet/{petId}`  | Delete a pet                  |

### **Store Endpoints**
| Method   | Endpoint               | Description                   |
|----------|------------------------|-------------------------------|
| `GET`    | `/store/inventory`     | Get store inventory           |
| `POST`   | `/store/order`         | Place a new order for a pet   |
| `GET`    | `/store/order/{orderId}` | Get details of an order       |
| `DELETE` | `/store/order/{orderId}` | Delete an order               |

### **User Endpoints**
| Method   | Endpoint            | Description                   |
|----------|---------------------|-------------------------------|
| `POST`   | `/user`             | Create a new user             |
| `GET`    | `/user/{username}`  | Get user details              |
| `PUT`    | `/user/{username}`  | Update user information       |
| `DELETE` | `/user/{username}`  | Delete a user                 |

For a detailed description of all endpoints, refer to the [Swagger PetStore documentation](https://petstore.swagger.io/).

---
📥 Importing the Collection
Follow these steps to import the collection into Postman:

Open Postman and navigate to File > Import.
Select the file PET_STORE.postman_collection.json from the repository.
(Optional) Import the environment file if provided.

---
🤝 Contributing
Contributions are welcome! If you find issues or have suggestions for improvement:

Fork this repository.
Make your changes.
Submit a pull request.

---
📄 License
This repository is licensed under the MIT License. Feel free to use and modify it as needed.

