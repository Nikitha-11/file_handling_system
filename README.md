# Web Application for Excel File Filtering System

## Description
This project is a web application designed to process and filter data from up to five Excel files. Users can upload Excel files containing records with predefined fields and specify a time duration in a given format (e.g., hours, minutes, and seconds). The system reads the files sequentially and filters out records where the total duration exceeds the specified threshold. The filtered data is then exported into a new Excel file for further use.

---

## Features
- Accepts 1 to 5 Excel files as input.
- Filters records based on a user-defined time duration.
- Processes each Excel file sequentially.
- Exports the filtered records into a newly generated Excel file.
- Built using *React* for handling Excel operations.

---

## File Requirements
Each Excel file must contain records with the following fields:
- Student Register No.
- Admn No.
- Student Name
- Block Description
- Transaction-Type
- G No
- OT
- OPurpose
- IT
- IPurpose
- Duration
- Total-Duration

---

## Usage
1. Download the repository files from GitHub.
2. Open the project folder and locate the `index.html` file.
3. Open the `index.html` file in any web browser to access the application.
4. Follow the interface instructions to upload Excel files and specify a time duration for filtering.
5. Download the filtered data as a new Excel file.

---

## Folder Structure
```plaintext
file_handling_system/
├── main-page/
│   ├── index.html
│   ├── assets/
│       └── images/
│           └── bg2
