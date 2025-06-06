# Task Management Application

A feature-rich task management application built with React, Redux, and Material UI.
![Screenshot 2025-03-31 221559](https://github.com/user-attachments/assets/37dbc2ca-167c-4e1f-8168-7e5b11a9a373)
![Screenshot 2025-03-31 221810](https://github.com/user-attachments/assets/f4e89c31-121f-42d2-8036-9ed062d969d5)
![Screenshot 2025-03-31 221846](https://github.com/user-attachments/assets/8de6f391-7d71-4fc2-9123-b76a10e71dbf)
![Screenshot 2025-03-31 221929](https://github.com/user-attachments/assets/ad9b0911-cf15-492d-af85-669d89f5a885)
![Screenshot 2025-03-31 222013](https://github.com/user-attachments/assets/e3133686-2031-4e05-a5d7-23d95b7766e2)
![Screenshot 2025-03-31 222046](https://github.com/user-attachments/assets/2daab299-f7a0-4a30-b078-875b8f5455f3)




## Features

- **Task Management**
  - Create, edit, and delete tasks
  - Mark tasks as complete/incomplete
  - Set task priority (Low, Medium, High)
  - Add due dates to tasks
  
- **Organization**
  - Filter tasks by status (All, Active, Completed)
  - Sort tasks by priority, due date, or creation date
  - Drag and drop tasks to reorder
  
- **User Experience**
  - Responsive design for mobile and desktop
  - Intuitive UI with Material Design
  - Persistent storage using localStorage

## Tech Stack

- **Frontend**: React.js
- **State Management**: Redux
- **UI Library**: Material UI
- **Storage**: localStorage
- **Drag and Drop**: react-beautiful-dnd

## Installation and Setup

### Prerequisites

- Node.js (v14.0.0 or later)
- npm (v6.0.0 or later)

### Steps to Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/task-management-app.git
   cd task-management-app
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm start
   ```

4. Open your browser and navigate to [http://localhost:3000](http://localhost:3000)

## Project Structure

```
src/
├── components/        # UI components
│   ├── TaskForm/      # Task creation/editing form
│   ├── TaskItem/      # Individual task component
│   ├── TaskList/      # List of tasks
│   └── FilterSort/    # Filtering and sorting controls
├── redux/             # Redux state management
│   ├── actions/       # Action creators
│   ├── reducers/      # Reducers
│   └── store.js       # Redux store configuration
├── hooks/             # Custom React hooks
├── utils/             # Utility functions
├── App.js             # Main application component
└── index.js           # Entry point
```

## Usage

### Creating a Task
1. Enter task details in the "Add Task" form
2. Set priority and due date if needed
3. Click "Add Task" to create

### Managing Tasks
- Check the checkbox to mark a task as complete
- Click the edit icon to modify task details
- Click the delete icon to remove a task
- Drag and drop tasks to reorder them

### Filtering and Sorting
- Use the filter dropdown to show All, Active, or Completed tasks
- Use the sort dropdown to arrange tasks by priority, due date, or creation date

## Deployment

The app is deployed on [Netlify/Vercel/GitHub Pages] and can be accessed at [your-deployed-url].

### Deployment Steps

1. Build the application
   ```bash
   npm run build
   ```

2. Deploy to your preferred platform:
   - **GitHub Pages**: Configure in package.json and run `npm run deploy`
   - **Netlify**: Connect GitHub repository or drag and drop the build folder
   - **Vercel**: Connect GitHub repository and configure build settings

## Future Enhancements

- User authentication
- Cloud storage integration
- Task categories/labels
- Task reminders and notifications
- Dark mode theme
- Data export/import functionality

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
