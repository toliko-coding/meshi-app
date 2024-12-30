# Repair and Fault Report Form

This project is a single-page web application for managing repair and fault reports for equipment. The form allows users to input, track, and submit various details related to tool inspections, faults, and maintenance procedures. Submitted data is integrated with **Google Sheets** as the backend database for efficient data storage and retrieval.

---

## Features

1. **Responsive Design**:
   - The form adapts to different screen sizes, ensuring a user-friendly experience on both desktop and mobile devices.

2. **Data Input Sections**:
   - **Command Information**: Includes fields for command number, tool type, manufacturer number, status, unit code, critical failure details, and location of execution.
   - **Entry and Exit Records**: Captures information about entry and release dates, operating hours, and inspector names.
   - **Faults Section**: Allows users to add multiple fault descriptions dynamically.
   - **Inspector Details**: Includes fields for the inspector’s name, signature, and notes.

3. **Interactive Fault Management**:
   - Users can add multiple faults dynamically with an "Add Fault" button.

4. **Google Sheets Integration**:
   - Data submitted via the form is stored in **Google Sheets**, making it easy to view, update, and analyze reports.

5. **JavaScript Functionality**:
   - Dynamic addition of fault fields.
   - Submission of form data to Google Sheets for processing and storage.

---

## How to Use

1. **Access the Form**:
   - Open the HTML file in any modern web browser.

2. **Fill Out the Form**:
   - Input details in the provided fields.
   - Use the "Add Fault" button to include additional fault descriptions as needed.

3. **Submit the Data**:
   - Click the "Submit Form" button to send the data to **Google Sheets**.
   - Ensure all required fields are filled before submission.

---

## Technology Stack

- **HTML**: Structure of the form.
- **CSS**: Styling for responsiveness and design.
- **JavaScript**: 
  - Dynamically handles fault entries.
  - Submits form data to **Google Sheets**.
- **Google Apps Script**:
  - Processes and manages the integration with **Google Sheets**.

---

## File Structure

- **HTML File**:
  Contains all the structure, styles, and scripts for the single-page application.

---

## Installation and Deployment

1. **Clone or Download the Repository**:
   - Save the HTML file to your desired directory.

2. **Set Up Google Sheets Integration**:
   - Create a new Google Sheet.
   - Use Google Apps Script to create a backend script that processes the form data.
   - Update the JavaScript code in the HTML file to connect with your Google Apps Script deployment.

3. **Open the File**:
   - Open the file in a modern web browser like Chrome, Firefox, or Edge.

4. **Customization (Optional)**:
   - Modify the `background-image` URL in the CSS section to include a custom background.

---

## Future Improvements

- **Enhanced Google Sheets Features**:
  - Add automation for generating reports and summaries directly within Google Sheets.
- **Validation Enhancements**:
  - Implement client-side and server-side validation for better data accuracy.
- **Language Support**:
  - Expand language support for global usability.

---

This web application integrates seamlessly with **Google Sheets**, serving as a reliable and efficient tool for managing repair and maintenance reports. It is easily customizable for specific organizational needs.
