Data Entry Form

This project is a simple **Data Entry Form** application built using Python's `tkinter` library. It captures user details and saves them into an Excel file, making it easy to store and retrieve information.

## Features

- User Information Section: Collects first name, last name, title, age, and nationality.
- Course Information Section: Captures registration status, the number of completed courses, and the number of semesters.
- Terms & Conditions: Ensures the user agrees to the terms before submitting.
- Data Storage: Automatically saves the data in an Excel file (`data.xlsx`) using `openpyxl`.

## Requirements

- Python 3.x
- Required libraries:
  - `tkinter`
  - `openpyxl`
  
You can install `openpyxl` with:
```bash
pip install openpyxl
```

## Installation and Usage

1. Clone the repository.
2. Make sure you have Python 3 installed.
3. Run the `data_entry_form.py` script:
   ```bash
   python data_entry_form.py
   ```

4. A window will open allowing data entry. Complete the fields and accept the terms to save your data.

5. Submitted data will be saved to `data.xlsx` in the specified directory. If `data.xlsx` does not exist, the program will create it.

## File Structure

```plaintext
data_entry_form.py     # Main script for running the Data Entry Form
data.xlsx              # Excel file where data is stored (generated automatically)
```

## License

This project is licensed under the MIT License.

---

Feel free to update paths or any additional information specific to your needs.
