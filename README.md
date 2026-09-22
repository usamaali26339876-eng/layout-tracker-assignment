# Personal Budget Tracker Layout

A clean, responsive dashboard layout built using **HTML5** and custom **CSS3**. This project fulfills the Week 3 layout assignment guidelines by turning interface components into clear, modular layout cards.

## Features Built

*   **Intentional Color Palette**: Features a cohesive, professional navy and slate blue theme (`#102a43`) mixed with gold indicators (`#ecc94b`) for clear styling contrast.
*   **Typography Hierarchy**: Integrated Google Fonts directly into the document. Uses **Poppins** for strong, clean headers and **Inter** for readable body text, inputs, and tables.
*   **Styled Tables & Forms**: Inputs and selectors utilize custom padding, state-focus animations, and explicit labels. The transaction table features bold structural headers, explicit data row padding, and alternating row backgrounds (`:nth-child(even)`) for clear data scanning.
*   **CSS Box Model Layout**: Applied `margin`, `padding`, `border`, and `border-radius: 12px` values intentionally to isolate structural blocks. 

## Structural Breakdown (The 3 Visual Cards)

1.  **Header Card (`<header class="card">`)**: A hero header displaying the app name and tracking objective over a deep-gradient backdrop.
2.  **Add Expense Form Card (`<section class="card">`)**: Contains explicit text inputs, numbers, and category choices styled cleanly with a distinct full-width submission button.
3.  **Expense Table Card (`<section class="card">`)**: Organizes logged tracking data inside a clean, responsive borders layout framework.
