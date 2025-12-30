# **GlowNotes**
GlowNotes is a modern, interactive note-taking prototype built with HTML5, CSS3, and JavaScript. Users can create accounts, log in, and manage personal notes in a clean, responsive interface. This project demonstrates front-end user authentication flow and dynamic content management using localStorage.

### **Features**
- **Landing Page**: A welcoming landing page with call-to-action buttons that guide users to signup or login.
- **Signup & Login System**: Users can create an account and log in with email and password. Credentials are stored in the browser via `localStorage`.

- **Dashboard**: After login, users are redirected to their dashboard where they can add, view, and persist notes.

- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop.

- **Animated UI**: Gradient backgrounds and particle animations enhance the visual experience.

- **Client-Side Validation**: Password confirmation during signup and email/password validation during login.

- **Persistent Notes**: Notes are stored in `localStorage` and remain available across sessions until logout or browser clear.


### **Technologies Used**
- **HTML5**: Page structure and semantic elements.

- **CSS3**: Styling, responsive layout, animations, and transitions.

- **JavaScript**: Form validation, dynamic note creation, localStorage handling, and page navigation logic.

### **Demo**
Live Demo - [Login]()<!-- Add a link to the live version of the project if available -->


### **Project Structure**
GlowNotes/
│
├── index.html           # Landing page with CTA buttons
├── signup.html          # Signup page with validation and account creation
├── login.html           # Login page with authentication check
├── dashboard.html       # User dashboard for viewing and adding notes
├── styles.css           # Shared styles for all pages (animations, layout, colors)
└── README.md            # Project documentation


### **How to Use**
1. Clone the repository:

```
git clone https://github.com/stephenombuya/GlowNotes
```

2. Navigate to the project directory:

```
cd GlowNotes
```

3. Open the index.html file in a web browser to view the login form:

```
open index.html
```

4. On the landing page, click Get Started or + Add Note:

 - New users are redirected to signup.

 - After signup, they proceed to login.

 - Once logged in, they access `dashboard.html` to add and view notes.


### **Customization**
- **Forms**: Modify signup and login forms to integrate with a backend if needed.

- **Dashboard**: Adjust styles or add new note features.

- **Styling**: Update `styles.css` to change colors, animations, or typography.

- **Validation**: Extend JavaScript for stronger client-side validation.


### **Folder Structure**

```
Login-Page/
│
├── index.html        # HTML structure for the login form
├── styles.css        # Styles for the login form layout
└── README.md         # Project documentation
```

### **Future Enhancements**
- **Backend Integration**: Connect to Node.js, PHP, or Python backend for real authentication and database storage.

- **Editable/Deletable Notes**: Allow users to update or remove existing notes.

- **Remember Me**: Keep users logged in across browser sessions.

- **Password Recovery**: Add “Forgot Password” functionality.

- **User Management**: Support multiple users with separate note storage.


### **Contributing**
Contributions are welcome! If you have ideas or suggestions to improve the project, feel free to fork the repository and submit a pull request.

### **License**
This project is licensed under the GNU GENERAL PUBLIC LICENSE. See the [LICENSE](https://github.com/stephenombuya/loginForm/blob/main/LICENSE) file for more details.

