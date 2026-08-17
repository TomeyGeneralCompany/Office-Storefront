# Office Supply Storefront

A responsive e-commerce website for office supplies built with HTML, CSS, and a modular design system.

## 📁 Project Structure

```
democode forproject/
├── index.html          # Main website structure
├── styles.css          # Component styles & responsive design
├── variables.css       # Design system (colors, spacing, typography)
└── README.md          # Documentation
```

## 🎨 Features

- **Responsive Design**: Works on mobile (550px), tablet (800px), and desktop (1200px+)
- **Modern CSS Grid & Flexbox**: Clean, maintainable layouts
- **CSS Custom Properties**: Centralized design tokens for easy customization
- **Category Navigation**: Interactive menu with hover effects
- **Product Grid**: Flexible product display that adapts to screen size
- **Color Accents**: Category-specific visual indicators
- **Hover Effects**: Smooth transitions and interactive feedback

## 🚀 Getting Started

### Option 1: View Locally
1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build tools or server required!

### Option 2: Deploy to GitHub Pages
1. Go to your repository settings
2. Navigate to **Pages**
3. Under "Source", select `main` branch
4. Save
5. Your site will be live at: `https://isaiztomey7-star.github.io/democodeforproject/`

## 🎯 Customization Guide

### Change Colors
Edit `variables.css`:
```css
--color-brand-blue: #0066cc;        /* Change primary blue */
--color-brand-red: #cc3333;         /* Change accent red */
--color-white: #ffffff;             /* Change background */
```

### Adjust Spacing
```css
--spacing-sm: 8px;                  /* Small gaps */
--spacing-md: 16px;                 /* Medium gaps */
--spacing-lg: 24px;                 /* Large gaps */
```

### Modify Typography
```css
--font-size-large: 16px;            /* Body text size */
--font-size-xl: 24px;               /* Heading size */
--line-height-loose: 1.6;           /* Text spacing */
```

### Add More Products
In `index.html`, copy a product `<li>` block and update:
- Product name in `<div class="subcategory-card__name">`
- Price in the price `<div>`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ (5-column product grid, 4-column categories)
- **Tablet**: 800px-1199px (4-column products, 2-column categories)
- **Mobile**: Below 800px (2-column products, 1-column categories)

## 🔧 Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Grid, Flexbox, Custom Properties, Media Queries
- **No dependencies** - Pure HTML & CSS

## 📝 Next Steps

### Enhance the Website

1. **Add Product Images**
   - Replace gray placeholder boxes with actual product photos
   - Add an `<img>` tag with `src` attribute

2. **Connect to a Backend**
   - Use JavaScript to fetch products from an API
   - Display dynamic pricing and inventory

3. **Add Shopping Features**
   - Implement a shopping cart
   - Add product filters and search
   - Create checkout functionality

4. **Improve SEO**
   - Add meta descriptions
   - Use structured data (Schema.org)
   - Optimize image alt text

5. **Accessibility**
   - Add ARIA labels
   - Improve color contrast
   - Test with screen readers

## 📄 License

Free to use and modify for your projects.

## 💬 Questions?

Check the code comments in `styles.css` and `variables.css` for detailed explanations of each section.