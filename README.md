# JSON Server

Welcome to the JSON Server repository! JSON Server is a simple and fast backend server that allows you to quickly set up a RESTful API using a JSON file as a data source. 

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/benjahmin-koenigsberg/JSON_Server.git
   ```

2. **Navigate to the Project:**
   ```bash
   cd JSON_Server
   ```

3. **Install Dependencies:**
   ```bash
   npm install
   ```

4. **Start the Server:**
   ```bash
   npm start
   ```

5. **Server Configuration:**
   - Modify the `db.json` file to define your API's data structure.

## Usage

JSON Server follows RESTful conventions, and you can perform CRUD operations using standard HTTP methods:

- **GET:** Retrieve data.
- **POST:** Add new data.
- **PUT:** Update existing data.
- **DELETE:** Remove data.

Example endpoints:
- `GET /api/tasks`: Retrieve all tasks.
- `GET /api/tasks/1`: Retrieve the task with ID 1.
- `POST /api/tasks`: Add a new task.
- `PUT /api/tasks/1`: Update the task with ID 1.
- `DELETE /api/tasks/1`: Delete the task with ID 1.

For more advanced configurations and features, refer to the [JSON Server documentation](https://github.com/typicode/json-server).

## Project Structure

```plaintext
|-- db.json
|-- .gitignore
|-- README.md
|-- package.json
|-- server.js
|-- etc.
```

- **`db.json`:** JSON file containing your data.
- **`routes.json`:** JSON file specifying custom routes.
- **`.gitignore`:** Specifies files/folders to be ignored by Git.
- **`README.md`:** Project documentation.
- **`package.json`:** Project dependencies and scripts.
- **`server.js`:** Entry point for the JSON Server.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

Happy mocking! 🚀
