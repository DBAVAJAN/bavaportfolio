# Portfolio Website

A modern personal portfolio built with React, TypeScript, Vite, Tailwind CSS, and shadcn/ui. This project presents a clean and responsive profile for showcasing education, skills, certifications, projects, internships, and contact information.

## Overview

This portfolio is designed to help highlight:

- Academic background and education
- Technical skills and strengths
- Professional certifications
- Internship and work experience
- Featured projects and achievements
- Additional interests and extracurricular activities
- Contact details for opportunities and networking

## Features

- Responsive single-page portfolio layout
- Smooth section navigation and scroll behavior
- Modern card-based UI and reusable components
- Light theme styling with polished visual design
- Structured sections for professional storytelling
- Mobile-friendly design for smaller screens
- Built with scalable component architecture

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- React Router DOM
- Lucide React icons
- TanStack Query

## Project Structure

```bash
src/
├── components/
│   ├── ui/
│   ├── Header.tsx
│   ├── HomeSection.tsx
│   ├── EducationSection.tsx
│   ├── SkillsSection.tsx
│   ├── CertificationsSection.tsx
│   ├── InternshipSection.tsx
│   ├── ProjectsSection.tsx
│   ├── ExtrasSection.tsx
│   └── ContactSection.tsx
├── contexts/
├── hooks/
├── lib/
├── pages/
├── App.tsx
├── main.tsx
├── index.css
└── App.css
```

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js 18+
- npm or yarn

### Installation

```bash
npm install
```

### Run locally

```bash
npm run dev
```

Then open the local Vite URL shown in the terminal, usually:

```bash
http://localhost:5173
```

### Production build

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

## Scripts

- `npm run dev` - starts the development server
- `npm run build` - creates the production build
- `npm run preview` - previews the built app locally
- `npm run lint` - runs ESLint for code quality checks

## Notes

This project can be customized by updating the section content in the components under `src/components/` and by adjusting theme, colors, and layout settings in the Tailwind configuration and CSS files.

## License

This project is for personal portfolio use and may be adapted for your own site or portfolio as needed.
