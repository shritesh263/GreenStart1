# 🌿 Green Start — Easy Houseplants for Complete Beginners

> 🌐 **Live Demo:** [https://greenstart10.vercel.app/](https://greenstart10.vercel.app/)  
> Visit the live site deployed on Vercel: **[https://greenstart10.vercel.app/](https://greenstart10.vercel.app/)**

**Green Start** is a clean, calm, and beginner-friendly static website designed to help anyone start growing houseplants with zero stress. Built purely with semantic **HTML5** and modern **CSS3**—no frameworks, no JavaScript libraries, and no build tools required.

---

## 📁 Project Structure

```text
apno1/
├── index.html       # Semantic HTML5 page with 4 main sections
├── style.css        # Mobile-first stylesheet with CSS variables & responsive grids
└── README.md        # Documentation, local preview guide, and deployment instructions
```

---

## ✨ Features & Architecture

- **Semantic HTML5 Structure**: Exactly 4 key sections:
  1. `<header class="hero">`: Site brand, tagline, beginner intro, and navigation.
  2. `<section id="why">`: 3 benefit cards (Cleaner Air, Better Mood, Easy Hobby).
  3. `<section id="plants">`: 5 curated starter plant cards (Snake Plant, Pothos, ZZ Plant, Spider Plant, Aloe Vera) detailing light needs, watering frequency, and beginner tips.
  4. `<footer id="contact">`: Newsletter signup form with tap-friendly inputs and copyright notice.
- **Mobile-First CSS**: Built from mobile (phone) upwards using media queries at `600px` (tablet) and `900px` (desktop).
- **CSS Variables (Custom Properties)**: Centralized palette with soft greens, cream background, and high-contrast dark green typography.
- **System Font Stack**: Fast and clean, completely free of external Google Fonts or tracking scripts.
- **Responsive Layout**: Flexbox for navigation, and CSS Grid for cards:
  - **Phone (< 600px)**: 1 column
  - **Tablet (600px – 899px)**: 2 columns
  - **Desktop (≥ 900px)**: 3 columns
- **Accessibility & Touch Standards**:
  - Minimum 16px body font size.
  - Interactive inputs and buttons meet or exceed the 44px minimum touch target height.
  - High WCAG AA/AAA compliant color contrast.
  - No horizontal overflow or scrolling at any viewport width.

---

## 🚀 How to Run Locally

### Option 1: Direct File Opening (Simplest)
1. Navigate to the project folder on your computer.
2. Double-click `index.html` (or right-click and choose **Open with** > **Google Chrome**, **Microsoft Edge**, **Mozilla Firefox**, or **Safari**).

### Option 2: Python Local Web Server
If you have Python installed, you can run a local development server in your terminal:

```bash
# Navigate to the project directory
cd apno1

# Start Python's built-in HTTP server
python -m http.server 8000
```
Then open your browser and visit: **`http://localhost:8000`**

### Option 3: VS Code Live Server
If you use Visual Studio Code:
1. Install the **Live Server** extension.
2. Right-click `index.html` and select **"Open with Live Server"**.

---

## 🌐 Live Deployment & Free Hosting

### 🟢 Active Deployment (Vercel)
The site is live in production at:
👉 **[https://greenstart10.vercel.app/](https://greenstart10.vercel.app/)**

---

### Alternative Free Hosting Options

#### Method A: Netlify Drop (Instant Drag & Drop — 30 Seconds)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop) (log in or create a free account).
2. Drag and drop the entire project folder (`apno1`) onto the drop area.
3. Netlify will instantly deploy your site and provide a free, live `https://*.netlify.app` link.
4. *(Optional)* Customize the site name under **Site settings > Domain management**.

### Method B: GitHub Pages (Free Git Hosting)
1. Create a free account and a new repository on [GitHub](https://github.com).
2. Push your project files to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial release of Green Start"
   git branch -M main
   git remote add origin https://github.com/<your-username>/green-start.git
   git push -u origin main
   ```
3. In your GitHub repository:
   - Click on **Settings** (top tab).
   - In the left sidebar, click **Pages**.
   - Under **Build and deployment > Source**, choose **Deploy from a branch**.
   - Under **Branch**, select `main` and `/ (root)`, then click **Save**.
4. In 1–2 minutes, your website will be live at:
   `https://<your-username>.github.io/green-start/`

---

## 📱 Responsive Testing Checklist

| Viewport | Device Example | Plants Grid Layout | Navigation & Form | Status |
| :--- | :--- | :--- | :--- | :--- |
| **375px** | iPhone SE / Mobile | 1 column, stacked | Clean wrap, stacked inputs, 48px tap targets | Passed ✅ |
| **768px** | iPad / Tablet | 2 columns | Spaced nav, comfortable 2-column cards | Passed ✅ |
| **1280px** | Laptop / Desktop | 3 columns | Full width header, 3-column grid, generous margins | Passed ✅ |

---

## 📄 License
Created for beginners learning houseplant care. Feel free to customize and expand for your personal garden journey!
