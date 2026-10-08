# 💙 Teacher's Day Letter — Sir Randy Bello

A beautiful, interactive **Teacher's Day digital letter** created for **Sir Randy Bello**, a Web Development instructor.

The project combines **HTML, CSS, and JavaScript in a single HTML file**, making it easy to run and share without installing any libraries or dependencies.

---

## 🌸 Preview

The website features a light-blue Teacher's Day design with:

* 💌 Interactive envelope
* 🌷 Flowers and decorative elements
* 🎈 Floating balloons
* 💙 Light-blue color theme
* 🌙 Dark mode / ☀️ Light mode
* ✨ Smooth animations and transitions
* 💖 Floating hearts when the letter opens
* 📱 Responsive mobile design
* ⌨️ Keyboard interaction
* 💻 No external libraries required

---

## 📁 Project Structure

The project can be kept extremely simple:

```text
teachers-day-letter/
│
├── index.html
└── README.md
```

### `index.html`

Contains everything required for the website:

* HTML structure
* CSS styling
* Animations
* JavaScript functionality
* Teacher's Day message

The page title is set to **"Happy Teacher's Day, Sir Randy Bello 💙"**.

---

## 🚀 How to Run

### 1. Download or copy the HTML file

Save the webpage as:

```text
index.html
```

### 2. Open the file

Double-click `index.html`.

It will open directly in your web browser.

No server or installation is required.

### 3. Enjoy the letter 💙

Click:

```text
💌 Open Your Letter
```

to open the envelope and reveal the message.

---

## 💌 Letter Animation

The project uses a CSS 3D animation to open the envelope.

When the envelope receives the `open` class, the flap rotates and the letter becomes visible.

The opening interaction is controlled by JavaScript through the `toggleLetter()` function.

The button changes between:

```text
💌 Open Your Letter
```

and:

```text
💙 Close Letter
```

---

## 🌙 Dark Mode

The website includes a light/dark theme switch.

Click the button in the upper-right corner:

```text
🌙
```

to activate dark mode.

It changes the interface to a darker blue theme and switches the button to:

```text
☀️
```

The dark theme is implemented using CSS variables and the `.dark` class.

JavaScript controls the theme switch.

---

## 🎈 Decorations

The website includes animated:

### Balloons

Three balloons are included:

* 💙 Blue
* 💗 Pink
* 💛 Yellow

They gently move up and down using CSS keyframe animation.

### Flowers

Decorative flowers include:

* 🌸 Cherry blossom
* 🌷 Tulip
* 🌼 Flower
* 🌺 Hibiscus

They have a gentle floating and rotating animation.

---

## ✨ Floating Effects

When the letter opens, floating hearts and other decorative emojis appear on the screen.

The JavaScript dynamically creates these elements and removes them after their animation finishes.

The page also continuously generates floating flowers for an additional animated effect.

---

## 📱 Responsive Design

The website is designed to work on:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile phone
* 📲 Tablet

A CSS media query adjusts the envelope, letter padding, text size, balloons, and flowers for smaller screens.

---

## ⌨️ Keyboard Controls

The project includes a small keyboard accessibility feature.

### Enter

When the **Open Your Letter** button is focused, pressing:

```text
Enter
```

opens or closes the letter.

### D

Press:

```text
D
```

to toggle between dark and light mode.

---

## 🛠️ Technologies Used

### HTML5

Used to create the structure and content of the Teacher's Day letter.

### CSS3

Used for:

* Layout
* Colors
* Gradients
* Responsive design
* Transitions
* Animations
* 3D envelope opening
* Dark mode

### JavaScript

Used for:

* Opening and closing the envelope
* Dark/light mode
* Floating hearts
* Floating flowers
* Keyboard controls

---

## 🎨 Color Theme

The primary design uses a soft light-blue palette.

Some of the main colors include:

```css
--bg: #eaf7ff;
--bg-secondary: #d8f0ff;
--heading: #1976a8;
--accent: #5bbce9;
--accent-dark: #278bbd;
```

These colors create the soft blue Teacher's Day aesthetic used throughout the page.

---

## ✏️ Personalizing the Letter

To change the recipient's name, look for:

```html
<div class="teacher-name">
    To Sir Randy Bello 🌷
</div>
```

You can replace the name with another teacher's name.

You can also edit the main letter inside:

```html
<article class="letter">
```

For example:

```html
<div class="signature">
    With gratitude and respect,<br>
    Your Student 💙
</div>
```

Replace **Your Student** with your name, section, or class.

---

## 📦 Dependencies

There are **no external dependencies**.

You do not need:

* npm
* Node.js
* Bootstrap
* jQuery
* React
* Tailwind CSS
* External JavaScript libraries

Everything is contained inside the HTML document.

---

## 🌐 Browser Compatibility

The project is intended for modern browsers such as:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

For the best visual experience, use an up-to-date browser.

---

## ❤️ Purpose

This project was created as a digital Teacher's Day greeting to express appreciation for:

**Sir Randy Bello**

and his effort, patience, guidance, and dedication as a Web Development instructor.

The letter specifically recognizes the lessons involving:

**HTML + CSS + JavaScript**

as well as creativity, problem-solving, patience, and continuous learning.

---

## 👨‍💻 Author

Created with:

**HTML • CSS • JavaScript • 💙 Appreciation**

Made especially for **Sir Randy Bello**.

---

## 📜 License

This project is intended for **personal, educational, and school-project use**.

Feel free to modify the message, colors, animations, and design to make it your own.

---

### 💙 Happy Teacher's Day, Sir Randy Bello!

> "Made with gratitude, appreciation, and a little bit of code." 💻💙
