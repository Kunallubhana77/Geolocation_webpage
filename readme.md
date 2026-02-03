# 🌍 Geolocation Matrix

A futuristic, cyberpunk-inspired geolocation finder that reveals your coordinates with a dramatic Matrix-style decoding animation.


![Project Preview](preview.png)

## ✨ Features
![Uploading Screenshot 2026-02-03 at 1.50.45 PM.png…]()![Uploading Screenshot 2026-02-03 at 1.51.26 PM.png…]()


- **Matrix Aesthetic**: Full-screen digital rain background with a custom canvas implementation.
- **Cyberpunk UI**: Centralized "Initiate Trace" button with neon glow effects and scanline overlays.
- **Decoding Animation**: Coordinates are revealed through a cryptographically-inspired text decoding effect.
- **Responsive Design**: Centralized layout that works on various screen sizes.
- **Privacy First**: Locations are fetched only when you click the button and approve the browser prompt.

## 🚀 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/geolocation-matrix.git
   ```
2. **Open the file**:
   Simply open `index.html` in any modern web browser.
3. **Grant Permission**:
   Click "INITIATE TRACE" and allow location access when prompted by your browser.
4. **Watch the Magic**:
   Observe the system "triangulating" your signal and decoding your latitude and longitude.

## 🛠️ Built With

- **HTML5**: Semantic structure.
- **CSS3**: Advanced styling including:
  - Custom animations (`@keyframes`)
  - Glassmorphism & Neon Glow effects
  - Scanlines and CRT effects
- **JavaScript (Vanilla)**:
  - Geolocation API (`navigator.geolocation`)
  - HTML5 Canvas for Matrix Rain
  - Custom text decoding algorithms

## 🔮 Demo logic

The "decoding" effect iterates through random characters before locking onto the actual coordinate digits, simulating a hacking or decrypting process.

```javascript
// Pseudo-code of the effect
interval = setInterval(() => {
    displayText = targetText
        .split("")
        .map((char, index) => {
            if (index < iteration) return char; // Locked character
            return randomChar(); // Scrambled character
        })
        .join("");
}, speed);
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*System Status: ONLINE* 🟢
