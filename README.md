<div align="center">

# 🏦 Regional Development Bank (RDB) – Website Project

### A Web-Based Redesign Concept for Regional Development Bank of Sri Lanka

A website project organized around the presentation of RDB information, financial resources, annual reports, and downloadable documents.

</div>

---

## 📖 Table of Contents

1. [Overview](#-overview)
2. [Project Contents](#-project-contents)
3. [Repository Structure](#-repository-structure)
4. [Technologies](#-technologies)
5. [Getting Started](#-getting-started)
6. [Running the Project](#-running-the-project)
7. [Configuration](#-configuration)
8. [Notes](#-notes)

---

## 📖 Overview

The **RDB Web Project** is a web development project related to the Regional Development Bank (RDB) of Sri Lanka. The repository contains website resources and supporting files organized into separate folders for HTML pages, stylesheets, JavaScript, backend resources, financial statements, annual reports, and downloadable documents.

The project is intended to provide a web-based way to browse RDB-related information and resources.

## ✨ Project Contents

The repository includes the following main content areas:

- **HTML pages** – website page files.
- **CSS resources** – stylesheets used to define the website presentation.
- **JavaScript resources** – scripts for client-side website behaviour.
- **Backend folder** – backend-related project files.
- **Financial statements** – financial statement resources.
- **Annual reports** – annual report documents.
- **Downloads** – downloadable resources.
- **Assets** – supporting website assets.

## 📂 Repository Structure

```text
RDB_Web_Project/
│
├── Assests/                 # Supporting website assets
├── Financial statementss/   # Financial statement resources
├── HTML/                    # HTML pages
├── annual reports/          # Annual report documents
├── backend/                 # Backend-related files
├── css/                     # Stylesheets
├── downloads/               # Downloadable resources
├── js/                      # JavaScript files
│
├── GOOGLE_MAPS_SETUP.md     # Google Maps configuration notes
├── broken_links.txt         # Broken-link tracking notes
├── nav_check.txt            # Navigation checking notes
├── package-lock.json        # npm lockfile
└── README.md
```

## 🛠 Technologies

The repository structure indicates the use of the following web technologies and resources:

| Technology / Resource | Purpose |
|---|---|
| HTML | Website page structure |
| CSS | Website styling and layout |
| JavaScript | Client-side interactions |
| Backend resources | Server-side project components |
| npm lockfile | Records npm package dependency state |
| Google Maps configuration | Setup notes for Google Maps integration |

> The repository listing does not identify the backend framework or a complete set of runtime dependencies. Those details should be confirmed from the backend source and its configuration files before installing or deploying the backend.

## ⚙️ Getting Started

### Prerequisites

- Git
- Visual Studio Code or another code editor
- A modern web browser
- Node.js and npm only if the backend or supporting scripts require them

### 1. Clone the Repository

```bash
git clone https://github.com/senath6932/RDB_Web_Project.git
```

### 2. Open the Project

```bash
cd RDB_Web_Project
code .
```

Alternatively, download the repository as a ZIP file from GitHub and extract it.

## ▶️ Running the Project

The repository contains an `HTML` folder and separate `css` and `js` folders. To preview an HTML page:

1. Open the project folder in Visual Studio Code.
2. Open the `HTML` folder.
3. Select the main HTML page (the page intended as the website entry point).
4. Right-click the HTML file and choose **Open with Live Server** if the Live Server extension is installed.

You can also open an HTML file directly in a browser. If the page uses server-side functionality, API routes, or backend services, opening the HTML file alone will not start those services.

### Backend

A `backend` folder is present in the repository. Its exact startup command and required environment variables need to be taken from the backend's own configuration and documentation. Check for files such as `package.json`, `requirements.txt`, or a backend README before running it. Do not assume a command or framework that is not specified by the project.

## 🗺 Google Maps Configuration

The repository includes [`GOOGLE_MAPS_SETUP.md`](./GOOGLE_MAPS_SETUP.md), which contains project-specific Google Maps setup information. Refer to that guide if the website requires Google Maps functionality.

Keep API keys private and follow the restrictions and configuration instructions in the setup guide.

## 📝 Notes

- The repository includes tracking files for navigation checks and broken links.
- The folder names `Financial statementss` and `Assests` are preserved as they appear in the repository.
- The root `package-lock.json` currently records an empty package set. It does not, by itself, establish the dependencies or run command for the backend.
- Before deployment, verify the main entry page, backend setup, required API keys, and any external document or map resources.

---

<div align="center">

**Regional Development Bank – Web Project**

</div>
