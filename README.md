# PESU GPA Calculator

This is a web-based GPA calculator designed for **PES University** students. It helps students compute their **SGPA (Semester Grade Point Average)** based on the grades they receive in their courses. The application is built using **Streamlit**, a Python library for creating interactive web applications.

---

## Features

- **SRN Validation**: 
  - Ensures that the entered SRN (Student Registration Number) is valid before proceeding with the GPA calculation.
  - This feature is implemented using **regular expressions**.

- **Semester Selection**:
  - Users can select their **semester** or **cycle** (Physics or Chemistry Cycle).
  - Currently, the app works for **1st-year, 1st-semester topics**.

- **Course-wise Input**:
  - Users can input their marks for various assessments including:
    - **ISA1**, **ISA2**, **ESA**, and any **assignments** or **lab work**.

- **SGPA Calculation**:
  - The app computes the **SGPA** based on the entered grades and credits of the courses.
  - **CGPA** calculation is not yet implemented but can be added in the future.

---

## Usage

1. **Enter Your SRN**: 
   - Input your **Student Registration Number** in the provided field. The system will validate the format.

2. **Select Your Semester or Cycle**:
   - Choose the appropriate **semester** or **cycle** (Physics/Chemistry) from the dropdown menu.

3. **Enter Marks for Each Course**:
   - Input the marks for **ISA1**, **ISA2**, **ESA**, and any other relevant assignments or lab work.

4. **SGPA Calculation**:
   - After entering the data, the application will automatically compute your **SGPA** based on the grades and credits.

---

## Installation

To run this application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Abhirambobba/PESU-GPA-CALCULATOR.git
