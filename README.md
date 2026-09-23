# R.C. Technical Institute Website

A responsive, multi-page website for **R.C. Technical Institute**, Ahmedabad. Built using **HTML5**, **Bootstrap 5**, and **JavaScript**, featuring a clean design and modular header/footer component loading via JavaScript Fetch API.

---

## 🚀 Features

- **Responsive Design**: Adapts seamlessly to mobile, tablet, and desktop viewports using Bootstrap 5.
- **Dynamic Header & Footer**: Uses JavaScript Fetch API to include reusable `header.html` and `footer.html` elements across all pages, keeping code DRY (Don't Repeat Yourself).
- **Navigation Bar**: Includes an interactive responsive menu toggle (hamburger menu) and dropdown for department courses.
- **Dedicated Pages**:
  - `index.html`: Home page featuring institute details and banner image.
  - `about.html`: Vision and Mission of the institute/department.
  - `course.html`: Itemized view of all available engineering and technical streams.
  - `contact.html`: Contact details including address, email, and phone information.

---

## 🛠️ Technologies Used

- **HTML5**: Page structure and semantic elements.
- **Bootstrap 5.3.3**: Layout grid, UI components, and utility classes via CDN.
- **JavaScript (ES6)**: Fetch API for dynamic header/footer injection and DOM manipulation.

---

## 📂 Project Structure

```text
├── index.html        # Main landing page
├── about.html        # Vision and Mission page
├── course.html       # Offered courses list
├── contact.html      # Contact information page
├── header.html       # Shared header and footer template component
├── logo.jpg          # Institute logo image
└── clg.avif          # Campus banner image

⚙️ How to Run Locally
Because the project uses JavaScript fetch() to load the header.html file, opening index.html directly via file:// in a browser may cause CORS issues.

Please run it using a local server:

Option 1: VS Code Live Server Extension (Recommended)
Open the project folder in Visual Studio Code.

Install the Live Server extension.

Right-click index.html and select Open with Live Server.

Option 2: Python HTTP Server
Run the following command in your terminal from the project directory:

Bash
# Python 3
python -m http.server 8000
Then open http://localhost:8000 in your browser.

📄 License
© 2026 R.C. Technical Institute, Ahmedabad, Gujarat, India. All rights reserved.
