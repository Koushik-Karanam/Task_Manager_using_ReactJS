# Task Management Application

A feature-rich task management application built with React, Redux, and Material UI.

![Screenshot 2025-03-31 222046](https://github.com/user-attachments/assets/a978c613-9596-4985-a2ae-b5e1239a1590)
![Screenshot 2025-03-31 222037](https://github.com/user-attachments/assets/29aea159-52d8-4fb9-bc92-557525c193cb)
![Screenshot 2025-03-31 222026](https://github.com/user-attachments/assets/965f6000-fde0-43b4-9bd9-ff1a0487fa5f)
![Screenshot 2025-03-31 222013](https://github.com/user-attachments/assets/45b18ee0-23dc-4eed-9eea-93c1c4aa4b6d)
![Screenshot 2025-03-31 221929](https://github.com/user-attachments/assets/f1415c68-c33e-4be0-9230-36859d5cb542)
![Screenshot 2025-03-31 221846](https://github.com/user-attachments/assets/e5103768-02af-4f7c-8ac9-9eb5756513de)
![Screenshot 2025-03-31 221810](https://github.com/user-attachments/assets/faae1402-f1c3-4fd1-9a8e-2bd5324a8e19)
![Screenshot 2025-03-31 221559](https://github.com/user-attachments/assets/ea55491d-62d6-474c-848f-a76239b9cfcb)


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
