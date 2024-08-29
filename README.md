# Global Store X Editor
### Global Store X File Editor Created for Clickteam's Game Development Products.

![Screenshot 2024-07-25 220950](https://github.com/user-attachments/assets/6b423a6d-dd31-4f36-907b-54d6db8bfdc1)


### This tool allows you to view and edit the internal structure of "Global Store X" files, which are typically used to store various data types in a structured format. This guide will help you understand how to use the application and make the most out of its features.

### 1. Interface Overview

*	New File Button:
	*	Clears the current data in the editor, allowing you to start editing a new Global Store X file from scratch.

*	Open File Button:
	*	Open File: Allows you to browse your file system and open an existing Global Store X file.
	*	Open Latest File: Provides a quick way to reopen the most recently accessed file.

*	Save File Button:
	*	Save File: Saves the current file with its existing name and location.
	*	Save File As: Allows you to save the current file under a new name or in a different location.

*	Editor Pane:
	*	The large text area where the content of the Global Store X file is displayed and can be edited. The file contents are divided into sections such as [Values], [Strings], [Bools], and [Shorts]. Each section has its own data type and structure. You can directly edit the data in this pane, ensuring that you maintain the correct file structure.

### 2. File Structure Overview

* [Values] Section:
	* NoOfValues: Indicates the number of value entries in this section.
	* Base: A reference or base number, often used as a starting index or reference.
	* 0, 1, 2, ...: Indexes for individual values, followed by their corresponding value.

* [Strings] Section:
	* NoOfStrings: Indicates the number of string entries in this section.
	* Base: A reference or base number for the string indexes.
	* 0, 1, 2, ...: Indexes for individual strings, followed by their corresponding text.

* [Bools] Section:
	* NoOfBools: Indicates the number of boolean entries in this section.
	* Base: A reference or base number for the boolean indexes.
	* 0, 1, 2, ...: Indexes for individual booleans, followed by their true (1) or false (0) value.

* [Shorts] Section:
	* NoOfShorts: Indicates the number of short integer entries in this section.
	* Base: A reference or base number for the short integer indexes.
	* 0, 1, 2, ...: Indexes for individual short integers, followed by their corresponding value.

### 3. Tips for Effective Use

*	Backup Files:
	*	 Before making significant changes, it's recommended to back up your original Global Store X files to avoid data loss.
	
*	Maintain Structure:
	*	 Always ensure that the structure of the file is maintained. Incorrect formatting can lead to errors when the file is used in its corresponding application.

*	Incrementing Indexes:
	*	 When adding new entries (e.g., new values, strings, etc.), make sure the indexes are incremented sequentially to avoid conflicts.

*	Keyboard Shortcuts:
	*	 To improve your efficiency, Global Store X Editor supports the following keyboard shortcuts:
			* New File: Ctrl + N
			* Open File: Ctrl + O
			* Open Latest File: Ctrl + Shift + O
			* Save File: Ctrl + S
			* Save File As: Ctrl + Shift + S

### 4. Troubleshooting

*	File Won't Save:
	*	Ensure that you have write permissions in the directory you're trying to save the file to. Also, check if the file path is correct and that the file is not open in another application.

*	File Errors on Load:
	*	If you encounter errors when loading a Global Store X file, it could be due to incorrect formatting or corrupted data. Try opening a different file or revert to a backup.

