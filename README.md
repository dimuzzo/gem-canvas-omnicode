# OmniCode: The Polyglot's Handbook 📘

**OmniCode** is an interactive, web-based handbook designed to help developers quickly compare and understand the basics of Python, Java, and C.

It features a responsive, app-like interface that allows users to toggle between languages instantly to see syntax differences side-by-side.

## 🚀 Features

* **Three-Language Context Switching:** Instantly switch between Python, Java, and C to compare syntax.
* **Structured Curriculum:** Covers Basics, Data Structures (Lists, Maps, Arrays), and Standard Libraries.
* **Interactive Code Blocks:** Syntax-highlighted snippets for clear readability.
* **Knowledge Checks:** Interactive quizzes at the end of each section to test retention.
* **Mobile Responsive:** Fully functional layout optimized for both mobile and desktop devices.

## 🛠️ Technologies Used

* **[React](https://react.dev/) (v18+)** - UI Library
* **[Vite](https://vitejs.dev/)** - Build tool
* **[Tailwind CSS](https://tailwindcss.com/)** - Styling
* **[Lucide React](https://lucide.dev/)** - Icons

## 💻 How to Run Locally

If you want to run this project on your own machine to make edits, follow these steps:

1. **Clone the repository**
  
    ```bash
    git clone https://github.com/dimuzzo/gem-canvas-omnicode.git
    cd gem-canvas-omnicode
    ```

2. **Install Dependencies**
   
   ```bash
   npm install
   ```


3. **Start Development Server**
   
   Use this command while you are editing code. It supports hot-reloading.
   
   ```bash
   npm run dev
   ```
   
   Open the link shown in the terminal (usually http://localhost:5173).

4. **Preview Production Build**

   Use this to see exactly how the deployed site will look and behave.
  
   ```bash
   npm run build
   npm run preview
   ```

---

## 🌍 Deployment

This project is optimized for deployment on GitHub Pages.

**Deployment Steps**

1. Update ``vite.config.js`` to set the base path:
   
  	```bash
    export default defineConfig({
      plugins: [react()],
      base: './', // Crucial for relative paths on GitHub Pages
    })
   ```

2. Run the build command:
   
    ```bash
    npm run build
    ```

3. Upload the contents of the ``dist`` folder to your GitHub repository (or use the ``gh-pages`` branch method).
4. Enable GitHub Pages in your repository settings pointing to the uploaded files.

---

## 🤖 AI Generation Info

This project was generated using the help of Google Gemini.

- Model: Gemini 3.0 Pro

---

## 📄 License

This project is open source.

---

Created with ❤️ by [dimuzzo](https://github.com/dimuzzo)
