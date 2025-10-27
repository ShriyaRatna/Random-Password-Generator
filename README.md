# Random Password Generator

A lightweight password generator built using **HTML**, **CSS**, and **JavaScript**.

---

## Features
- Generates strong random passwords of fixed or customizable length  
- Supports uppercase, lowercase, numbers, and symbols  
- One-click **Copy to Clipboard**  
- Works directly in any modern browser  

---

## How It Works
The JavaScript file defines character sets for:
- Uppercase letters  
- Lowercase letters  
- Numbers  
- Symbols  

All sets are combined into one string. A loop randomly picks characters until the password reaches the target length (`length = 12` by default).  
Copy functionality uses the **Clipboard API** for seamless copying.

---

## Technologies Used
- **HTML** – Structure of the page  
- **CSS** – Styling and layout  
- **JavaScript** – Password generation logic  

---

## How to Use
1. Clone or download this repository  
   ```
   git clone https://github.com/yourusername/random-password-generator.git
   ```
2. Open index.html in your browser
3. Click Generate
4. Copy your password if needed
