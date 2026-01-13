# PERNAMBUCO NEWS
A responsive webpage about the culture, history, and economy of Pernambuco.

## Deployment
The project is hosted on GitHub Pages.
 **[Visit the Website](https://adonaaai.github.io/News-Static-Webpage/)**

## About
I developed this project to improve my skills in vanilla HTML5 and CSS3. 
The main focus was on **Semantic HTML** to ensure accessibility for visually impaired users, and **Scalable CSS** to make it possible to create new pages without problems.

## Design
I utilized the **Neo-Brutalism** design trend, drawing inspiration from traditional newspapers and old magazines. The design uses high-contrast accent colors to create a bold, raw aesthetic.

### Typography
* **Headlines:** `Archivo Black` (for bold, impactful titles).
* **Body Text:** `Space Grotesk` (for readability in paragraphs).
* **Accents:** `Space Mono` (to highlight specific details and meta-data).

## Architecture
To ensure maintainability, I implemented a **Modular CSS Architecture**. Instead of writing all styles in one large file, I separated them into specific modules (Global, Pages, and Partials).
Each page utilizes its own "master" CSS file that imports all necessary dependencies. This approach keeps the project organized and ensures the corresponding HTML file remains clean with only a single `<link>` reference.

### Folder Structure
```text
/css
  ├── global/          # Variables, Reset, Typography (Shared)
  └── pages/
      └── index/       # Home Page folder
          ├── index.css    # The Master File (Imports variables & partials)
          └── partials/    # Specific Components (Header, Grid, Footer)```

## 📄 License 

### The Code
This project is licensed under the **MIT License** - you are free to use the HTML and CSS architecture for your own studies.

## Tech Stack
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)