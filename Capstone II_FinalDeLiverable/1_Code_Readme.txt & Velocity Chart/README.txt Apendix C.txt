GoPhish Email and URL Threat Detection (Proof of Concept)

Project Description:
---------------------
This project is a proof of concept for a phishing detection system that scans URLs and email text for potential threats. It uses a simple web-based frontend and a Node.js backend proxy to securely communicate with VirusTotal and AbuseIPDB APIs.

Directory Structure:
---------------------

GoPhish-Detection/
├── public/
│   ├── index.html        # Main frontend UI with tab-based interface for URL and email scanning.
│   └── (optional styles) # You can add a CSS file here if styles are split out later.
│
├── server.js             # Node.js Express server (API proxy) that communicates with VirusTotal and AbuseIPDB.
├── package.json          # Node.js configuration file listing dependencies and scripts.
└── README.txt            # Documentation file describing structure and setup (this file).

How to Run:
------------
1. Make sure you have Node.js and npm installed.
2. Place all files in a project folder.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the backend server.
5. Open `http://localhost:3000` in your web browser to access the frontend.

Dependencies:
--------------
- express
- axios
- cors
- (APIs used: VirusTotal, AbuseIPDB)

Notes:
-------
- Ensure your API keys for VirusTotal and AbuseIPDB are inserted in `server.js`.
- This is a non-production demo — API keys should be secured using environment variables in real deployments.
- The server runs on port 3000 by default.

