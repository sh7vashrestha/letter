# Letter Page Template

This project is a stylized HTML page that simulates the experience of opening a personal letter. It includes decorative design, handwriting animations, and soft background music to evoke a heartfelt, vintage feel.

## 📦 Files

- `index.html` – The main interactive letter page.
- `assets/music.mp3` – Optional background music (must be placed in the `assets/` directory).
- `assets/icon.png` – Icon used in the page.
- `README.md` – This file.

## 🎨 Features

- Clickable envelope to reveal a letter.
- Handwritten-style fonts and animations applied word by word.
- Responsive design for desktop and mobile.
- Optional background music (autoplays after interaction).
- Placeholder text for letter content and signature.

## 🚀 Usage

1. Clone or download the project.
2. Place a `music.mp3` file in the `assets/` directory or replace the existing one.
3. Open `index.html` in any web browser.
4. Click the envelope to reveal the letter.

## ✍️ Customization

### Editing the Letter Content

Inside `index.html`, the letter body is structured with `<span class="word">...</span>` around each word. This is used to apply animated handwritten effects.

**Example:**

```html
<p>
  <span class="word">Hello,</span>
  <span class="word">this</span>
  <span class="word">is</span>
  <span class="word">a</span>
  <span class="word">letter.</span>
</p>
```

Each `span.word` allows the script to animate individual word appearances. When customizing the letter:

- Keep the `<span class="word">...</span>` wrappers around each word.
- You can use a script or find-replace in your editor if writing a longer message.

### Other Elements to Customize

- **Recipient title** in the `<h1>` tag (e.g., “Dear Reader”).
- **Signature block** (e.g., `[Your Name]`).
- **Music** – Replace `assets/music.mp3` with your own file, or remove the `<audio>` element if not needed.
- **Icon** – Replace `assets/icon.png` with your own image and update the `<link rel="icon">` path in the HTML `<head>`.

## Live Demo
[Website](https://sh7vashrestha.github.io/letter/)

## 📝 Notes

- This is a front-end-only project. No server or backend setup is required.
- Modern browsers support the animations and fonts used.
- Audio playback only begins after user interaction (e.g., click), due to browser autoplay restrictions.

## 📄 License

This template is free to use and modify. Attribution appreciated but not required.
