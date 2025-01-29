# JobHuntly - Job Search Platform

A modern job search platform built with React, TypeScript, and Material UI, featuring a clean and intuitive interface for job seekers and employers.

## 📁 Project Structure

```
src/
├── assets/               # Static assets like images
├── components/          
│   ├── Categories/      # Job categories components
│   │   └── index.tsx    
│   ├── Footer/         
│   │   └── index.tsx    
│   ├── Header/          
│   │   └── index.tsx    
│   ├── Jobs/            # Job listing components
│   │   └── index.tsx
│   └── OpeningJobs/     # Latest job openings section
│       └── index.tsx
├── layouts/
│   └── mainlayout.tsx   # Main layout wrapper
├── pages/
│   └── homepage.tsx     # Home page component
├── App.tsx              # Root component
└── index.css            # Global styles
```

## 🎯 Features

### Header Section
- Logo and navigation
- Find Jobs & Browse Companies links
- Login and Sign Up buttons

### Hero Section
- Job search functionality
- Location selector
- Popular search tags
- Company showcase (Vodafone, Intel, Tesla, AMD, Talkit)

### Categories Section
- 8 different job categories
- Individual category cards with:
  - Category icon
  - Category name
  - Available jobs count
  - Category-specific styling

### CTA Section
- "Start posting jobs today" banner
- Sign up promotion
- Dashboard preview

### Featured Jobs Section
- Job cards with company logos
- Job details (title, location, description)
- Tag-based categorization
- Full-time job indicators

### Latest Jobs Section
- Recent job postings
- Detailed job cards
- Category tags
- Company information

### Footer Section
- Company information
- Navigation links
- Newsletter subscription
- Social media links

## 🛠️ Tech Stack

- React 18
- TypeScript
- Material UI v5
- React Router v6
- Vite

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd jobhuntly
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

## 💻 Development

### Component Structure

Each component follows this basic structure:
```typescript
/components/ComponentName/
├── index.tsx           # Main component file
└── styles.ts          # Styled components (if needed)
```

### Page Structure

Pages are composed of multiple components:
```typescript
/pages/homepage.tsx
- Hero Section
- Categories Section
- CTA Section
- Featured Jobs
- Latest Jobs
```

## 🔧 Configuration

### Environment Variables
Create a `.env` file:
```env
VITE_APP_TITLE=JobHuntly
VITE_API_URL=your_api_url
```

## 📱 Responsive Design

The application is responsive across:
- Mobile devices (< 768px)
- Tablets (768px - 1024px)
- Desktop (> 1024px)

## 🎨 Design System

### Colors
- Primary: #4F46E5 (Indigo)
- Secondary: Various colors for category tags
- Text: #111827 (Primary), #6B7280 (Secondary)
- Background: #FFFFFF, #F9FAFB

### Typography
- Font Family: Inter, system-ui
- Headings: 36px - 48px
- Body: 14px - 16px

## 📂 Assets

Required assets:
- Company logos (SVG format)
- Category icons
- Dashboard preview image


## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📝 License

This project is licensed under the MIT License.