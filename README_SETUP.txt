I ESAKKI RAJ — PREMIUM EEE PORTFOLIO
====================================
This is the screenshot-inspired premium dark-blue/cyan portfolio layout.

FILES
- index.html: responsive portfolio website with hero workspace visual and two project-card illustrations.
- firestore.rules: owner-only Firestore write rules.
- README_SETUP.txt: this setup guide.

PRIVATE EDITING
The "Edit in Web" button is hidden from public visitors. Press Alt+Shift+E
to open the owner login panel. After Firebase confirms the verified owner
account, the "Edit in Web" button appears in the navigation bar:
greazyrider143@gmail.com.
Public visitors can read published portfolio text but cannot edit it.
The Firestore rules below are the actual security boundary; hiding a button
is not security by itself.

FIREBASE SETUP
1. Create a project at https://console.firebase.google.com/
2. Add a Web App in Project settings and copy its config into index.html,
   replacing PASTE_FIREBASE_API_KEY, PASTE_PROJECT_ID,
   PASTE_MESSAGING_SENDER_ID and PASTE_FIREBASE_APP_ID.
3. Authentication > Sign-in method > enable Email/Password.
4. Add greazyrider143@gmail.com as a Firebase Authentication user.
   Set a strong password and complete email verification.
5. Create a Firestore database.
6. In Firestore > Rules, paste firestore.rules and Publish.
7. Host index.html over HTTPS (GitHub Pages works). Add your hosting domain
   to Firebase Authentication > Settings > Authorized domains if required.
8. The resume download link expects I_Esakki_Raj_Professional_Resume.pdf
   in the same hosting folder. Upload your final resume PDF with that name.

RESUME FILE
- The ZIP includes I_Esakki_Raj_Professional_Resume.pdf beside index.html.

CURRENT EDITABLE FIELDS
- Hero introduction
- About paragraph
- Home automation project description
- Smart protection project description

The current text editor does not yet provide image upload, project add/delete,
or editing of all navigation/education sections. Those need a later admin
editor upgrade. The "Add Project" control is a placeholder, not an active
project-creation function.

PROJECT DIAGRAMS
The two card visuals are illustrative project graphics, not wiring diagrams.
Use safe isolation, correctly rated protection and qualified supervision for
any mains-voltage implementation.
