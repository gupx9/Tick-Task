# 🌟 Tick-Task: Your Mini Productivity Hub

**Tick-Task** is a lightweight web app that combines a **Stopwatch**, **To-Do List**, and **Daily Motivation** — designed for productivity lovers and beginners learning front-end web development.  
Built entirely using **HTML**, **CSS**, and **vanilla JavaScript**, it’s simple, responsive, and works right in your browser.

---

## ✨ Features

### ⏱️ Stopwatch
- Start, Stop, and Reset buttons  
- Real-time display of **minutes : seconds : milliseconds**  
- Smooth timer accuracy using `setInterval()`  

### 📝 To-Do List
- Add, check off, or delete daily tasks  
- Stores tasks in local storage (persists after refresh)  
- Minimal and clean design  

### 💬 Daily Motivation
- Displays a **new motivational quote** each time the page reloads  
- Encourages a positive start for your work or study sessions  

---

## 🧩 Tech Stack

| Part | Technology |
|------|-------------|
| Structure | **HTML5** |
| Styling | **CSS3** |
| Logic | **JavaScript (Vanilla)** |

---

## ⚙️ How It Works

1. **Stopwatch:**  
   Uses JavaScript’s `setInterval()` to increment milliseconds. When 100 ms pass, one second is added; after 60 seconds, one minute increments.  
   The Stop button pauses using `clearInterval()`.

2. **To-Do List:**  
   Each task is saved as an object inside `localStorage`, so your list remains even after closing the browser.

3. **Motivational Quotes:**  
   A small array of quotes is randomized every time the page loads, ensuring a new burst of inspiration daily.
