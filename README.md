# File Badger
![logoForApp](https://github.com/necatisahin/kafka-producer-consumer/assets/17224549/0e00b68f-091f-42e1-9e75-042d74ee35e6)

File Badger is a desktop application designed to help developers manage file chaos by automatically organizing files based on tasks. When you save a new file in specified applications, File Badger will create a copy in a destination folder, organizing files according to tasks.

## Overview

![overview3](https://github.com/necatisahin/kafka-producer-consumer/assets/17224549/0f29b659-dc7e-443e-9237-7c15ee650bc6)
![settingsoverview](https://github.com/necatisahin/kafka-producer-consumer/assets/17224549/cbf8f28d-51e1-4d61-821d-1be7839aefcb)
![overview2](https://github.com/necatisahin/kafka-producer-consumer/assets/17224549/532b5cad-ce5e-488e-b19e-25bbf5afbd62)


## Usage

1. Launch File Badger.
2. Navigate to the settings menu and configure the following options:

   - **Source Application Paths**: Specify the paths of the applications you want to monitor for new file saves (e.g., Notepad++, DBVisualizer).
   - **Destination Folder**: Select the root folder where task-based subfolders will be created.
   - *(Optional)* Other settings based on your preferences.

3. Click the "File Badger On" button to pole folder paths.

Now, whenever you save a new file in one of the specified source applications, File Badger will automatically create a copy organized into a subfolder corresponding to the current task.
![overview](https://github.com/necatisahin/kafka-producer-consumer/assets/17224549/8b304088-16f3-428a-b256-393bf760ddee)


## Task-Based Archiving System

File Badger employs a task-based archiving system to help you keep your files organized. When you save a file in a source application, it will be copied to a subfolder named after the current task. This way, you can easily locate and manage files related to specific projects or tasks.

![folder management](https://github.com/necatisahin/kafka-producer-consumer/assets/17224549/6c56cf37-cd50-43f4-bc55-091a9ccb2d8a)

## Task Selection and File Organization

File Badger allows you to associate files with specific tasks, making it easier to keep your projects organized. Follow these steps to select a task and organize your files:

Choose the current task from the dropdown menu.

![notepad++112](https://github.com/necatisahin/kafka-producer-consumer/assets/17224549/4cb7e4c9-7059-4aa6-a0d9-d8f9f87ffd32)

## File Copying in Action

To demonstrate how File Badger works in real-time, check out the gif below. It showcases the application in action, copying new files from Notepad++, DBeaver, and the Downloads folder:
![all](https://github.com/necatisahin/kafka-producer-consumer/assets/17224549/c2be095f-ef20-4c9c-bcbd-bc694cdf9f0b)


## Settings

To demonstrate how to set up a watched folder and configure the application to copy files when a new one is added, check out the gif below:
![settings](https://github.com/necatisahin/kafka-producer-consumer/assets/17224549/00b9d7a6-b4a0-44ce-8597-050fdd9ae9d8)

## Installation

Follow these steps to install and run File Badger on your system:

1. **Download Required Files:**
   - Navigate to the [https://github.com/necatisahin/file-badger](https://github.com/necatisahin/file-badger).
   - Download the `fileBadger`and `openjfx-21_windows-x64_bin-sdk` folder.

2. **Adjust Path in `startFileBadger.bat`:**
   - Open the `startFileBadger.bat` file in a text editor.
   - Update the path based on the location where you downloaded the `openjfx-21_windows-x64_bin-sdk` folder.

     ```bash
     start javaw --module-path "C:\Path\To\openjfx-21_windows-x64_bin-sdk\javafx-sdk-21\lib" --add-modules javafx.controls,javafx.fxml -jar app.jar
     ```

3. **Run `startFileBadger.bat`:**
   - Save the changes to the `startFileBadger.bat` file.
   - Double-click on `startFileBadger.bat` to launch File Badger.

Now, File Badger should be up and running on your system. If you encounter any issues or have questions, please refer to the [GitHub repository](https://github.com/necatisahin/file-badger) for support.








## Support and Issues

If you encounter any issues or have questions, please [open an issue](https://github.com/necatisahin/file-badger) on the GitHub repository.
