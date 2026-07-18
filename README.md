# Jude Joby Joseph - Personal Portfolio

A modern, responsive, and highly premium personal portfolio website built with Flask, Python, and Vanilla CSS. It features a deep dark mode aesthetic, smooth glassmorphism effects, dynamic micro-animations, and a seamless contact form integrated with Google Forms.

## 🌟 Features

- **Premium UI/UX**: Deep dark mode with vibrant neon accents (Cyan, Purple, Pink) and glassmorphic UI elements (frosted glass panels).
- **Dynamic Animations**: Floating 3D visual elements, animated background gradients, and smooth hover transitions.
- **Serverless Contact Form**: The "Get in Touch" page submits directly and silently to Google Forms, triggering a beautiful custom modal upon success without redirecting the user.
- **Fully Responsive**: Optimized for seamless viewing across desktops, tablets, and mobile devices.
- **Flask Backend**: Lightweight, highly customizable Python backend rendering optimized HTML templates.

## 🚀 Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML5, Vanilla CSS3 (Custom Variables, Flexbox, CSS Grid)
- **Icons**: FontAwesome 6
- **Typography**: Google Fonts (Outfit, Inter)

## 📂 Project Structure

```
Personal-Portfolio-Website/
├── app.py                 # Main Flask application and routing
├── requirements.txt       # Python dependencies
├── static/                # Static assets
│   ├── css/               
│   │   └── style.css      # Custom styling, dark mode, glassmorphism
│   ├── images/            # 3D models, avatars, and visual assets
│   └── js/                # Client-side interactivity
└── templates/             # HTML Templates
    ├── base.html          # Master layout template
    ├── index.html         # Hero section & Landing page
    ├── about.html         # Bio, Technical Arsenal, and Certifications
    ├── projects.html      # Portfolio projects & GitHub links
    └── contact.html       # Contact form integrated with Google Forms
```

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/judejjj/Personal-Portfolio-Website.git
   cd Personal-Portfolio-Website
   ```

2. **Create a virtual environment (Recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```
   The application will start on `http://127.0.0.1:5000/`.

## 🎨 Customization

- **Colors & Theming**: Open `static/css/style.css`. All primary colors, glassmorphism opacities, and gradients are stored in the `:root` variables at the very top of the file.
- **Hero Image**: Replace `static/images/3d_image_me.png` with your own AI avatar or photo. The floating 3D animation will automatically apply.
- **Contact Form**: Update the Google Form action URL and input `entry.*` names in `templates/contact.html` to connect it to your own Google Form.

## 📝 License

Designed and developed by [Jude Joby Joseph](https://github.com/judejjj). Open for inspiration and reference.
