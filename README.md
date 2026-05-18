# Modero - Flutter Todo App

A clean and simple Flutter todo application to manage your daily tasks efficiently.

## Features

✅ **Create Tasks** - Add new tasks with title and description  
✅ **View Tasks** - See all active and completed tasks  
✅ **Mark Complete** - Toggle task completion status  
✅ **Edit Tasks** - Update task details  
✅ **Delete Tasks** - Remove tasks you no longer need  
✅ **Task Organization** - Filter between active and completed tasks  

## Project Structure

```
lib/
├── main.dart                 # App entry point with Provider setup
├── models/
│   └── todo.dart            # Todo data model
├── providers/
│   └── todo_provider.dart   # State management using Provider
├── screens/
│   └── home_screen.dart     # Main screen with bottom navigation
└── widgets/
    ├── todo_item.dart       # Individual todo card
    ├── add_todo_dialog.dart # Dialog to create tasks
    └── edit_todo_dialog.dart# Dialog to edit tasks
```

## Getting Started

### Prerequisites

- Flutter SDK (3.0.0 or higher)
- Dart SDK (included with Flutter)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/am9729992-afk/modero.git
cd modero
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Dependencies

- **provider**: State management solution
- **uuid**: Generate unique IDs for tasks
- **flutter**: UI framework

## Architecture

This app follows a clean architecture pattern with:

- **Models**: Data classes that define the structure of todos
- **Providers**: Business logic and state management using the Provider package
- **Screens**: Main UI components
- **Widgets**: Reusable UI components

## Usage

1. **Add a Task**: Tap the floating action button (+) to create a new task
2. **Mark Complete**: Check the checkbox to mark a task as complete
3. **Edit a Task**: Tap the edit icon to modify task details
4. **Delete a Task**: Tap the delete icon to remove a task
5. **Filter Tasks**: Use the bottom navigation to toggle between Active and Completed tasks

## Future Enhancements

- Local database integration (SQLite/Hive)
- Push notifications
- Cloud synchronization
- Dark mode support
- Task categories/tags
- Due dates and reminders

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## Author

Created by **am9729992-afk**
