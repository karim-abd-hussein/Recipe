# Simple Recipe Page

A clean and responsive recipe page built using HTML and CSS. This project showcases a classic omelette recipe with a detailed preparation guide, ingredients list, nutritional information, and visually appealing design.

---

## Features
- **Responsive Design**: Adapts seamlessly to different screen sizes.
- **Customizable Style**: Uses CSS variables for primary colors, margins, and border-radius.
- **Detailed Recipe**: Includes preparation time, ingredients, and step-by-step cooking instructions.
- **Nutritional Info**: Displays calories, protein, carbs, and fat content.

---

## Technologies Used
- **HTML5**: For semantic structure and accessibility.
- **CSS3**: For styling, layout, and responsive behavior.

---

## CSS Highlights
- **CSS Variables**: Used for consistency and easier theme customization:
  ```css
  :root {
    --primary-color: hsl(14, 45%, 36%);
    --second-color: hsl(12, 11%, 83%);
    --main-margin: 15px 0;
    --radius: 1.2em;
  }
  ```
- **Responsiveness**: Adjustments for screens smaller than `775px`:
  ```css
  @media (max-width: 775px) {
    body {
      margin: 0;
    }
    .continer {
      padding: 0;
      border-radius: 0;
    }
    .omelette {
      border-radius: 0;
    }
    .mobile-continer {
      padding: 0 30px;
    }
  }
  ```
- **Grid Layout**: Used for nutritional information display:
  ```css
  .vag {
    display: grid;
    grid-template-columns: auto auto;
  }
  ```

---

## Preview
![Preview of the Recipe Page](./preview.jpg)

---

## How to Use
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/karim-abd-hussein/Recipe
   ```
2. Navigate to the project folder:
   ```bash
   cd recipe-page
   ```
3. Open the `index.html` file in your browser.

---

## Project Structure
```
.
├── index.html        # Main HTML file
├── index.css         # Stylesheet
├── assets/           # Folder for images and other assets
│   └── images/
│       └── image-omelette.jpeg
└── README.md         # Project documentation
```

---

## Credits
- **Design and Development**: Kairm Hussein.

