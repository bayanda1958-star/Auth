# SecurePortal Authentication Interface
Hey! 👋 This is a lightweight, frontend-only authentication page built with HTML, CSS, and vanilla JavaScript. It's designed to give a modern, polished login and registration experience right in the browser without needing a backend server immediately.
## ✨ What's Inside?
 * **Sleek UI / UX**: Built with a dark mode aesthetic, smooth CSS transitions, glowing gradient accents, and a frosted-glass card effect (backdrop-filter).
 * **Client-Side Storage**: Uses localStorage to save user accounts and manage active browser sessions so users stay logged in (or can sign out cleanly).
 * **Multi-View State Machine**: Handles multiple views dynamically (#authView, #welcomeScreen, and #dashboardView) without ever reloading the page.
 * **Form Validation**: Quick checks for email formats, matching passwords (minimum 6 characters), and existing email collisions on registration.

## 🚀 How to Run It
 1. Save the HTML code into a file, for example: index.html.
 2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
 3. Switch between **Sign In** and **Register** tabs to create a dummy account and test the session flow!
## 🛠️ Tech Stack
 * **HTML5**
 * **CSS3** (with custom variables, keyframe animations, and radial gradients)
 * **Vanilla JavaScript** (ES6+)
 * **Google Fonts** (Plus Jakarta Sans)


```text
secure-auth-portal/
│
├── index.html       # Complete single-file app (Markup, Styles, and Logic)
└── README.md        # Project documentation
