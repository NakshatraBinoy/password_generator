Password-generator
PASSFORGE — Password Generator
A sleek, dark-themed password generator built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no build step — just open and use.

Features
Adjustable length — slide from 6 to 64 characters
Character set toggles — mix and match Uppercase, Lowercase, Numbers, and Symbols
No Ambiguous Characters — removes visually confusing chars like I, l, 1, O, 0
Memorable mode — generates hyphen-separated word combinations instead of random strings
Strength meter — 5-bar visual indicator rating from Weak to Elite
Copy to clipboard — one-click copy with toast confirmation
Password history — shows the last 3 generated passwords, clickable to restore
Cryptographically secure — uses crypto.getRandomValues() (not Math.random())
Usage
Open password-generator.html in any modern browser
Adjust the length slider and toggle your preferred character sets
Click GENERATE
Click COPY to copy to clipboard
No installation, no server, no internet connection required.

Options
Toggle	Description
Uppercase	A–Z
Lowercase	a–z
Numbers	0–9
Symbols	`!@#$%^&*()_+-=[]{}
No Ambig.	Excludes I, l, 1, O, 0, o
Memorable	Word-based passwords (e.g. solar-frost-blaze)
At least one of Uppercase, Lowercase, Numbers, or Symbols must remain active.

Security Notes
All generation happens client-side in the browser — no data is sent anywhere
Uses the Web Crypto API (crypto.getRandomValues) for true randomness, not Math.random()
Passwords are not stored — history only lives in memory for the current session
Browser Support
Works in all modern browsers (Chrome, Firefox, Safari, Edge). Requires support for the Web Crypto API (available in all browsers since 2017).

File Structure
password-generator.html   ← single self-contained file (HTML + CSS + JS)
README.md
License
MIT — free to use, modify, and distribute.
