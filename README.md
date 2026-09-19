# ✏️ NoteFolio

A charming, handmade doodle-style personal portfolio template built with HTML and CSS. Perfect for developers, designers, and creatives who want a unique, sketch-like web presence.

<img width="1365" height="645" alt="image" src="https://github.com/user-attachments/assets/2ee59c02-8707-4356-8696-bb533929edf4" />


## ✨ Features

* **Handmade Aesthetic:** Sketchy borders, pencil textures, and playful CSS doodles (stars, sparkles, swirls).

* **Interactive Elements:** Click-to-copy buttons for Discord and Phone contacts with animated toast notifications.

* **Embedded Audio:** Background ambient music support (`autoplay loop`).

* **Responsive & Lightweight:** Pure HTML and CSS with zero heavy JavaScript frameworks required.

* **Fully Customizable:** Easily tweak colors, links, and text to make it your own.

## 🚀 Quick Start

1. **Clone or Download** this repository:

   ```
   git clone https://github.com/your-username/notefolio.git
   
   ```

2. Open the project folder in your favorite code editor (like VS Code).

3. Open `index.html` in your browser or use a live server extension to view it locally.

## 🛠️ Customization

### 1. Personal Information & Social Links

Open `index.html` and modify the following sections to match your details:

* **Name & Title:** Look for the `.card-title` div.

* **Social Media Links:** Update the `href` attributes inside the `.doodle-container` list items.

* **Discord & Phone:** Update the `data-copy` attributes with your actual username and phone number:

  ```
  <button type="button" class="doodle-link copy-btn" data-copy="yourusername#0000">...</button>
  
  ```

* **Email:** Change `haripatel@notefolio.com` to your personal email address.

### 2. Background Music

To change or remove the background music:

* Replace the audio file at `music/song2.mp3` with your preferred `.mp3` track, or remove the `<audio>` block entirely if you prefer silence.

## 📁 Project Structure

```
notefolio/
├── index.html       # Main HTML markup
├── styles.css       # Doodle styles, layout, and keyframe animations
├── assets/          # Images and icons
└── music/           # Background audio tracks

```

## 📄 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and share it for your own personal portfolio!

## 💖 Credits

* **Site Design & Code:** [Jimmy Mc 124](https://jimmymc.netlify.app/?utm_source=gemini)

* **UI Elements & Inspiration:** [Hari Bro via Uiverse.io](https://uiverse.io/profile/mamyapro123?utm_source=gemini)
