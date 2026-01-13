# Task Tracker Application

A modern, responsive task tracking application built with React. This application allows users to efficiently manage their daily tasks with a clean and intuitive user interface.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Future Enhancements](#future-enhancements)

## 🎯 Overview

This Task Tracker application is designed to help users organize and track their daily tasks efficiently. The application provides a simple yet powerful interface for adding, managing, and tracking task completion status. Built as an assignment for Hexa Solutions, this project demonstrates modern React development practices and responsive design principles.

## ✨ Features

### Core Functionality
- **Add Tasks**: Easily add new tasks using the input field and "Add Task" button
- **Task Status Tracking**: Each task displays its current status (Pending or Completed)
- **Status Toggle**: Mark tasks as completed or pending with a single click
- **Delete Tasks**: Remove tasks that are no longer needed
- **Date Display**: Shows current weekday and full date for better context

### User Interface
- **Modern Design**: Clean, gradient-based UI with smooth animations
- **Responsive Layout**: Fully responsive design that works on desktop, tablet, and mobile devices
- **Visual Status Indicators**: 
  - Color-coded status badges (Yellow for Pending, Green for Completed)
  - Different background colors for pending and completed tasks
  - Strikethrough text for completed tasks
- **Interactive Elements**: Hover effects and smooth transitions throughout the application
- **Empty State**: Helpful message when no tasks are present

### User Experience
- **Keyboard Support**: Press Enter to add tasks quickly
- **Real-time Updates**: Instant visual feedback for all actions
- **Intuitive Controls**: Clear buttons and visual cues for all operations

## 🛠️ Technologies Used

- **React** (v19.2.0) - JavaScript library for building user interfaces
- **React DOM** (v19.2.0) - React renderer for web
- **CSS3** - Modern styling with gradients, animations, and responsive design
- **Font Awesome** - Icon library for UI elements
- **Create React App** - Build tooling and development environment

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher recommended)
- npm (Node Package Manager) or yarn

### Steps

1. **Clone the repository** (if applicable) or navigate to the project directory:
   ```bash
   cd Simple_Todo
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm start
   ```

4. **Open your browser**:
   The application will automatically open at [http://localhost:3000](http://localhost:3000)

## 🚀 Usage

### Adding a Task
1. Type your task in the input field at the top of the page
2. Click the "Add Task" button or press Enter
3. Your task will appear in the task list below

### Managing Tasks
- **Mark as Completed**: Click the "Mark Completed" button on any pending task
- **Mark as Pending**: Click the "Mark Pending" button on any completed task
- **Delete Task**: Click the trash icon button to remove a task permanently

### Task Status
- **Pending Tasks**: Displayed with a yellow badge and orange-tinted background
- **Completed Tasks**: Displayed with a green badge, cyan-tinted background, and strikethrough text

## 📁 Project Structure

```
Simple_Todo/
├── public/
│   ├── index.html          # Main HTML file
│   └── manifest.json       # PWA manifest
├── src/
│   ├── App.js              # Main application component
│   ├── App.css             # Application styles
│   └── index.js            # Application entry point
├── package.json            # Project dependencies and scripts
└── README.md               # Project documentation
```

### Key Components

- **App.js**: Contains the main application logic including:
  - State management for tasks
  - Task CRUD operations (Create, Read, Update, Delete)
  - Date and weekday calculation
  - Event handlers for user interactions

- **App.css**: Contains all styling including:
  - Responsive layout styles
  - Color scheme and gradients
  - Animations and transitions
  - Mobile-first responsive breakpoints

## 📸 Screenshots

### Features Highlight:
- **Gradient Background**: Modern cyan-to-blue gradient background
- **Task Input Section**: Clean input field with prominent "Add Task" button
- **Task List**: Organized display of all tasks with status indicators
- **Status Badges**: Clear visual distinction between Pending and Completed tasks
- **Action Buttons**: Intuitive buttons for status changes and deletion

## 🎨 Design Highlights

- **Color Scheme**: 
  - Primary: Cyan to Blue gradient (#06b6d4 → #3b82f6)
  - Pending: Yellow/Orange tones (#fbbf24, #d97706)
  - Completed: Green tones (#4ade80, #059669)
  
- **Typography**: Modern sans-serif font stack for optimal readability
- **Spacing**: Generous padding and margins for comfortable viewing
- **Animations**: Smooth fade-in and slide-in effects for better UX

## 📱 Responsive Design

The application is fully responsive and optimized for:
- **Desktop**: Full-width container with centered layout
- **Tablet**: Adaptive spacing and button sizing
- **Mobile**: Stacked layout with full-width buttons and optimized touch targets

## 🔮 Future Enhancements

Potential improvements for future versions:
- Local storage persistence for tasks
- Task categories or tags
- Due dates and reminders
- Task priority levels
- Search and filter functionality
- Drag-and-drop task reordering
- Dark mode toggle
- Export/import tasks functionality

## 📝 Assignment Context

This project was developed as an assignment for **Hexa Solutions**, demonstrating:
- React component development and state management
- Modern CSS styling and responsive design
- User interface design principles
- Clean code practices and project organization

## 🤝 Contributing

This is an assignment project. For any questions or feedback, please contact the project maintainer.

## 📄 License

This project is created for educational/assignment purposes.

---

**Developed with ❤️ using React**
