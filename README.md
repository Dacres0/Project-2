# BitBay

[🔗 View Live Site](https://dacres0.github.io/Project-2/)

![Responsive Design Preview](assets/images/responsive-preview.png)

## Introduction

BitBay is a modern, crypto-friendly online auction platform designed for collectors, sellers, and crypto users alike. It allows users to browse, bid, and purchase unique vintage and antique items using Ethereum and other cryptocurrencies. The platform is responsive, user-focused, and designed with simplicity in mind.

---

## User Experience (UX)

### User Stories (US)

#### User Persona 1: Alex – The Crypto Buyer

**User Story 1: Crypto Spending**  
As Alex, I want to quickly link my crypto wallet to online stores, so I can make secure payments without manually entering details every time.

**Acceptance Criteria:**
- Alex can connect multiple cryptocurrencies to his wallet.
- Alex can select his preferred crypto asset to use for payment.
- The transaction process is quick, with minimal verification.

**User Story 2: Asset Monitoring**  
As Alex, I want to be able to bid on products via Ethereum, so I do not need to convert from Ethereum to pounds, thereby saving transaction fees.

**Tasks:**
- **Task 1:**
  - **Action:** Alex views items using the category tab and finds an item to bid on.
  - **Goal:** View multiple auctions live on the website.
- **Task 2:**
  - **Action:** Alex selects a product to place a bid or max bid.
  - **Goal:** Complete a secure and fast payment transaction using Ethereum.

---

####  User Persona 2: Linda – The Vintage Seller

**User Story: Product Price Setting**  
As Linda, I want an easy-to-use pricing tool, so I can set a fair price for my vintage items without confusion.

**Acceptance Criteria:**
- The website suggests an average price based on category, condition, and similar items sold.
- Linda can adjust the price based on her preferences.
- There is a currency converter to help her set the price in her local currency.

**Tasks:**
- **Task 1:**
  - **Action:** Linda uploads photos of her vintage chair.
  - **Goal:** Create an attractive listing for potential buyers to view.
- **Task 2:**
  - **Action:** Linda sets a price for her vintage ring.
  - **Goal:** Use the pricing tool to find an optimal price point and adjust accordingly.

---

## Design Choices

### Color Palette

![Color Palette](assets/images/color-palette.png)

- I used **dark gray (#343a40)** text against a **light background (#ffffff, #f8f9fa)** to maintain readability and visual contrast.
- Accent color: **Bootstrap Primary Blue (#007bff)** for interactive elements like buttons and links.

### Typography

- **Font:** 'Roboto', sans-serif (via Google Fonts)
- **Weight Usage:** Headings use bold weights for hierarchy, while body content uses lighter weights for readability.

### Structure

- **Framework:** Bootstrap 4.5.2
- **Template:** Responsive grid layout with consistent card components

### Imagery

- Images are sourced from [Unsplash](https://unsplash.com), royalty-free and optimized for high quality.
- Used to represent auction items and for hero images in the carousel.

### Wireframes

!![Picture2](https://github.com/user-attachments/assets/997c2c6a-199a-4c7e-ad85-37135f6b9a8d)


- Initial wireframes used a basic grid and carousel layout.
- Revised to include stronger CTAs and clearer section spacing.

---

## Development Process

### Features

- Live auction cards with item details and bidding buttons
- Carousel of featured items
- Wallet integration for Ethereum-based bidding (conceptual UI)
- Responsive navigation and layout

### Navigation

- Sticky header with links to Home, Auctions, and Payment pages
- Active state highlighting

### Header

- Contains branding/logo and accessible navigation

### Webpage 1: Home

- Carousel with featured item images
- Auction section with live bid cards

### Webpage 2: Auctions

- Individual auction product pages (planned)
- Future enhancements: filters by category and live countdown timers

### webpage 3: Payment 

- payment with ethereum or debit card
- bid on any product
### Footer

- Simple copyright notice
- Future: Social media links and newsletter subscription

---

## Frameworks, Libraries & Programs Used

- [Bootstrap 4.5.2](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
- [Google Fonts – Roboto](https://fonts.google.com/specimen/Roboto)
- [Unsplash](https://unsplash.com)
- [GitHub Pages](https://pages.github.com/)

---

## Deployment & Local Development

### Deployment

1. Pushed all project files to GitHub Repository.
2. Enabled GitHub Pages via repository settings.
3. Selected `main` branch as source.
4. Deployed at: [https://dacres0.github.io/Project-2/](https://dacres0.github.io/Project-2/)

### Local Development

1. Clone the repo: `git clone https://github.com/dacres0/Project-2.git`
2. Open `index.html` in browser or use Live Server in VSCode.
3. Make changes and commit to GitHub to update deployment.

---

## Testing

### Automated Testing

#### W3C HTML Validator
-  Passed with no major errors.
- Screenshot: `assets/images/html-validator.png`

#### W3C CSS Validator
-  Valid CSS.
- Screenshot: `assets/images/css-validator.png`

#### Lighthouse

**Desktop**
- Performance: 98
- Accessibility: 100
- Best Practices: 100
- SEO: 95

**Mobile**
- Performance: 87
- Accessibility: 98

#### Wave Accessibility Tool
- No major accessibility issues found.

---

### Manual Testing

#### Testing User Stories

- Alex was able to browse, select items, and view bid options using Ethereum. (i acted as Alex)
- Linda was able to upload and price items with placeholder pricing tools. (i acted as Linda)

#### Full Testing

Devices tested:
- Windows 10 (Chrome, Firefox)
- macOS (Safari)
- iPhone 12
- Samsung Galaxy S21

Browsers tested:
- Chrome, Firefox, Safari

#### Full Page Testing
- All images render correctly
- Carousel and buttons are responsive
- Navbar and footer function as expected

---

### Bugs
was some issues with the repisitory 
issues with website launching
issues with images

#### Solved Bugs
- Fixed image URLs that did not render (added complete Unsplash URLs with parameters)
- i created a new one uploaded the files and it started working
- search engine had to catch up for images to update
- website fixed itself

#### Known Bugs


---

## Credits / References

### Code Used

- Bootstrap Carousel and Card components
- Responsive nav from Bootstrap docs

### Content

- Created by the BitBay project team

### Media

- Product images from [Unsplash](https://unsplash.com)

### Research Material

- [Lighthouse Docs](https://web.dev/measure/)
- [W3C Validator](https://validator.w3.org/)
- Inspiration: OpenSea, eBay, and Sotheby's auction UI

