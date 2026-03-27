LBC Dispatch Reference Cards 📡

A mobile-first dispatch reference application built for Long Beach Disaster Prep and Emergency Communications (LBC) personnel. Provides fast, searchable access to dispatch cards covering call types, codes, geography, locations, and commands — optimized for real-time use during active dispatch calls.

🔗 Live App
https://chriskrs111.github.io/dispatch_cards

📱 Features

206 Dispatch Cards organized across 9 categories
Global Search — search across all cards instantly by keyword or code number
Swipe Navigation — swipe left/right to move between categories
Favorites — star any card for quick one-tap access
Dark Mode — optimized for low-light dispatch environments
Mobile Optimized — designed for iPhone use during live calls
Home Screen App — can be saved as a home screen shortcut via Safari


📂 Card Categories
CategoryDescription⭐ FavoritesYour bookmarked cards for instant accessRememberGeneral dispatch reminders and proceduresTC'sTraffic collision proceduresCivil MattersCivil dispute and custody proceduresCall TypesP1, P2, P3 and Emergency call proceduresDescriptionsSuspect, vehicle, gun and knife descriptionsCodes10 Codes and department codesCommandsDispatch system commands and shortcutsLocationsStations, hospitals, schools, parksGeographyStreet grid, beats, divisions, north/south/east/west reference

🛠️ Tech Stack

React (Create React App)
GitHub Pages for hosting
gh-pages package for deployment
No external dependencies — lightweight and fast


🚀 Deployment
Prerequisites

Node.js (LTS version)
Git

Initial Setup
bashgit clone https://github.com/chriskrs111/dispatch_cards.git
cd dispatch_cards
npm install
Deploy Updates
bashnpm run deploy
This builds the app and pushes to the gh-pages branch automatically. Allow 2–3 minutes for changes to go live.

📁 Project Structure
dispatch_cards/
├── public/
│   ├── index.html
│   └── logo.png          # LBC logo
├── src/
│   ├── App.js            # Main app — all cards and UI logic
│   └── index.js          # React entry point
├── package.json
└── README.md

✏️ Adding or Updating Cards
All cards are defined in the cards array at the top of src/App.js. Each card follows this format:
javascript{ 
  id: 999,              // Unique number
  cat: "Remember",      // Category name
  title: "Card Title",  // Displayed in collapsed view
  body: "Card content"  // Displayed when expanded
}
After editing, redeploy with:
bashnpm run deploy

📲 Adding to iPhone Home Screen

Open Safari on your iPhone
Navigate to the live app URL
Tap the Share button (box with arrow)
Tap "Add to Home Screen"
Name it Dispatch Ref and tap Add


📋 Print Template
A print-ready Avery 8873 template (2" x 3.5" business cards, 10 per sheet) is maintained alongside this app covering all 206 cards across 21 pages.

👤 Author
Christopher VanSon
This application was independently developed and built for use by Long Beach Disaster Prep and Emergency Communications. The author is not affiliated with or employed by the organization.

📄 License
This project is for internal department use only. Not for public distribution.
