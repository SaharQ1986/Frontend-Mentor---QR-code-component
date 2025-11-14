# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 🧠 Overview

### 📌 The challenge

Users should be able to:

- View the component on any device size
- See a clean, centered layout
- Read the text and view the QR image clearly

---

## 🚀 My Process

### 🧱 Built With

- Semantic HTML5
- CSS3 (Flexbox for alignment)
- Custom CSS variables
- Responsive design
- Google Fonts (Outfit)

---

## 📂 File Structure

📱 Responsive Design

This component is naturally responsive because:

A fixed-width card (320px) centered inside a flexible container

Image is inside the card and resizes consistently

The max-width: 100% prevents overflow

No complex media queries were needed.

### Mobile (≤ 375px)

```CSS
.container {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
.card {
  width: 320px;
  max-width: 100%;
  height: 500px;
  background-color: var(--clr-white);
  border-radius: 16px;
  margin: 10px 16px;
}

```

---

🧪 How to Run

1. Download or clone this repo

2. Open index.html in your browser

3. Enjoy the clean QR component 💙

---

## 🚀 Live Demo

[[live demo link ](https://chimerical-kelpie-ad5f52.netlify.app/)]

## 🧑‍💻 Author

- Frontend Mentor – [@SaharQ1986](https://www.frontendmentor.io/profile/SaharQ1986)
- GitHub – [@SaharQ1986](https://github.com/SaharQ1986/Frontend-Mentor---QR-code-component.git)

---

## 🪶 Acknowledgments

Design concept inspired by [Frontend Mentor](https://www.frontendmentor.io/).
