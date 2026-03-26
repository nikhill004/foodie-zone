# 🍛 Foodie Zone - Food Ordering Landing Page

A responsive food ordering landing page built with React.js and Tailwind CSS, featuring smooth animations, dark mode support, and an interactive UI.

Preview: https://foodiebynik.netlify.app/

## 🚀 Tech Stack

- **React 18** - Component-based UI
- **Vite** - Fast build tool and dev server
- **Tailwind CSS** - Utility-first styling
- **AOS** - Scroll-triggered animations
- **React Slick** - Testimonials carousel
- **React Icons** - Icon library
- **React Star Ratings** - Star rating component

## ✨ Features

- Dark / Light theme toggle with `localStorage` persistence
- Interactive hero section with dynamic product image switcher
- Auto-playing testimonials slider (pause on hover)
- Responsive layout for mobile, tablet, and desktop
- Smooth scroll animations using AOS
- Gradient text and button effects with Tailwind CSS

## 📁 Project Structure

```
src/
├── assets/              # Images and static assets
├── components/
│   ├── Navbar/          # Navbar with dark mode toggle
│   ├── Hero/            # Hero section with image carousel
│   ├── Services/        # Menu/services cards
│   ├── Banner/          # Promotional banner
│   ├── AppStore/        # App download section
│   ├── Testimonial/     # Customer reviews slider
│   └── Footer/          # Footer
├── App.jsx
├── main.jsx
└── index.css
```

## 🛠️ Getting Started

### Prerequisites

- Node.js >= 16
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/foodie-zone.git

# Navigate to project directory
cd foodie-zone

# Install dependencies
npm install
```

### Running the App

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📸 Sections

| Section | Description |
|---|---|
| Navbar | Logo, nav links, dark mode toggle, order button |
| Hero | Animated headline, image switcher, CTA button |
| Services | Food menu cards with hover effects |
| Banner | Promotional content section |
| App Store | Mobile app download links |
| Testimonial | Auto-playing customer reviews carousel |
| Footer | Links and branding |

## 📦 Dependencies

```json
{
  "aos": "^2.3.4",
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "react-icons": "^4.12.0",
  "react-slick": "^0.29.0",
  "react-star-ratings": "^2.3.0",
  "slick-carousel": "^1.8.1"
}
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
