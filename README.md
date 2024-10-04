# Directory Tree Generator
This script generates a tree of directories and files in a given directory.

The file `Directory Tree Generator.ipynb` is a Jupyter Notebook that contains a Python script for generating a visual representation of the directory structure of a given folder. The script uses the `os` module to traverse directories and files, printing them in a tree-like format.

### Key Components:
1. **Importing the `os` Module**:
   - The script starts by importing the `os` module, which provides functions for interacting with the operating system, particularly for file and directory operations.

2. **Function Definition**:
   - The `generate_tree` function is defined to recursively traverse a directory and print its structure.
   - **Parameters**:
     - `directory`: The path of the directory to be traversed.
     - `prefix`: A string used to format the output, indicating the level of depth in the directory tree.
   - **Functionality**:
     - Checks if the provided path is a valid directory.
     - Prints the name of the directory.
     - Iterates through the items in the directory.
     - Recursively calls itself for subdirectories.
     - Prints file names with the appropriate prefix.

3. **Function Calls**:
   - The `generate_tree` function is called twice with different directory paths to demonstrate its functionality.
   - The first call uses a valid directory path, while the second call uses an invalid path to show the error handling.

### Example Output:
- The script prints the directory structure in a hierarchical format, with subdirectories and files indented to show their levels.

### Usage:
- This script can be used to quickly visualize the structure of any directory, making it useful for understanding the organization of files and folders in a given path.