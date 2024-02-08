# Compress_Files_and_Folder_assignment
## Folder Compression Script
- Author: Jason Nwachukwu

##Description
This script allows users to compress folders into various archive formats such as ZIP, TAR, and TGZ. Users are prompted to enter the path of the folder they want to compress, as well as the desired compression format. The script then compresses the folder accordingly.

##Prerequisites
Python 3.x installed on your system.
Basic understanding of the command line interface.

##Usage
Clone or download the script to your local machine.
Open a terminal or command prompt.
Navigate to the directory containing the script.

Run the script by executing the following command:
python folder_compression.py
Follow the on-screen prompts to enter the folder path and select the compression format.
Once the compression is complete, the script will display a message indicating the success or failure of the operation.

##Functionality
compress_folder(folder_path, compress_type):

This function compresses the specified folder using the provided compression format.
It handles three compression formats: ZIP, TAR, and TGZ.
If the compression is successful, it prints a message with the name of the compressed file.
If an error occurs during compression, it prints an error message.
main():

This is the main function that drives the script's functionality.
It continuously prompts the user to enter the folder path and compression format until the user chooses to quit.
It validates user inputs and handles errors gracefully.
Example
Suppose you want to compress a folder named "my_folder" located at "/path/to/my_folder" into a ZIP file. You would run the script, enter "/path/to/my_folder" as the folder path, select "1" for ZIP compression, and the script will create a ZIP file named "my_folder_YYYY_MM_DD.zip" in the current directory.

##Notes
Ensure that you have appropriate permissions to read the folder and write the compressed file.
The script uses the current date to append to the compressed file name for uniqueness.
If the folder or file path contains spaces or special characters, enclose it in double quotes (e.g., "/path/to/my folder").
