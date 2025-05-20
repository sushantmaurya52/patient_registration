# patient_registration

# Clone the repository
git clone https://github.com/sushantmaurya52/patient_registration.git

# Go to the directory
cd patient_registration

# Open the App locally
This project is 100% frontend and runs entirely in the browser using PGlite, a WebAssembly-based PostgreSQL engine.

You have two Options
    1.Open index.html directly
    2.Serve with a Local HTTP Server

1. Open index.html directly
Double-click the index.html file to open it in your browser.

    Note : Some browsers (like Chrome) may block certain functionality when opening from file://.If Face issue use Option B below.

2. Serve with a Local HTTP Server

Using Python (recommended)
On the same directory open terminal and write below command to start local server

    python3 -m http.server

# You will see something like below
    Serving HTTP on :: port 8000 (http://[::]:8000/) ...

# Once you see above thing in terminal then open below address on browser

    http://localhost:8000




# Usage
    1. Enter patient details (Name, Age, Gender,MobileNo , Address).
    2. Click Register to insert into the local browser-based database.
    3. Use the query box to run custom SQL queries (e.g., SELECT * FROM patients;).
    4. Data persists in the browser (IndexedDB) and syncs across tabs.
