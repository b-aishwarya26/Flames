# FLAMES Game using Streamlit

## Overview
This is a simple FLAMES game built using Streamlit, a Python framework for creating interactive web applications. The game takes two names as input, removes common letters, and determines the relationship type based on the remaining characters.

## Prerequisites
Ensure you have Python installed on your system.

## Setting Up the Virtual Environment
To create a virtual environment, run the following command:
```bash
python -m venv env
```
Activate the virtual environment:
- On Windows:
  ```bash
  env\Scripts\activate
  ```
- On macOS/Linux:
  ```bash
  source env/bin/activate
  ```

## Installation
Install the required dependencies using:
```bash
pip install streamlit
```

## Running the Application
To run the Streamlit app, execute the following command in the terminal:
```bash
streamlit run app.py
```
Replace `app.py` with the name of your Python file containing the FLAMES game code.

## How the Game Works
1. Enter two names in the input fields.
2. Common letters between the names are removed.
3. The remaining letters are counted and used to determine the FLAMES result:
   - **F** - Friends
   - **L** - Love
   - **A** - Affection
   - **M** - Marriage
   - **E** - Enemies
   - **S** - Siblings
4. Click the "Get Results" button to see the outcome.

## Example Usage
- Input: **John, Mary**
- Process: Remove common letters
- Remaining letters count: Used to determine the relationship
- Output: One of the FLAMES categories

## Notes
- Ensure Streamlit is installed before running the script.
- This is a fun, non-scientific game and should be taken lightly!

## License
This project is open-source and free to use for educational and entertainment purposes.

