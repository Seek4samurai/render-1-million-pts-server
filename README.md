# How I Rendered 1 Million Points

A high-performance web-based visualization tool designed to render 1,000,000 points efficiently in the browser. This project demonstrates techniques for handling large datasets using hardware acceleration.
Basically, a demo of how we can use WebGL to handle & render these large datasets on the client side.

This is the server for the frontend. Here we give support for rendering out

> ⚠️ This is **not** a traditional web application.  
> It’s a **data visualization** focused purely on performance.

---

## 🏁 Getting Started

### Prerequisites

- **Node.js:** [Download Node.js](https://nodejs.org/) (v16+ recommended).
- **Python:** [Download Python](https://www.python.org/) (v3.x for data processing scripts).
- **Modern Web Browser:** A browser that supports **WebGL 2.0** (Chrome, Firefox, Edge, or Safari).

### Installating Server

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Seek4samurai/render-1-million-pts-server
   cd render-1-million-pts-server
   ```

2. **Install dependencies:**

   Make a virtual environment.

   ```bash
   python -m venv env
   ```

   Activate the virtual environment.

   ```bash
   source env/bin/activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the development server:**
   ```bash
   fastapi dev server.py
   ```

### **Important Note**

Frontend already has the ability to load points without the need of a server. But if you want to hover over a point load its data, like which song
am I hovering on? Basically its metadata you'll need to setup the server.

### To setup frontend follow this guide: [Frontend Guide](https://github.com/Seek4samurai/render-1-million-pts?tab=readme-ov-file#how-i-rendered-1-million-points)
