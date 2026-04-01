# 🎓 Career Guidance Advisor

---

## 📌 Project Description

**Career Guidance Advisor** is an interactive, browser-based platform designed to help students in Andhra Pradesh discover the right engineering college and branch for their future. It collects student preferences such as location, budget, and career interests, and then recommends matching colleges from a curated database of 1800+ engineering institutions across AP. The platform also provides detailed branch overviews, career salary insights, and links to official college pages and exam resources.

---

## 🧩 Problem Statement

Every year, thousands of students in Andhra Pradesh appear for engineering entrance exams like AP EAMCET without a clear understanding of which branch suits their strengths or which college fits their budget and location. The lack of a centralized, easy-to-use guidance tool leads to poor decision-making, mismatched career paths, and financial stress. There is a strong need for an accessible platform that bridges this gap by offering personalized college and branch recommendations based on individual student profiles.

---

## ✨ Features of the Project

- **Student Profile Creation** — Collects name, email, age, education level, preferred location (university region), and annual budget to build a personalized profile.
- **Career Interest Selection** — Students can explore and select from 10+ engineering branches (CSE, ECE, EEE, MEC, CIV, CSM, AID, AIM, CHE, BIO), each displaying descriptions and average salary ranges.
- **Personalized College Recommendations** — Filters and displays colleges from the database that offer the student's chosen branches, showing college name, location, district, type, annual fee, and matching branch count.
- **Smart Filtering** — Supports dynamic search and filter by region (AU, SVU, JNTUK, JNTUA, JNTUV), college type (Private, University, Self-Finance, Private University), and fee range.
- **College Official Page Links** — Every college card includes a direct link to its official website.
- **Statistics Dashboard** — Shows total matching colleges, average fee, number of regions, and selected branches at a glance.
- **Branches Overview** — Detailed cards for each selected branch with career options and salary data.
- **Career Resources Section** — Curated links to AP EAMCET and other helpful exam/career resources.
- **Responsive Design** — Mobile-friendly layout that adapts to all screen sizes.
- **Smooth Animations** — Fade-in transitions and hover effects for an engaging user experience.

---

## 🛠️ Technologies Used

| Category | Technology |
|---|---|
| **Markup Language** | HTML5 |
| **Styling** | CSS3 (Flexbox, Grid, Animations, Media Queries) |
| **Programming Language** | JavaScript (Vanilla ES6+) |
| **UI Approach** | Single Page Application (SPA) with section toggling |
| **Data Storage** | In-memory JavaScript objects (no backend/database) |
| **Hosting** | Static file — can be served via any web server or GitHub Pages |
| **Version Control** | Git & GitHub |

> ⚠️ No external libraries or frameworks are used. This is a pure HTML/CSS/JS project.

---

## 📂 Project Structure

```
Career-guidance-advisor-/
│
└── indexx.html          # Single-file application containing all HTML, CSS, and JavaScript
```

> The entire project is self-contained within a single file (`indexx.html`), including:
> - Page structure and layout (HTML)
> - All visual styling (CSS — embedded in `<style>` tags)
> - Application logic, college data, and interactivity (JavaScript — embedded in `<script>` tags)

---

## ⚙️ Installation / Setup

No installation or server setup is required. Follow these steps:

**Step 1 — Clone the Repository**
```bash
git clone https://github.com/javvadi-ajay-kumar/Career-guidance-advisor-.git
```

**Step 2 — Navigate to the Project Folder**
```bash
cd Career-guidance-advisor-
```

**Step 3 — Open the Application**

Simply open `indexx.html` in any modern web browser:
```bash
# On Windows
start indexx.html

# On macOS
open indexx.html

# On Linux
xdg-open indexx.html
```

> ✅ No npm, no pip, no server required — just open and use!

---

## 🚀 Usage of the Project

1. **Sign Up** — Open the app and fill in your profile: name, email, age, education level, preferred AP region, and annual budget. Click **"Create Profile & Continue"**.

2. **Select Career Interests** — Browse the engineering branch cards. Click on branches that interest you (they highlight in purple when selected). Click **"Save Interests & View Colleges"**.

3. **View Recommended Colleges** — The platform displays colleges that offer your selected branches, along with fees and official website links. Use the **search bar** and **filters** (region, type, fee range) to narrow down results.

4. **Explore Branches** — Navigate to the **Branches** tab to view detailed descriptions, career options, and average salary ranges for your selected specializations.

5. **Access Resources** — Visit the **Resources** tab for links to AP EAMCET and other official exam and career guidance portals.

---

## 🖥️ Sample Output of the Project

**Profile Creation Screen**
> Student fills in personal details and budget preferences to create a personalized profile.

**Career Interest Selection**
> Cards for 10 engineering branches are displayed. Selected branches are highlighted in a purple gradient. Stats like average salary are shown per branch.

**College Recommendations**
> After selecting "Computer Science Engineering" and "Artificial Intelligence & Data Science", the platform displays colleges like:
> - **VITAP University** — Amaravathi | Fee: ₹1,03,000/yr | 13 Branches
> - **SRM University AP** — Amaravathi | Fee: ₹1,02,000/yr | 5 Branches
> - **Aditya Institute of Technology & Mgmt** — Tekkali | Fee: ₹79,600/yr | 9 Branches
>
> A statistics bar shows: **28 Matching Colleges | ₹76K Avg Fee | 5 Regions | 2 Selected Branches**

**Branches Overview**
> Each selected branch is shown as a card with its description, average salary (e.g., CSE: ₹4–12 LPA), and career roles (e.g., Software Engineer, Data Scientist, Web Developer).

---

## 🔮 Future Improvements

- **Backend Integration** — Add a server (Node.js / Python Flask) and database (MySQL / MongoDB) to persist user profiles and preferences across sessions.
- **Full College Database** — Expand the embedded dataset to cover all 1800+ AP engineering colleges with complete branch-level data.
- **EAMCET Rank-Based Filtering** — Allow students to input their EAMCET rank and receive cutoff-based college recommendations.
- **Comparison Tool** — Let students compare up to 3 colleges side-by-side on fees, branches, ratings, and placement stats.
- **User Authentication** — Add login/signup with Google OAuth or email OTP for secure profile management.
- **Placement Statistics** — Include average placement packages and top recruiters for each college.
- **Admin Panel** — Allow administrators to update college data, fees, and branch availability in real time.
- **Multi-Language Support** — Add Telugu language support to make the platform more accessible to local students.
- **PWA Support** — Convert the app into a Progressive Web App (PWA) so it can be installed on mobile devices and used offline.

---

## 👤 Author

| Field | Details |
|---|---|
| **Name** | *(Add your name here)* |
| **Role** | *(e.g., Full Stack Developer / Student / Project Lead)* |
| **LinkedIn** | *(Add your LinkedIn profile URL here)* |

---

> 💡 *Built with the goal of making engineering career decisions easier for students across Andhra Pradesh.*
