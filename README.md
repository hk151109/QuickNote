# QuickNote 
![QuickNote Logo](https://github.com/hk151109/QuickNote/blob/main/img/256px-Icon-notepad.svg.png)

QuickNote is a simple and lightweight Chrome extension designed for taking quick notes directly in your browser. You can save notes to local storage, export them to a text file, and import notes from your own files for convenient editing – all without leaving your browser.

## Features

- **Local Storage Saving**: Your notes are automatically saved to local storage, so you won’t lose your text on refresh.
- **File Export**: Quickly export your notes to a `.txt` file.
- **File Import**: Easily import a text file and load its contents into QuickNote.
- **Minimal UI**: A simple and clean interface lets you focus on your notes.

## Screenshot

![QuickNote Screenshot](https://github.com/hk151109/QuickNote/blob/main/img/UI_SS.png)

## Installation

1. **Download or Clone the Repository**  
   - Click the green "Code" button in GitHub to clone or download this project as a ZIP file.
2. **Open the Chrome Extensions Page**  
   - In Google Chrome, navigate to `chrome://extensions/`.
3. **Enable Developer Mode**  
   - Toggle the **Developer mode** switch (usually located in the top-right corner).
4. **Load Unpacked**  
   - Click **Load unpacked** and select the folder containing this project’s files (including `manifest.json`).

Once loaded, the QuickNote extension’s icon will appear in your browser’s toolbar.

## Usage

1. **Open the Extension**  
   - Click on the QuickNote icon in the Chrome toolbar.  
2. **Editing Notes**  
   - Type directly into the text area. Your text will be automatically restored from your last session.
3. **Save to Local Storage**  
   - Click **Save to Local Storage**. You can close the extension and reopen it later without losing your notes.
4. **Exporting Notes**  
   - Click **Save to File** to download your notes as a `download.txt` file.
5. **Importing Notes**  
   - Use the **Choose File** button to select a text file. Its contents will automatically be loaded into the text area.

## Project Structure

- **img**: The directory contains the logo and a screenshot of the Extension UI.
- **popup.html**: The HTML layout for the QuickNote UI.
- **script.js**: Contains the logic for saving/loading from local storage and handling file I/O.
- **manifest.json**: Defines the extension’s metadata and configuration.

## Contributing

Contributions are welcome! If you have ideas or suggestions for improvements, feel free to open an issue or submit a pull request.
