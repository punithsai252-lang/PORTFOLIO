# 🌐 Punith Sai — Personal Portfolio

A simple, responsive personal portfolio website built using **HTML5 and CSS3**.
The website showcases my profile, technical skills, projects, education, and contact information.

---

## 📌 About the Project

This portfolio website is designed to provide an overview of my academic background, programming skills, projects, and interests in **Artificial Intelligence and Machine Learning**.

The website uses a clean and simple interface with:

* Navigation menu
* Profile section
* About Me section
* Skills section
* Projects section
* Education table
* Contact information
* Responsive design for smaller screens

---

## 🛠️ Technologies Used

* **HTML5** — Website structure and content
* **CSS3** — Styling, layout, colors, shadows, and responsiveness
* **Responsive Web Design** — Media queries for mobile devices

---

## 📂 Project Structure

```text
Portfolio/
│
├── index.html
├── phot
└── README.md
```

### Files Description

| File         | Description                         |
| ------------ | ----------------------------------- |
| `index.html` | Main portfolio webpage              |
| `phot`       | Profile image used in the portfolio |
| `README.md`  | Project documentation               |

> **Note:** Rename the profile image to something like `profile.jpg` or `profile.png` and update the image path in `index.html`.

---

## ✨ Features

### 1. Navigation Bar

The navigation bar provides links to different sections of the portfolio:

* About
* Skills
* Projects
* Education
* Contact

The links use HTML section IDs to navigate within the same webpage.

---

### 2. Hero Section

The hero section displays:

* Profile photo
* Full name
* Professional/academic description

Example:

```text
Gitta Punith Sai Madhav
B.Tech Student | Java Developer | AI & ML Enthusiast
```

---

### 3. About Me

The About Me section provides a brief introduction and describes interests in:

* Programming
* Data Structures
* Artificial Intelligence
* Machine Learning
* Computer Vision

---

### 4. Skills

The portfolio currently includes the following skills:

* Java Programming
* Data Structures & Algorithms
* HTML & CSS
* Machine Learning Basics
* MobileNet & YOLO
* Computer Vision

---

### 5. Projects

The Projects section highlights three projects:

#### 🚧 Pothole Detection System

A computer vision project using **MobileNet V2 and YOLO** for real-time road damage detection.

#### 💻 Data Structures Implementation

Java implementations of common data structures and algorithms such as:

* Stack
* Queue
* Linked List
* Merge Sort

#### 🎓 Student Management System

A console-based Java application designed to manage student records.

---

### 6. Education

The education section uses an HTML table to display:

* Degree
* Institution
* Year
* CGPA/Percentage

Current educational details include:

| Degree           | Institution              | Year      |
| ---------------- | ------------------------ | --------- |
| B.Tech (AI & DS) | KL University            | 2025–2029 |
| Intermediate     | Resonance Junior College | 2023–2025 |
| School           | Institution              | 2008–2023 |

---

### 7. Contact

The Contact section provides links/details for:

* Email
* LinkedIn
* GitHub

GitHub:

```text
https://github.com/punithsai252-lang
```

---

## 🎨 Design Features

The website uses a modern and simple visual design.

### Background

A gradient background is applied to the main page:

```css
background: linear-gradient(to right, #e3f2fd, #f3e5f5);
```

### Navigation

The navigation bar uses a dark blue background:

```css
background: #0d47a1;
```

### Cards/Sections

Each content section is displayed inside a white card with:

* Rounded corners
* Padding
* Box shadow
* Centered layout

### Profile Image

The profile image is displayed as a circular image using:

```css
border-radius: 50%;
```

---

## 📱 Responsive Design

The website includes a CSS media query for smaller devices.

```css
@media(max-width:768px){
    section{
        width:95%;
    }
}
```

This allows the content sections to use more screen width on mobile and tablet devices.

---

## 🚀 How to Run the Project

### Step 1: Download or Clone the Project

Download the project files to your computer.

### Step 2: Open the Project Folder

Open the folder containing:

```text
index.html
```

### Step 3: Add Your Profile Image

Place your profile image in the same folder.

For example:

```text
profile.jpg
```

Then change:

```html
<img src="phot" alt="Profile Photo">
```

to:

```html
<img src="profile.jpg" alt="Profile Photo">
```

### Step 4: Open the Website

Double-click `index.html`.

The portfolio will open in your default web browser.

---

## 🔗 GitHub Deployment

The portfolio can also be hosted using **GitHub Pages**.

Basic process:

1. Create a GitHub repository.
2. Upload `index.html` and your image.
3. Go to repository **Settings**.
4. Select **Pages**.
5. Select the appropriate branch.
6. Save the settings.
7. GitHub will provide a public website URL.

---

## 🔮 Future Improvements

The portfolio can be enhanced by adding:

* [ ] Downloadable Resume
* [ ] GitHub project links
* [ ] LinkedIn profile link
* [ ] Project screenshots
* [ ] Project details pages
* [ ] JavaScript animations
* [ ] Dark mode
* [ ] Contact form
* [ ] Social media icons
* [ ] Skill progress bars
* [ ] Certifications section
* [ ] Achievements section
* [ ] Responsive mobile navigation
* [ ] Custom domain

---

## 👨‍💻 Author

**Gitta Punith Sai Madhav**

B.Tech — Artificial Intelligence & Data Science

Interests:

* Java Development
* Data Structures & Algorithms
* Artificial Intelligence
* Machine Learning
* Computer Vision
* Web Development

---

## 📄 License

This project is created for **personal portfolio and educational purposes**.

You are free to modify and customize the design according to your requirements.

---

⭐ **If you like this portfolio, consider giving the project a star on GitHub!**
