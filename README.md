# Notepad Application

A simple Notepad application built using Java Swing, offering basic text editing functionalities like creating, opening, saving files, cut/copy/paste operations, and word wrap toggling. It also includes a live status bar displaying character count, line count, column, row, and word count.

## Features

- **Create New File:** Start with a blank text area to write and edit.
- **Open File:** Open `.txt` files and edit them in the application.
- **Save File:** Save your current text to a `.txt` file.
- **Clipboard Operations:** Cut, copy, and paste text.
- **Word Wrap Toggle:** Enable or disable word wrapping.
- **Status Bar:** Displays the following:
  - Character count
  - Line count
  - Column and row position of the cursor
  - Word count
- **File Filter:** The `Open` dialog shows `.txt` files by default.
- **Responsive Interface:** The application uses a simple and clean Swing-based interface with a menu bar and a status bar.

## Requirements

- **Java Version:** 1.8 or higher (the application uses Java Swing components, which are available in JDK 8 and above).
- **IDE (Optional):** Any Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans).
- **JDK:** Ensure the JDK is installed and configured properly on your machine.

## Setup and Installation

1. **Clone the Repository:**
   You can clone the project repository to your local machine:
   ```bash
   git clone https://github.com/nehamurthy2005/notepad.git
   ```

2. **Compile the Java Code:**
   Open the project folder in your terminal or IDE and compile the code using the following command:
   ```bash
   javac com/mycompany/notepad/Notepad.java
   ```

3. **Run the Application:**
   After compiling, you can run the application with:
   ```bash
   java com.mycompany.notepad.Notepad
   ```

4. **IDE Setup (Optional):**
   If you're using an IDE (e.g., IntelliJ IDEA or Eclipse), simply open the project folder and run the `Notepad.java` file.

## Usage

1. **Creating a New File:**
   - Click on the **File > New** menu option to clear the text area and start writing from scratch.

2. **Opening a File:**
   - Click on **File > Open**, and select a `.txt` file from your computer to open and edit.

3. **Saving a File:**
   - Click on **File > Save** to save the current text to a file. If no file has been opened before, you will be prompted to choose a location to save the file.

4. **Editing Text:**
   - The text area allows for basic typing and editing. Use **Cut**, **Copy**, and **Paste** from the **Edit** menu or use keyboard shortcuts:
     - **Ctrl + X** (Cut)
     - **Ctrl + C** (Copy)
     - **Ctrl + V** (Paste)

5. **Toggle Word Wrap:**
   - You can toggle the word wrap feature on and off from the **View > Word Wrap** menu. When enabled, long lines will wrap automatically.

6. **Status Bar:**
   - The status bar at the bottom shows the current cursor position (row and column), the number of characters, words, and lines in the document. The counts update as you type.

## Screenshots

**Main Window:**

![Notepad Screenshot](screenshots/main_window.png)

**File Open Dialog:**

![Open File Dialog](screenshots/open_file.png)

**Status Bar:**

![Status Bar](screenshots/status_bar.png)

## Future Enhancements

- **Find and Replace:** Add the ability to search for text and replace it.
- **Undo/Redo:** Implement undo and redo functionality to support better editing experience.
- **Font Selection:** Add an option to select different fonts, sizes, and styles.
- **File Encoding:** Allow the user to choose file encoding (UTF-8, ANSI) when opening and saving files.
- **Drag and Drop Support:** Enable drag-and-drop functionality for opening files.

## Contribution

If you'd like to contribute to this project, feel free to open a pull request. You can also file issues or suggest enhancements.

1. Fork the repository.
2. Clone your fork:
   ```bash
   git clone https://github.com/yourusername/notepad.git
   ```
3. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
4. Make your changes and commit them.
5. Push to your forked repository.
6. Open a pull request with a detailed explanation of your changes.

## License

This project is open-source and available under the MIT License.

---

Let me know if you'd like to adjust anything or if you'd like help with other parts of your project!
