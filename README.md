DevDetective

A simple and responsive web app that fetches GitHub user profile data using the GitHub REST API.  
It displays details like avatar, bio, repositories, followers, location, and more, along with a dark/light mode toggle.

---

Features

- Search for any GitHub username
- View public repos, followers, and following count
- Display user location, blog, Twitter handle, and company
- Light/Dark mode with preference saved in localStorage
- Error handling for invalid usernames
- Fully responsive design

---

Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- GitHub REST API

---

Project Structure

DevDetective/
│
├── assets/
│   ├── images/           # Icons and graphics
│   ├── favicon-32x32.png
│   ├── favicon-16x16.png
│   └── site.webmanifest
│
├── styles.css            # Main stylesheet
├── script.js             # App logic
├── index.html            # Main HTML file
└── README.md             # Project documentation

---

Getting Started

1. Clone the Repository
   git clone https://github.com/yourusername/devdetective.git
   cd devdetective

2. Open in Browser  
   Simply open index.html in your preferred browser.

---

Usage

1. Enter a GitHub username in the search bar.
2. Press Enter or click Search.
3. The profile information will appear.
4. Toggle between Dark and Light mode using the button in the header.

---

Notes

- This app uses the public GitHub API and does not require authentication.
- If you make too many requests in a short time, GitHub may temporarily limit your access (rate limiting).

