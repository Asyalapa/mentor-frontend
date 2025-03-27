# Frontend Mentor – Testimonials grid section Solution  

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).  

## 🔗 Live Site  

- [Live Demo](https://asyalapa.github.io/mentor-frontend/testimonials-grid-section/)  

## 🛠 Built with  

- **Semantic HTML5**  
- **CSS3 with Custom Properties (CSS Variables)**  
- **CSS Grid & Flexbox**  
- **Responsive Design with Media Queries**  
- **Google Fonts**  

## 📝 Development Steps  

### 🖥️ Desktop-First Approach
Designed the layout for larger screens first, using CSS Grid to create a flexible 4-column layout. Cards were strategically placed using grid-template-areas for precise positioning.
Used Flexbox for internal alignment of card headers, avatars, and text content.
Structured the content with semantic HTML (`<main>`, `<article>`) for better accessibility and SEO.
### 🎨 Styling & Theming
Used CSS Variables (`:root`) for consistent colors, spacing, typography, and responsive adjustments.
Imported Barlow Semi Condensed (500, 600 weights) from Google Fonts for typography.
### 📱 Responsive Adjustments
Applied media queries for:
Tablet (≤ 768px) : Adjusted the grid layout to 2 columns while maintaining a logical flow of content.
Mobile (≤ 550px) : Stacked cards in a single column and fine-tuned padding, margins, and font sizes for optimal readability.
Optimized spacing and alignment for all screen sizes using CSS variables like --gap-grid-v, --gap-grid-h, and --pdg-top-article.

### 🎯 Challenges & Learnings  
- **Grid Layout Complexity** : Ensuring cards aligned properly across breakpoints required careful use of grid-template-areas and responsive adjustments.
- **Spacing Consistency** : Used CSS variables (--gap-card-text, --gap-head-article) to maintain uniform gaps between elements.
- **Dynamic Backgrounds** : Added a decorative quotation mark background to the first card using background-image and background-position.
- **Avatar Borders** : Styled avatar borders dynamically using conditional CSS for specific cards to enhance visual distinction.

## ✨ Author  

- Frontend Mentor – [@Asyalapa](https://www.frontendmentor.io/profile/Asyalapa)  
