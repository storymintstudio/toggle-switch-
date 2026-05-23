Toggle Switch On/Off Using CSS

A simple and customizable Toggle Switch built using HTML and CSS.
This project demonstrates how to create a modern ON/OFF switch without using JavaScript.

📌 Features
Pure HTML & CSS
Smooth toggle animation
Responsive design
Easy to customize
Beginner-friendly project
📂 Project Structure
toggle-switch-on-off/
│
├── index.html
├── style.css
└── README.md
🚀 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/toggle-switch-on-off.git
2. Open the Project

Simply open index.html in your browser.

🧾 HTML Code
<label class="switch">
  <input type="checkbox">
  <span class="slider"></span>
</label>
🎨 CSS Code
.switch {
  position: relative;
  display: inline-block;
  width: 60px;
  height: 34px;
}

.switch input {
  opacity: 0;
  width: 0;
  height: 0;
}

.slider {
  position: absolute;
  cursor: pointer;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #ccc;
  transition: 0.4s;
  border-radius: 34px;
}

.slider:before {
  position: absolute;
  content: "";
  height: 26px;
  width: 26px;
  left: 4px;
  bottom: 4px;
  background-color: white;
  transition: 0.4s;
  border-radius: 50%;
}

input:checked + .slider {
  background-color: #4CAF50;
}

input:checked + .slider:before {
  transform: translateX(26px);
}
📸 Preview
OFF  ◯────
ON   ────◯
🛠️ Customization

You can customize:

Switch size
Colors
Animation speed
Border radius

Example:

background-color: #2196F3;
transition: 0.3s;
📚 Learning Purpose

This project is great for beginners learning:

CSS positioning
Pseudo-elements
CSS transitions
UI component design
🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

📄 License

This project is licensed under the MIT License.

⭐ Support

If you like this project, give it a ⭐ on GitHub!
