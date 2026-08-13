# Classic Resume --- Punith Sai Madhav G

A clean, responsive, classic-style personal resume website built using
**HTML and CSS**, with a **Download Resume** button that generates an A4
PDF.

## 📌 Project Overview

This project is a personal resume webpage for **Punith Sai Madhav G**, a
B.Tech student specializing in **Artificial Intelligence & Data
Science**.

The resume uses a traditional professional design with:

-   Navy blue and antique-gold colors
-   Ivory/cream background
-   Classic typography
-   Clean section dividers
-   Responsive layout
-   Education cards
-   Technical skills
-   Projects
-   Strengths
-   Career objective
-   Personal details
-   Declaration
-   PDF resume download functionality

## ✨ Features

### 1. Classic Resume Design

The resume uses a professional classic color palette:

-   **Navy Blue** --- headings and borders
-   **Antique Gold** --- decorative accents
-   **Cream/Ivory** --- background and paper effect
-   **Dark Gray** --- supporting text

### 2. Personal Details

The resume contains:

-   Full Name
-   Date of Birth
-   Place of Birth
-   Address
-   Phone Number
-   Email Address

### 3. Education

The education section includes:

#### B.Tech --- Artificial Intelligence & Data Science

-   Institution: KL University
-   Duration: 2025 -- 2029
-   CGPA: 9.0

#### Intermediate

-   Institution: Resonance Junior College
-   Duration: 2023 -- 2025
-   Score: 961

#### School Education

-   Secondary Education
-   Duration: 2008 -- 2023
-   Percentage: 75%

### 4. Technical Skills

The resume includes:

-   HTML & CSS
-   Java
-   Python
-   JavaScript
-   React
-   SQL
-   Git & GitHub
-   Data Structures & Algorithms

### 5. Projects

The project section contains:

-   Personal Portfolio Website
-   Web Development Projects

### 6. Strengths

The resume highlights:

-   Quick Learner
-   Problem Solving
-   Teamwork
-   Time Management
-   Adaptability
-   Self-Motivated

### 7. Responsive Design

The resume is designed to work on:

-   Desktop
-   Laptop
-   Tablet
-   Mobile

The layout automatically adjusts for smaller screens.

### 8. Download Resume as PDF

The **Download Resume** button generates the resume as a PDF using the
`html2pdf.js` library.

The downloaded file is saved as:

`Punith_Sai_Madhav_G_Resume.pdf`

The PDF is configured for:

-   A4 paper
-   Portrait orientation
-   High-quality rendering

## 🛠️ Technologies Used

  Technology    Purpose
  ------------- -----------------------------------
  HTML5         Resume structure
  CSS3          Styling and responsive design
  JavaScript    PDF download functionality
  html2pdf.js   Converts the HTML resume into PDF

## 📁 Project Structure

``` text
classic-resume/
│
├── resume.html
└── README.md
```

## 🚀 How to Run

### Step 1 --- Download or Clone the Project

Place the HTML file in a folder.

### Step 2 --- Open the Resume

Open:

``` text
resume.html
```

in any modern web browser.

Recommended browsers:

-   Google Chrome
-   Microsoft Edge
-   Mozilla Firefox
-   Safari

### Step 3 --- Download the Resume

Click the:

``` text
Download Resume
```

button.

The browser will generate and download the resume as a PDF.

## 🖨️ Print / PDF Support

The resume also includes print-friendly CSS.

You can use the browser's:

``` text
Print → Save as PDF
```

option if required.

The print layout is optimized for **A4 paper**.

## 🎨 Customization

You can easily modify the resume by editing the HTML file.

### Change Name

Find:

``` html
<h1>Punith Sai Madhav G</h1>
```

and replace the name.

### Change Contact Information

Update:

``` html
+91 8179944028
punithsai252@gmail.com
8-2-269/19/398/A
```

### Change Education

Update the content inside the:

``` html
<section class="section">
```

Education section.

### Change Skills

Add or remove skills from:

``` html
<ul class="skills">
```

### Change Projects

Edit the project information inside:

``` html
<div class="project">
```

### Change Colors

The main colors are defined at the beginning of the CSS:

``` css
:root {
    --navy: #1f2f46;
    --gold: #b08a4a;
    --dark-gold: #8f6c32;
    --cream: #f5f0e6;
    --paper: #fffdf8;
}
```

You can change these values to create your own color theme.

## 📄 PDF Download Function

The project uses `html2pdf.js` to convert the resume container into a
PDF.

The library is loaded using:

``` html
<script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>
```

The JavaScript function creates an A4 portrait PDF and downloads it with
the filename:

``` text
Punith_Sai_Madhav_G_Resume.pdf
```

## 🌐 Internet Requirement

The webpage itself does not require a server and can be opened directly.

However, the PDF download feature loads `html2pdf.js` from a CDN, so an
internet connection is recommended when using the download feature.

## 📱 Browser Compatibility

The resume is designed for modern browsers that support:

-   HTML5
-   CSS3
-   JavaScript
-   CSS Grid
-   CSS Flexbox

## 🔒 Privacy

The resume contains personal information such as contact details.

If you publish this project on a public GitHub repository or website,
consider whether you want your phone number and email address to be
publicly visible.

## 👨‍💻 Author

**Punith Sai Madhav G**

B.Tech --- Artificial Intelligence & Data Science

KL University

## 📜 License

This project is intended for personal resume and portfolio use.

You may modify the design, content, colors, skills, projects, and other
sections for your own use.

------------------------------------------------------------------------

## ⭐ Final Notes

This project combines a classic resume appearance with modern web
functionality. It is suitable for:

-   College applications
-   Internship applications
-   Job applications
-   Portfolio websites
-   Personal websites
-   Resume PDF generation
