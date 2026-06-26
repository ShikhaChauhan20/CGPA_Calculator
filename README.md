# 🎓 Grademeter - Smart CGPA/SGPA Calculator

Grademeter is a premium, fully responsive web utility application designed for university students to flawlessly compute their semester SGPA and track their aggregate Cumulative GPA (CGPA) over time. Calibrated specifically against standard 10-point academic grading matrices.

🌐 **[Live Demo: Calculate Your Grades Instantly!](https://shikhachauhan20.github.io/CGPA_Calculator/)**

---

## ✨ Key Features

- **Dual Computation Modes:** Toggle seamlessly between **Semester SGPA** (subject-by-subject) and **Overall CGPA** (semester-by-semester) calculation dashboards using clean navigation tabs.
- **Calibrated Grading Engine:** Programmed to accept absolute letter grades (`A+`, `A`, `B+`, etc.) and automatically translate them into correct university grade-point numeric equivalents.
- **Dynamic Row Management:** Add or delete subjects and semesters instantly with automated re-indexing of labels.
- **State Persistence (Auto-Save):** Powered by browser `LocalStorage` configurations. Your grade entries, course names, and tab choices are securely cached locally, meaning your data won't wipe when you refresh the page or close the tab.
- **Modern Responsive Design:** Built using **Tailwind CSS** and customized vector vector icon sets from **FontAwesome** to deliver a sleek user experience across smartphone viewports, tablets, and desktop displays.

---

## 🛠️ Tech Stack Architecture

- **Frontend Core:** HTML5 (Semantic Layout)
- **Styling Architecture:** Tailwind CSS (Utility-First Web UI framework Engine)
- **Computational Logic & Engine:** Vanilla JavaScript (ES6 Modules & Client-Side Array Operations)
- **Data Retention Layer:** Browser Web Storage API (`LocalStorage`)
- **Deployment Platform:** GitHub Actions & GitHub Pages Cloud Servers

---

## 📐 The Mathematical Formulation

The computational engines track academic criteria through the following standard formulas:

### 1. Semester SGPA
Calculated by dividing the total credit points earned by the total credits registered:
$$SGPA = \frac{\sum (\text{Grade Points} \times \text{Course Credits})}{\sum \text{Total Course Credits}}$$

### 2. Cumulative CGPA
Calculated by weighting individual semester averages against their respective total credit distributions:
$$CGPA = \frac{\sum (\text{SGPA} \times \text{Total Semester Credits})}{\sum \text{Total Cumulative Credits}}$$

---

## 🚀 How to Run Locally

Since this is a fully client-side application, there are no complicated installation steps or server environments required:

1. Clone or download this repository.
2. Double-click the `index.html` file to open it instantly inside any modern browser (Chrome, Edge, Safari, Firefox).
3. Start tracking your academic milestones!
