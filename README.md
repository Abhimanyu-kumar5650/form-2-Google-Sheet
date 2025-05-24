## 📝 Project Overview

This project provides a web-based form interface that, upon submission, sends the collected data to a specified Google Sheet. It leverages HTML and CSS for the frontend form design and utilizes Google Apps Script to handle the backend data processing and integration with Google Sheets.

---

## 🚀 Features

* **User-Friendly Form Interface**: A clean and responsive HTML/CSS form for data collection.
* **Google Sheets Integration**: Seamless submission of form data to a designated Google Sheet using Google Apps Script.
* **Customizable Design**: Easy to modify form fields and styling to suit specific requirements.

---

## 📁 Project Structure

The repository contains the following key files:

* `index.html`: The main HTML file containing the form structure.
* `style.css`: CSS file for styling the form and enhancing its appearance.
* `background.jpg`: Background image used in the form's design.
* `send-icon.webp`: Icon used for the form's submit button.

---

## ⚙️ Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Abhimanyu-kumar5650/form-2-Google-Sheet.git
   ```



2. **Open `index.html`**:
   Use a web browser to open the `index.html` file and view the form.

3. **Configure Google Apps Script**:

   * Create a new Google Sheet where you want to store the form responses.
   * Navigate to `Extensions` > `Apps Script` in the Google Sheet.
   * Replace the default code with a script that handles form submissions and appends data to the sheet.
   * Deploy the script as a web app and obtain the URL.([GitHub][1])

4. **Update Form Action URL**:
   In the `index.html` file, set the form's `action` attribute to the URL of the deployed Google Apps Script web app.

5. **Test the Form**:
   Submit the form and verify that the data appears in your Google Sheet.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

Inspired by the need for a straightforward method to collect form data into Google Sheets without relying on third-party services.
