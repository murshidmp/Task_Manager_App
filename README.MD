# Task Manager App

A simple web application for managing tasks. The app allows users to create, view, edit, and delete tasks.

![Task Manager App](/public/favicon.ico)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/murshidmp/Task_Manager_App.git
   cd Task_Manager_App

2.Install dependencies:

    npm install

3. Create a .env file in the root directory and provide your MongoDB connection URI:

    MONGO_URI=your-mongodb-uri
    PORT=5000

4. Run the app:

    npm start

## Usage
    1. Open your web browser and navigate to http://localhost:5000.
    2. Use the interface to add, edit, and delete tasks.


## API Routes
    GET /api/v1/tasks: Get a list of all tasks.
    POST /api/v1/tasks: Create a new task.
    GET /api/v1/tasks/:id: Get details of a specific task.
    PATCH /api/v1/tasks/:id: Update details of a specific task.
    DELETE /api/v1/tasks/:id: Delete a specific task.
    
    
    # Example Response:

    json
    Copy code
    {
    "tasks": [
        {
        "_id": "task-id",
        "name": "Sample Task",
        "completed": false
        },
        // More tasks...
    ]
    }
## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to create an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or feedback, you can reach us at contact@example.com.