# Taskly-App-using-Flutter-and-Dart

Taskly is a simple yet powerful task management app built using Flutter. It leverages the flutter_hive database for efficient, local, and persistent data storage. This README will guide you through setting up, running, and understanding the core functionalities of the Taskly app.

# Features

Task Management: Create, read, update, and delete tasks.
Local Storage: Uses flutter_hive for storing tasks locally on the device.
User-friendly UI: Intuitive and easy-to-navigate user interface.
Offline Access: Access your tasks even when you are offline.

# Prerequisites

Before you begin, ensure you have met the following requirements:

1. Flutter installed on your local machine. You can follow the official Flutter installation guide.
2. Dart SDK.
3. A suitable IDE like Visual Studio Code or Android Studio.

# Dependencies

The main dependencies used in this project are:

1. Flutter
2. Hive
3. hive_flutter

These dependencies are specified in the pubspec.yaml file.

# Usage
# Creating a Task 

1. Open the app.
2. Tap on the "Add Task" button.
3. Enter the task details and save.

# Viewing Tasks

Tasks are displayed on the home screen in a list format. Each task shows its title and completion status.

# Updating a Task

1. Tap on a task in the list to open the task details.
2. Edit the details and save the changes.
3. 
# Deleting a Task

1. double click or hold click for 2 seconds.

# Hive Database Integration

Hive is initialized in the main.dart file. Make sure to initialize Hive and register the adapter before running the app:

