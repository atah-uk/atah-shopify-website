# Atah Website

A modern, feature-rich e-commerce website designed to provide an exceptional shopping experience with extensive customization options and performance optimizations.

## Overview

Atah's website is built on Shopify using Liquid, CSS, and JavaScript, providing a flexible and customizable foundation for the online store. The website emphasizes clean design, smooth user interactions, and powerful customization capabilities through the Shopify theme editor.

## Key Features

### Design & Customization

- **Color Schemes**: Multiple color scheme options with full customization for backgrounds, text, buttons, variants, and UI elements
- **Typography**: Customizable font families for body, heading, subheading, and accent text with extensive size, line height, and letter spacing controls
- **Responsive Design**: Fully responsive layouts optimized for mobile, tablet, and desktop devices
- **Animations**: Configurable page transitions, add-to-cart animations, and product card hover effects
- **Badges**: Customizable product badges with position, corner radius, and color scheme options

### Product Experience

- **Product Cards**: Advanced product card system with quick add functionality, hover effects, second image on hover, and carousel support
- **Variant Picker**: Flexible variant selection with button and swatch options, customizable styling
- **Media Gallery**: Rich media support including images, videos, and 3D models with zoom functionality
- **Product Recommendations**: Intelligent product recommendation system
- **Inventory Display**: Real-time inventory status and availability indicators
- **Recently Viewed Products**: Automatic tracking and display of recently viewed items

### Shopping Cart

- **Cart Types**: Choose between drawer or page-based cart experience
- **Cart Drawer**: Modern slide-out cart drawer with auto-open option
- **Quick Add**: Add products to cart directly from product cards
- **Cart Features**: Seller notes, discount code input, installments display, accelerated checkout buttons
- **Cart Customization**: Customizable product title case, price fonts, and media styling

### Search & Navigation

- **Predictive Search**: Real-time search suggestions with product, collection, and article results
- **Search Modal**: Full-screen search interface with keyboard shortcuts
- **Collection Filtering**: Advanced filtering and sorting capabilities
- **Mega Menu**: Support for complex navigation structures
- **Header Customization**: Flexible header layouts with announcement bars and multiple menu styles

### Performance

- **View Transitions**: Smooth page transitions using modern web APIs
- **Lazy Loading**: Optimized image and asset loading
- **Critical CSS**: Inline critical styles for faster initial render
- **Code Splitting**: Modular JavaScript architecture for efficient loading

### Accessibility

- **Keyboard Navigation**: Full keyboard support throughout the website
- **Screen Reader Support**: Semantic HTML and ARIA attributes
- **Focus Management**: Proper focus handling in dialogs and modals
- **Skip Links**: Accessibility navigation shortcuts

### Internationalization

- **Multi-language Support**: Comprehensive translation files for 30+ languages including:
  - European: English, German, French, Spanish, Italian, Portuguese, Dutch, Polish, Czech, and more
  - Asian: Chinese (Simplified & Traditional), Japanese, Korean, Thai, Vietnamese, Indonesian
  - Other: Arabic, Russian, Turkish, and many more
- **Localization**: Currency and date formatting support
- **RTL Support**: Right-to-left language support

## Website Structure

```
shopify-v1/
├── assets/              # JavaScript, CSS, and SVG files
├── blocks/             # Reusable block components
├── config/             # Theme configuration
│   ├── settings_schema.json
│   └── settings_data.json
├── layout/             # Theme layouts
│   ├── theme.liquid
│   └── password.liquid
├── locales/            # Translation files
├── sections/           # Theme sections
├── snippets/           # Reusable Liquid snippets
└── templates/           # Page templates
```

## Assets

### JavaScript Modules

The website uses modern ES6 modules with custom elements for component architecture:

