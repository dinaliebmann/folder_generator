# Folder Generator

This was a commissioned project that takes in an excel file and creates a folder structure. For each page, a folder is created and within it, subfolders concatenating the first three columns of each row.  

This program is used on a weekly basis to generate a folder system for athlete's photographs and videos, and was created for the layman to use (and troubleshoot) easily. Simply follow the instructions provided!

## Instructions
### File Preparation

- Your excel workbook must be in the following format, with no headers. See the attached excel for an example.

  | # | firstname | lastname |
  |----|-----------|----------|

- The name of each page will become the name of each foler, and the subfolders will be of the form `#-firstname-lastname`
- Save the file as `names.xlsx`

### Running the program

- If running for the first time, enter the following commands into the terminal
  ```
  sudo easy_install pip
  sudo pip install -r requirements.txt
  ```
- To run the version with 3-digit numbers, enter the following into the terminal
  ```
  python create_names_000.py
  ```
- To run the version with 4-digit numbers, enter the following into the terminal
  ```
  python create_names_0000.py
  ```
  