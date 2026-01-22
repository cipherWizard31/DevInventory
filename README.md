# 🚀 DevInventory

**DevInventory** is a centralized hub for developers to discover programming languages, frameworks, and libraries. Instead of searching across multiple tabs, users can browse a curated list, search for specific tools, and jump straight to official documentation—all powered by a dynamic API.



---

## ✨ Features

* **🔍 Live Search:** Instantly filter through languages and frameworks by name.
* **🌐 API-Driven:** Content is dynamically fetched and updated from a central API.
* **🔗 Quick Access:** Direct links to official websites and documentation for every entry.
* **📱 Responsive Design:** Fully optimized for desktop, tablet, and mobile views.
* **⚡ Lightweight:** Built for speed and minimal load times.

---

## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **Frontend** | React.js / Vue.js / Vanilla JS (Choose yours) |
| **Styling** | Tailwind CSS / Styled Components |
| **Data Fetching** | Fetch API / Axios |
| **Icons** | Lucide React / FontAwesome |

---

## 🚀 Getting Started

Follow these steps to get a local copy up and running.

### Prerequisites

* [Node.js](https://nodejs.org/) (v16.0.0 or higher)
* npm or yarn

### Installation

1.  **Clone the repo**
    ```bash
    git clone [https://github.com/your-username/DevInventory.git](https://github.com/your-username/DevInventory.git)
    ```
2.  **Navigate to the directory**
    ```bash
    cd DevInventory
    ```
3.  **Install dependencies**
    ```bash
    npm install
    ```
4.  **Run the development server**
    ```bash
    npm run dev
    ```

---

## 📖 API Documentation

This project consumes a custom API to populate the list. 

**Endpoint:** `GET /api/v1/languages`  
**Example Response:**
```json
{
  "id": 1,
  "name": "TypeScript",
  "type": "Language",
  "documentation": "[https://www.typescriptlang.org/docs/](https://www.typescriptlang.org/docs/)",
  "logo": "url_to_logo"
}