- **Cart Management**: `cart-drawer.js`, `cart-icon.js`, `cart-discount.js`, `cart-note.js`
- **Product Features**: `product-form.js`, `product-price.js`, `product-inventory.js`, `variant-picker.js`
- **Search**: `predictive-search.js`, `search-page-input.js`, `results-list.js`
- **Media**: `media-gallery.js`, `media.js`, `video-background.js`, `zoom-dialog.js`
- **Navigation**: `header.js`, `header-menu.js`, `header-drawer.js`, `facets.js`
- **UI Components**: `dialog.js`, `accordion-custom.js`, `slideshow.js`, `marquee.js`
- **Performance**: `performance.js`, `section-renderer.js`, `view-transitions.js`
- **Utilities**: `utilities.js`, `localization.js`, `events.js`

### CSS Architecture

- **Base Styles**: `base.css` - Core theme styles and component foundations
- **Component Styles**: Modular CSS for reusable components
- **Responsive Utilities**: Mobile-first responsive design patterns
- **Animation System**: Smooth transitions and animations throughout

### SVG Icons

Comprehensive icon library including:
- Navigation: cart, menu, search, account, close
- Product: add-to-cart, available, unavailable, inventory
- UI: arrow, caret, checkmark, error, filter, plus, minus
- Media: play, pause, grid views

## Sections

### Core Sections

- **Header Group**: Configurable header with menus, logo, search, and cart
- **Footer Group**: Flexible footer with links, social icons, and payment methods
- **Product Information**: Product details, media, variants, and purchase options
- **Collection**: Product listing with filters, sorting, and grid controls
- **Cart**: Shopping cart with items, summary, and checkout options
- **Search Results**: Search interface with filters and result display
- **Blog**: Blog post listing and individual post layouts

### Content Sections

- **Hero**: Large banner section for homepage or landing pages
- **Slideshow**: Image and video carousel with navigation
- **Media with Content**: Image/video sections with text overlays
- **Featured Product**: Highlighted product showcase
- **Featured Collection**: Product grid from selected collection
- **Marquee**: Scrolling text or image banner
- **Accordion**: Expandable content sections
- **Custom Liquid**: Custom code injection section
- **Email Signup**: Newsletter subscription forms
- **Contact Form**: Customer contact forms

### Layout Sections

- **Section**: Flexible container for custom layouts
- **Divider**: Visual separator elements
- **Spacer**: Custom spacing controls
- **Group**: Logical grouping of blocks

## Blocks

The website includes 90+ reusable blocks organized into categories:

### Product Blocks
- Product media gallery
- Product title, price, description
- Variant picker and swatches
- Buy buttons and add to cart
- Product inventory
- Product custom properties
- Product recommendations

### Content Blocks
- Text, headings, and inline text
- Images and media
- Buttons and links
- Video players
- Icons and social links
- Accordion rows

### Collection Blocks
- Collection cards and links
- Collection information
- Featured collection grids

### Cart Blocks
- Cart products listing
- Cart summary and totals
- Cart title and notes
- Accelerated checkout buttons

### Navigation Blocks
- Menu items
- Header logo
- Social icons
- Payment icons

## Configuration

### Website Settings

Accessible through the Shopify theme editor, organized into logical groups:

#### Logo & Branding
- Logo upload and sizing
- Inverse logo option
- Favicon configuration

#### Colors
- Multiple color schemes
- Customizable backgrounds, text, buttons, inputs
- Variant picker colors
- Badge colors

#### Typography
- Font family selection (body, heading, subheading, accent)
- Font size controls for all heading levels (H1-H6)
- Line height and letter spacing
- Text case transformations

#### Buttons
- Primary and secondary button styles
- Border radius and width
- Font and text case options
- Button hover states

#### Product Cards
- Quick add functionality
- Hover effects (lift, scale, subtle zoom)
- Second image on hover
- Product card carousel

#### Cart Settings
- Cart type (drawer or page)
- Auto-open cart drawer
- Cart features (notes, discounts, installments)
- Cart styling options

#### Search
- Predictive search configuration
- Search result styling
- Empty state customization

