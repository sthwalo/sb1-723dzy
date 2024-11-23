# African Health Excellence Organisation (AHEO) Website

A modern, responsive website for the African Health Excellence Organisation built with React, TypeScript, and Tailwind CSS.

## Story Points & Development Phases

### Phase 1: Project Setup and Core Infrastructure (8 points)
- [x] Initialize React + TypeScript project with Vite
- [x] Configure Tailwind CSS and theme colors
- [x] Set up ESLint and TypeScript configurations
- [x] Implement basic routing structure
- [x] Create reusable component architecture

### Phase 2: Navigation and Layout (13 points)
- [x] Design and implement responsive navbar
- [x] Create dropdown menu system
- [x] Build footer component with social links
- [x] Implement mobile menu functionality
- [x] Add smooth scrolling to sections

### Phase 3: Home Page and Hero (8 points)
- [x] Design hero section with dynamic background
- [x] Create events slider component
- [x] Implement features section
- [x] Add partners showcase
- [x] Optimize responsive layouts

### Phase 4: Awards System (21 points)
- [x] Build awards categories page
- [x] Create nomination form system
- [x] Implement voting interface
- [x] Design winners showcase
- [x] Add SMS and email voting integration
- [x] Create category descriptions
- [x] Implement voting modal

### Phase 5: Medical Events (13 points)
- [x] Design events listing page
- [x] Create event registration system
- [x] Implement countdown timer
- [x] Add CPD information section
- [x] Build event details components

### Phase 6: About and Contact (8 points)
- [x] Design about page with organization info
- [x] Create board members showcase
- [x] Implement contact form
- [x] Add location and contact details
- [x] Create WhatsApp integration

### Phase 7: Gallery and Media (8 points)
- [x] Build responsive gallery grid
- [x] Implement image modal viewer
- [x] Add category filtering
- [x] Create image lazy loading
- [x] Optimize image delivery

### Phase 8: Testing and Optimization (13 points)
- [ ] Implement unit tests
- [ ] Add integration tests
- [ ] Perform accessibility audit
- [ ] Optimize performance
- [ ] Add error boundaries
- [ ] Implement loading states
- [ ] Add form validation

## Features

### 1. Awards System
- Complete awards categories showcase
- Nomination system
- Voting platform for finalists
- Past winners gallery
- Honorary and voted categories

### 2. Medical Events
- Event registration system
- CPD-accredited events listing
- Upcoming events showcase
- Event countdown timer

### 3. Interactive Components
- Dynamic navigation with dropdown menus
- Responsive image galleries
- Modal dialogs for voting
- Contact forms with validation

### 4. Key Pages
- Home
- Awards/Summit
- Our Partners
- Medical Events
- About
- Finalists
- Gallery
- Contact

## Technology Stack

- **Frontend Framework:** React 18.3
- **Type System:** TypeScript
- **Styling:** Tailwind CSS
- **Routing:** React Router v6
- **Icons:** Lucide React
- **Build Tool:** Vite
- **Linting:** ESLint

## Project Structure

```
src/
├── components/         # Reusable UI components
│   ├── Hero.tsx
│   ├── Navbar.tsx
│   ├── Footer.tsx
│   ├── EventsSlider.tsx
│   └── ...
├── pages/             # Page components
│   ├── Home.tsx
│   ├── Awards/
│   ├── Partners.tsx
│   ├── MedicalEvents/
│   └── ...
└── App.tsx            # Main application component
```

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/aheo-website.git
```

2. Install dependencies:
```bash
cd aheo-website
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## Color Scheme

- Primary: #962326 (Burgundy)
- Secondary: #F2C849 (Gold)
- Accent: #A7864B (Bronze)
- Dark: #2B2A29 (Charcoal)

## Development Guidelines

### Code Style
- Use TypeScript for all components
- Follow React best practices and hooks
- Implement proper error handling
- Write meaningful component documentation
- Use proper TypeScript types and interfaces

### Component Structure
- Create reusable components
- Implement proper prop typing
- Use proper file and folder organization
- Follow single responsibility principle

### Performance
- Implement code splitting
- Use proper image optimization
- Implement lazy loading
- Minimize bundle size
- Use proper caching strategies

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Security Considerations

- Form validation
- Protected routes
- Secure contact forms
- Data encryption
- Input sanitization

## Contact

For any queries or support, please contact:
- Email: info@aheo.org
- Phone: +27 12 345 6789

## License

This project is licensed under the MIT License.