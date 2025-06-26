 # Run Framework 🏃‍♂️‍➡️

**Inspired by React. Powered by jQuery. Designed for Speed.**

Run Framework is a lightweight JavaScript framework for building blazing-fast, single-page web applications in just **four simple steps** — with no page reloads and no bloated setup.

---

## 🚀 Why Run Framework?

- 🔄 **No reloads:** All updates happen dynamically on the frontend.
- ⚛️ **React-inspired:** Component-based architecture.
- ⚡ **jQuery-powered:** Simple and direct DOM control.
- 🧩 **Only 3 core parts:** Clean, fast, and beginner-friendly.

---

## 🔧 The 4 Core Building Blocks

1. **Routes**
   - Define your app’s navigation flow

2. **Screens**
   - Map each route to a screen layout

3. **Components**
   - Reusable UI pieces that respond to state and interaction

 
---

## ✨ Example
```html
<!-- Define a route -->
<route path="/home" screen="HomeScreen"></route>

<!-- Create a screen -->
<screen id="HomeScreen">
  <component is="Header"></component>
  <element bind="message"></element>
</screen>

<!-- Component definition -->
<component name="Header">
  <h1>Welcome to Run Framework</h1>
</component>

<script>
  Run.set('message', 'Hello, world!');
</script>
```

---

## 📦 Installation

```bash
npm install run-framework
```
Or via CDN:
```html
<script src="https://cdn.runframework.dev/latest/run.min.js"></script>
```

---

## 🧪 Getting Started

Check the [Docs](#) to learn how to:
- Set up routes and screens
- Create and reuse components
- Handle dynamic state with elements

---

## 🌐 Who is it for?
- Developers tired of bloated frontend tools
- Beginners coming from jQuery or React
- Anyone who wants fast, reload-free apps

---

## 🧠 License
MIT License