#### Swatches
- Variant swatch dimensions
- Border styles and radius
- Color and image swatches

#### Animations
- Page transitions
- Product transitions
- Add to cart animations
- Card hover effects

#### Badges
- Badge position
- Corner radius
- Color schemes for sale and sold out

## Templates

### Page Templates

- **index.json**: Homepage template
- **product.json**: Product detail page
- **collection.json**: Collection listing page
- **blog.json**: Blog listing page
- **article.json**: Individual blog post
- **page.json**: Generic page template
- **cart.json**: Shopping cart page
- **search.json**: Search results page
- **404.json**: Error page
- **password.json**: Password protection page
- **gift_card.liquid**: Gift card template

### Custom Page Templates

- **page.about.json**: About page layout
- **page.artist.json**: Artist page layout
- **page.contact.json**: Contact page layout
- **page.events.json**: Events page layout

## Snippets

110+ reusable Liquid snippets organized by functionality:

### Product Snippets
- Product card rendering
- Product media displays
- Product price formatting
- Product inventory status
- Variant pickers and swatches

### Cart Snippets
- Cart drawer implementation
- Cart products listing
- Cart summary calculations
- Discount code interface

### Navigation Snippets
- Header components
- Menu rendering
- Mega menu structures
- Footer elements

### Media Snippets
- Image optimization
- Video embedding
- Slideshow components
- Media galleries

### Form Snippets
- Contact forms
- Email signup forms
- Account actions
- Localization forms

### UI Snippets
- Buttons and links
- Icons and badges
- Typography utilities
- Spacing controls

## Customization Guide

### Color Schemes

The website supports multiple color schemes that can be applied to different sections. Configure colors in Theme Settings > Colors, where you can:

- Set background and text colors
- Customize button colors (primary and secondary)
- Configure input field colors
- Set variant picker colors
- Define badge colors

### Typography

Customize typography through Theme Settings > Typography:

1. Select font families for different text types
2. Adjust font sizes for headings (H1-H6)
3. Set line heights (tight, normal, loose)
4. Configure letter spacing
5. Apply text case transformations

### Layout Customization

- **Page Width**: Choose between narrow, normal, or wide layouts
- **Section Widths**: Full-width or page-width sections
- **Spacing**: Custom padding and margin controls
- **Grid Layouts**: Flexible grid systems for product listings

### Component Styling

Many components can be customized individually:

- **Buttons**: Border radius, border width, fonts
- **Inputs**: Border styles, border radius, typography
- **Drawers**: Colors, borders, shadows
- **Popovers**: Colors, borders, shadows, radius
- **Badges**: Position, radius, colors

## Browser Support

The website supports all modern browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- **Critical CSS**: Inline critical styles for faster initial paint
- **Lazy Loading**: Images and assets load on demand
- **View Transitions**: Smooth page transitions using modern APIs
- **Code Splitting**: Modular JavaScript for efficient loading
- **Optimized Assets**: Minified and optimized JavaScript and CSS
- **Performance Monitoring**: Built-in performance utilities

## Development

### JavaScript Architecture

The website uses modern JavaScript with:

- ES6 modules
- Custom Elements API
- Event-driven architecture
- Component-based structure

### Styling Approach

- CSS custom properties (variables)
- Mobile-first responsive design
- BEM-like naming conventions
- Modular component styles

### Liquid Templates

- Reusable snippets for common components
- Section-based architecture
- Block-based content management
- Schema-driven settings

## Support & Resources

### Theme Editor

All website customization can be done through the Shopify theme editor. Navigate to **Online Store > Themes > Customize** to access:

- Website settings
- Section customization
- Block management
- Preview mode

### Documentation

For detailed customization help:

- Review the website settings in the Shopify admin
- Use the built-in help text within theme settings
- Refer to Shopify's theme documentation

## Version

**Website Version**: 3.0.0

---

*Atah's website is designed to provide a beautiful, functional online shopping experience on the Shopify platform.*

