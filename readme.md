📌 What is RideCompare?
RideCompare is a web app that helps you estimate and compare ride fares across Ola, Uber and Rapido for any route in India — before you even open those apps.
Just enter your pickup and drop location, select your ride type, and instantly see a fare breakdown for all three providers sorted from cheapest to most expensive.

✨ Features

🗺️ Real route distance — fetched live from OSRM routing engine
💸 Fare breakdown — shows base fare, distance charge and surge separately
🔍 Smart autocomplete — location search powered by OpenStreetMap Nominatim API
🕒 Search history — last 5 searches saved in your browser automatically
💬 Share on WhatsApp — send fare comparison to friends in one tap
📋 Copy to clipboard — copy results anywhere you need
🏍️ Three ride types — Bike, Auto and Cab
📱 Mobile friendly — works on all screen sizes


🛠️ Tech Stack
TechnologyPurposeHTML, CSS, JavaScriptFrontend — no frameworks usedOpenStreetMap Nominatim APILocation autocomplete and geocodingOSRM Routing APIReal driving distance and travel timelocalStorageSaving search history in browser

📸 Screenshots

(Add your screenshots here after deploying)


⚙️ How to Run Locally
No installation needed. No terminal needed.

Download or clone this repository
Open index.html in your browser

That's it. The app runs directly in the browser.

Note: For search history to work locally, open the file using VS Code Live Server extension instead of double-clicking. On GitHub Pages it works automatically.


🧮 How Fare Calculation Works
The app calculates fares using this formula:
Total = Base Fare + (Per km Rate × Distance) + Surge Charge
Example for Ola Bike on a 10km route:
Base Fare        →  ₹25
Distance Charge  →  ₹5 × 10km = ₹50
Surge Charge     →  ₹6  (random between 0–15%)
Total Estimate   →  ₹81
Each provider has different base fares and per-km rates built into the app.

⚠️ Disclaimer
Fares shown are estimates only. Actual prices on Ola, Uber and Rapido may vary based on:

Real-time surge pricing
Driver availability
Traffic conditions
App-specific promotions

Ola, Uber and Rapido do not provide public APIs for live fare data, so this app uses approximate rate cards for calculation.

📁 Project Structure
ridecompare/
│
└── index.html       # Entire app — HTML + CSS + JS in one file

🚀 Deployment
This app is deployed using GitHub Pages — completely free.
To deploy your own copy:

Fork this repository
Go to Settings → Pages
Select main branch as source
Your app will be live at https://YOURUSERNAME.github.io/ridecompare


👨‍💻 Author
Your Name

GitHub: @YOURUSERNAME
LinkedIn: Your LinkedIn


📄 License
This project is open source and available under the MIT License.