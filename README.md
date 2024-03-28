Automatic File Sorter

The Automatic File Sorter is a Python script designed to organize files into their respective folders based on their file extensions. 
This tool automates the process of file management, making it easier to maintain a tidy workspace.

Features
Automated Sorting: Files are automatically sorted into predefined folders based on their file extensions.
Repetitive Sorting: The script runs at regular intervals, ensuring that files are consistently organized.
Error Handling: Robust error handling mechanisms ensure smooth operation, providing feedback in case of any issues.

Technology Used:
Os and Shutil -  The File Sorter is developed using standard libraries such as os and shutil which are Python 
standard libraries used for interacting with the operating system and performing file system operations.
Using os.path.exists to check whether the path exists or not
os.makedirs to create the new directories within that specified path
shutil.move to move the file from the current path location to their respective folder 

Time Module - Using Time module to perform the repetitive file sorting process by using time.sleep function
which accpet the parameters in second.
