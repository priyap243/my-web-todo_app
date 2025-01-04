# To-Do List App

This Python application helps you manage your daily tasks efficiently through a simple and interactive to-do list interface.

## Prerequisites
* Python 3.x
* Streamlit (installed via requirements.txt)

## Usage
1. Clone the repository or download the files: `functions.py`, `web.py`, `todos.txt`, and `requirements.txt`.
2. Install all dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run web.py
   ```

## Description
* `functions.py`: Contains functions to handle reading from and writing to the `todos.txt` file.
* `todos.txt`: Stores the list of to-do items, one task per line.
* `web.py`: The main Streamlit application that provides a user-friendly interface for managing the to-do list.

## How It Works
1. The app reads tasks from `todos.txt` and displays them in the Streamlit interface.
2. Users can add new tasks using the text input field.
3. Completed tasks can be removed by checking the associated checkbox.
4. All changes are automatically saved to `todos.txt` for persistence.

## Configuration
* `todos.txt` serves as the storage file for to-do items. Ensure it exists in the same directory as the app files.
* Modify the `FILEPATH` variable in `functions.py` if you want to use a different file for storing tasks.

## Note
* The app is designed to boost productivity by providing a simple and intuitive task management system.
* Ensure that Streamlit is correctly installed and accessible from your command line.
* Customize the app as needed to better suit your specific workflow or preferences.
  
## Author
Priya Patel
Github: priyap243
