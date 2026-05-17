# 🌌 Nexus Premium — Glassmorphic Dashboard Template

Congratulations on acquiring **Nexus Premium**, the ultimate single-page glassmorphic landing page boilerplate designed to help you launch your SaaS or digital product in record time.

This premium, clean, high-performance HTML/CSS/JS template is optimized for high conversions, beautiful UI styling, and features live interactive metrics powered by **Chart.js**.

---

## 🚀 Key Features

* **Glassmorphism Design**: High-fidelity modern styling using CSS backdrop filters, sleek neon glows, and custom typography (`Plus Jakarta Sans`).
* **Live Interactive Mockups**: Integrated real-time numbers updates simulator and an embedded interactive Chart.js line graph.
* **Fully Responsive**: Adapts flawlessly from standard 4K desktop screens down to mobile phones.
* **Zero Dependencies**: Pure HTML, Vanilla CSS, and lightweight JS. No complex build tools or heavy node modules required. Simply open and run.

---

## 🛠️ How to Customize

### 1. Change the Brand Logo and Text
Open [index.html](index.html) and search for the `<div class="logo">NEXUS</div>` tag. Replace `NEXUS` with your own company name or logo.

### 2. Configure Your Core Color Palette
Inside the CSS `<style>` section of [index.html](index.html), locate the `:root` variables:
```css
:root {
  --bg: #030712;         /* Deep dark background */
  --accent: #3b82f6;     /* Primary blue accent */
  --accent2: #a855f7;    /* Secondary purple gradient accent */
  --text: #f9fafb;       /* Bright body text */
}
```
Simply adjust these hex values to match your brand style guides!

### 3. Edit Dashboard Data
To customize the graph data points, search for the `const liveChart` variable at the bottom of the script section and edit the list of months (`labels`) and values (`data`):
```javascript
data: {
  labels: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul'],
  datasets: [{
    label: 'Monthly Growth (USD)',
    data: [12000, 19000, 15000, 25000, 22000, 30000, 45231],
    ...
```

---

## 📄 License
This template is licensed under the permissive **MIT License**. You are free to modify and use it for personal or commercial projects.
