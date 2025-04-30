# Full-Stack QA Transition Course  
_A 6-weekend crash course for manual/automation testers with no coding experience_

---

## 📅 Weekly Breakdown

### **Weekend 1: HTML/CSS & Static UI Layout**  
**Theme:** Structure and style a QA-centric UI

#### Saturday (Learning + Mini-Project)
- **Topics:**
  - HTML tags, tables, forms, semantic elements
  - CSS basics: Flexbox, Grid, responsive design
- **Hands-On Exercise:**
  - Build a static defect log table with columns: ID, Severity, Status, Assigned To, Description
  - Create a form to submit new defects (no functionality yet)
  - Color-code severity levels (Red/Yellow/Green)

#### Sunday (Practice + Extensions)
- **Topics:**
  - Advanced CSS: Transitions, hover effects, mobile responsiveness
  - Git basics: Repository setup, commits
- **Exercises:**
  - Add filters to show Open/Closed bugs
  - Clone repo locally and push updates to GitHub

---

### **Weekend 2: JavaScript & DOM Manipulation**  
**Theme:** Interactive QA Elements

#### Saturday (Learning + Mini-Project)
- **Topics:**
  - Variables, functions, DOM traversal
  - Event handling (click, input), LocalStorage API
- **Hands-On Exercise:**
  - Add/Delete defects (client-side only)
  - Mark defects as Resolved (toggle status)
  - Save defects to LocalStorage

#### Sunday (Practice + Extensions)
- **Topics:**
  - Error handling (try/catch), form validation
  - Debugging basics (browser DevTools)
- **Exercises:**
  - Validate defect form inputs (required fields, date formatting)
  - Sort defects by priority (drag-and-drop reordering)

---

### **Weekend 3: Introduction to React.js**  
**Theme:** Component-Based UI Development

#### Saturday (Learning + Mini-Project)
- **Topics:**
  - React setup (Create React App)
  - Components, JSX, state (useState), props
- **Hands-On Exercise:**
  - Convert static defect table to React
  - DefectList component rendering defects from state
  - Form component for adding defects (controlled inputs)

#### Sunday (Practice + Extensions)
- **Topics:**
  - Conditional rendering, useEffect hook
  - Styling in React (CSS Modules, Tailwind CSS)
- **Exercises:**
  - Implement search/filter bar for defects
  - Persist state to LocalStorage using useEffect

---

### **Weekend 4: Backend Development with Node.js/Express**  
**Theme:** REST APIs for Defect CRUD Operations

#### Saturday (Learning + Mini-Project)
- **Topics:**
  - Node.js/Express setup, routing, middleware (JSON parsing)
  - REST principles: GET/POST/PUT/DELETE endpoints
- **Hands-On Exercise:**
  - Build a `/defects` API:
    - GET all defects
    - POST new defect data
  - Test with Postman

#### Sunday (Practice + Extensions)
- **Topics:**
  - Error handling, MongoDB vs SQL comparison
  - HTTP clients (Axios/fetch in React)
- **Exercises:**
  - Connect React frontend to backend APIs
  - Add edit/delete functionality via PUT/DELETE

---

### **Weekend 5: MySQL Database Integration**  
**Theme:** Relational Data Models for QA Assets

#### Saturday (Learning + Mini-Project)
- **Topics:**
  - MySQL schema design (tables, relationships)
  - Query execution (SELECT, INSERT, UPDATE, DELETE)
  - ORM: Sequelize for model creation
- **Hands-On Exercise:**
  - Design `Defects` and `TestCases` tables
  - Link backend APIs to MySQL queries
  - Seed database with sample test cases

#### Sunday (Practice + Extensions)
- **Topics:**
  - Associations (one-to-many between TestCases → Defects)
  - Authentication basics: Mock user roles (Admin/QA User)
- **Exercises:**
  - Allow users to link defects to test cases
  - Add role-based access control (RBAC) to API routes

---

### **Weekend 6: Deployment & Final Touches**  
**Theme:** End-to-End Hosting and Delivery

#### Saturday (Learning + Mini-Project)
- **Topics:**
  - Deployment options (Heroku, Vercel, AWS)
  - CI/CD pipelines, environment variables, domain setup
- **Hands-On Exercise:**
  - Deploy frontend (Vercel/Netlify) and backend (Render/Railway)
  - Configure production database (MySQL on AWS RDS or Planetscale)

#### Sunday (Practice + Extensions)
- **Topics:**
  - SSL certificates, logging, monitoring
  - Security best practices (input sanitization, rate limiting)
- **Exercises:**
  - Test deployment workflows (GitHub Actions CI/CD)
  - Document user manuals and API guides

---

## 🎯 Final Project: Defect Dashboard Features

### ✅ Core Functionality:
- Create, Read, Update, Delete defects/test cases
- Filter defects by status, severity, assignee
- Real-time updates via React state/backend sync

### 📊 Advanced Features:
- Metrics dashboard (open vs resolved bugs)
- User roles (Admin, QA Lead, Tester)
- Export defect reports to CSV

### 🔐 Security:
- Input validation, sanitized SQL queries

---

## 💡 QA-to-Dev Transition Tips

- **Leverage Your Testing Superpowers:** Think about edge cases when designing UI/API flows.
- **Write Tests:** Unit and integration tests using Jest/Mocha.
- **Automate What You Know:** Use Selenium/Playwright to test the dashboard.
- **Think Like a User Advocate:** Apply usability testing practices.
- **Collaborate Across Teams:** Incorporate stakeholder feedback loops.
- **Document Everything:** Maintain API docs and test plans as living documentation.

---

## 🏁 Course Outcome

Graduates will ship a **full-stack QA tool** and gain confidence to
