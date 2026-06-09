# CI-Notes System Prototype
 
Welcome to the CI-Notes System prototype! This single-file web application serves as an interactive mockup constructed directly from the provided architectural Use Case Specifications.
It blends HTML5, CSS3, and vanilla JavaScript into a clean, modern user experience designed for IIUM Students to manage their notes, academic deadlines, and tasks.

<h2>Feature Mapping Blueprint</h2><br>
The source code explicitly translates the functional rules of your system into interactive features:

1. Central Authenticator Service (CAS) Portal
  Implementation: The application boots into a secure, full-screen lock overlay. Users cannot see or interact with the dashboard until they click "Login using IIUM CAS". This mocks the system redirecting to the CAS server, validating user authorization rules, and granting entry to the primary workspace.

2. Notes Management System
   Implementation: Located under the 📝 Notes navigation panel. It features a responsive layout card grid where users can launch an input form modal, enter note content details, save items dynamically to an active memory array, or purge outdated notes instantly using the built-in deletion engine.

3. Kanban Task Board (Drag & Drop)
   Implementation: Located under the 📋 Kanban Task Board navigation panel. This implements the 3-column architecture tracking system (To Do, In Progress, and Done). Users can add task cards using standard parameters (Title, Subject) and freely use interactive native drag-and-drop workflows to advance tasks through completion statuses.

4. Push Notification Engine
   Implementation: Simulates an automatic trigger mechanism where the system checks its database against looming academic deadlines. An alert banner drops down at the top of the viewport to capture attention instantly. Clicking the navigation header bell toggle displays or dismisses alerts while adjusting live notification badges.

5. Universal System Search
   Implementation: Built right into the top header workspace. Typetasting keywords into the search prompt triggers a global real-time filter algorithm. The page instantly parses all note data strings and active Kanban tasks on screen, hiding non-matching elements and showing relevant data dynamically without page reloads.

   



<h2>🚀 How to Run the Prototype?</h2><br>
Because this prototype is entirely self-contained, it requires zero installations, terminal commands, or server environments.


1. Save the Code: Copy the generated HTML code block and save it on your machine as index.html or app.html.<br>
2. Open the File: Double-click the saved file or drag and drop it into any modern web browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge, or Apple Safari).<br>
3. Interact: Step through the login path to enter the workspace, then feel free to draft notes, schedule tasks, drag them across columns, or test the live search functionality.<br>

or just click this link: https://kyleiqmalz.github.io/sad-finalz/


<h2>🎨 Tech Stack & Architecture</h2><br>
1. Markup: Clean, semantic semantic HTML5 structures (<sidebar>, <main>, <header>).<br>
2. Styling: Vanilla CSS3 utilizing CSS Grid layouts for structural components, Flexbox for internal content alignments, and custom state pseudo-classes (.open, .active) for transitions.<br>
3. Interactivity: Vanilla JavaScript (ES6+) handling custom application states, DOM manipulation, standard web drag-and-drop registration handling APIs, and runtime regex searching patterns.<br>
