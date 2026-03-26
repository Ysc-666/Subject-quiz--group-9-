# Subject-quiz--group-9-
Using html,CSS and JavaScript to do the project about Subject quiz.

## ✨ Features
- Create and manage custom subjects
- Add different types of questions (multiple choice / true-false)
- Take quizzes and view instant results
- Review wrong answers
- Manage subjects and questions easily
- Clean, stable, and modular page structure

## 📁 Project Structure
The project is fully modularized and divided into 6 core pages:
1. Quiz Home Page – select subject to start
2. Create Subject Page – add new subjects
3. Add Question Page – insert questions into subjects
4. Quiz Page – answer questions
5. Result Page – view score & review mistakes
6. Management Page – delete subjects or questions

## 🚀 How to Run
1. Download or clone this repository
2. Open `index.html` with any browser (Chrome / Edge / Firefox)
3. No installation required – the app runs directly in the browser

## 🧩 Modules
### Module 1 – Basic Template & Page Architecture
- Builds the entire UI framework
- Provides 6 independent pages
- Implements page switching using `switchPage()`
- Defines global CSS styles and layout
- Supports modular collaboration with other components

## 📚 Technical Stack
- HTML5 (page structure)
- CSS3 (styling & layout)
- Vanilla JavaScript (interactive logic)
- Local Storage (data persistence)

## 📌 Page Switching Core Logic
All pages are controlled by CSS classes:
- `.page { display: none; }` (hidden by default)
- `.page.active { display: block; }` (show current page)

The `switchPage()` function controls navigation between pages.

## 👥 Group Project Contribution
- **Module 1 (Page Architect)**: Responsible for the entire front-end framework, page structure, navigation, and global style design.

## 📝 Notes
- All data is stored locally in your browser
- Refresh or close the browser will NOT lose saved subjects and questions
- The template supports independent running and smooth module integration
