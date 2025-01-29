# Bakery Online Delivery Service

## Project Overview

This project is a single-page website for an online bakery delivery service. Users can browse a list of bakery items, filter them by category, add items to a shopping cart, and switch between light and dark mode.

## Features

- **Responsive Design**: The website will work on both mobile and desktop.
- **Product Listing**: Bakery items will be displayed as cards.
- **Category Filtering**: Users can filter bakery items by categories such as vegan, gluten-free, or classic treats.
- **Shopping Cart**: A shopping cart component will display selected items and the total price.
- **Dark Mode Toggle**: Users can switch between light and dark mode for better accessibility and preference.

## Development Steps

1. **Project Setup**
   - Initialize a new project with Vite (React + TypeScript).
   - Set up a clean folder structure (components, assets, styles).

2. **Create the UI Components**
   - `Header`: Contains the logo and navigation links.
   - `Hero`: Displays a welcome message and a call-to-action button.
   - `DishCard`: Displays bakery items (name, image, price, category).
   - `FilterBar`: Allows users to filter items by category.
   - `ShoppingCart`: Shows selected items and the total price.
   - `DarkModeToggle`: Switches between light and dark mode.

3. **Implement State Management**
   - Create the shopping cart
   - Store the dark mode preference in local storage.

4. **Make the Website Responsive**
   - Use Flexbox/Grid for layout.
   - Ensure the design adapts to mobile and desktop screens.

5. **Enhance the UI/UX**
   - Add animations for better interactions.
   - Use consistent typography and spacing.

6. **Test and Deploy**
   - Perform cross-browser testing.
   - Deploy using Netlify or Vercel.

## Design Conventions

To ensure a visually appealing and user-friendly interface, follow these design guidelines:

### Typography

- Use a readable font like `Poppins` or `Montserrat`.
- Maintain proper text hierarchy:
  - **Headings:** Bold, slightly larger font.
  - **Body Text:** Regular weight, comfortable size.

### Color Scheme

#### Light Mode

- Background: `#FFF8E1` (light cream)
- Primary Color: `#D2691E` (warm brown)
- Accent: `#F4A460` (sandy orange)
- Text: `#5C4033` (dark brown)

#### Dark Mode

- Background: `#2B1B0F` (dark chocolate)
- Primary Color: `#A0522D` (sienna)
- Accent: `#D2691E` (warm brown)
- Text: `#F5DEB3` (wheat)

### Layout and Spacing

- Use padding and margins to separate elements.
- Ensure consistent spacing between items for a clean layout.
- Maintain a max width for content to prevent stretching on large screens.

### Button and Card Styles

- Use rounded corners (`border-radius: 8px` or more) for a soft feel.
- Hover effects on buttons (`opacity` change or slight `box-shadow`).
- Bakery item cards should have an image, name, price, and an "Add to Cart" button.

## Conclusion

This project will serve as a simple and elegant online delivery system for your bakery. By following these guidelines, you will create a visually appealing and user-friendly experience for customers.
