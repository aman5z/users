🏢 Web-Based Active Directory Console & IT Tools Suite
A powerful, single-page application (SPA) that mimics a native Windows Active Directory environment directly in the browser. Built entirely with Vanilla HTML, CSS, and JavaScript, it connects to a Google Apps Script backend to serve as a fully functional IT administration portal.

It features user management, audit logging, an IT ticketing system, a token counter, Google Drive integration, and a massive suite of built-in IT utilities.

✨ Features
🛠️ Core Administration Modules
👥 User Management (Active Directory): Create, edit, and delete user objects. Manage roles, custom permissions, and reset passwords. Enable or disable accounts with a native-feeling property inspector.

📊 System Dashboard: Real-time overview of system stats, user roles, ticket statuses, and recent audit activity with CSS-based charting.

📋 Audit Log: Tracks all system actions (logins, user creations, permission changes, file uploads) with advanced filtering and CSV export capabilities.

🖴 Local Disk (D:) / Cloud Drive: Google Drive integration acting as a local file system. Supports file uploading, deleting, and visual storage capacity tracking.

🎫 IT Ticketing System: Create, assign, update, and close IT support tickets. Features SLA tracking, priority levels (High, Medium, Low), and status filtering.

🔢 Token Counter System: Manage digital queue tokens. Features increment, decrement, repeat, reset, and live display integration.

⬛ Terminal Shell: A built-in command prompt interface to execute backend commands directly from the UI.

🧰 The "IT Tools" Suite
A massive collection of client-side utilities built directly into the console, operating primarily within the browser for maximum privacy and speed:

File & Document Tools: PDF Manipulation (Merge, Split, Compress, Watermark, Rotate), Text Diff/Compare tool, and Google Drive Upload + instant QR Code generation.

Network & Sysadmin: Subnet Calculator, Ping/Latency Monitor (with live Canvas charting), IP/DNS/Hosting Lookups, and MAC Vendor Lookup.

Generators & Converters: Secure Password Generator, Base64 Encode/Decode, Hex/Decimal/Binary Converter, and custom QR Code & Barcode (Code128) generators.

System Diagnostics: In-depth System Info Viewer (CPU, RAM, GPU, Battery, Local/Public IP, Screen DPR).

Quick Links Hub: A categorized directory for external proxies, AI tools, software archives, and browser emulators.

💻 Tech Stack
Frontend: Vanilla HTML5, CSS3, JavaScript (ES6+). No heavy frameworks (React/Vue) used, ensuring a lightning-fast load time in a single file structure.

Backend: Google Apps Script (GAS) acting as a serverless REST API to handle user authentication, database operations, and file storage.

Theming: Fully responsive design with native CSS Variables supporting seamless Light and Dark modes.

Libraries Used:

pdf-lib (Client-side PDF manipulation)

JsBarcode (Barcode generation)

QRCode.js (QR Code generation)

🚀 Installation & Usage
Because the frontend is a standalone HTML file, setup is incredibly simple:

Clone the repository:

Bash
git clone https://github.com/yourusername/active-directory-console.git
Open the index.html file directly in any modern web browser.

(Optional) To host it live, you can deploy it directly via GitHub Pages, Vercel, or Netlify with zero build steps required.

Note: The application expects a Google Apps Script backend URL to authenticate users and fetch data. You will need to configure the API constant at the top of the <script> tag to point to your own deployment if you are forking this project.

⌨️ Global Keyboard Shortcuts
Ctrl + K: Focus Search Bar

Ctrl + E: Export all current IT Tool outputs to a text file

Ctrl + D: Toggle Light/Dark Theme

Escape: Clear search focus

📜 License
Created by aman5z.in. All rights reserved.
