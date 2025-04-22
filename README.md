# EduEquityAnalytics

**EduEquityAnalytics** is a web application developed during the JPMorgan Chase **Data for Good Hackathon** to support the **National Education Equity Lab** in expanding their educational programs to Title I and Title II schools in underserved regions.

The platform analyzes extensive datasets related to student enrollment, course performance, success rates, drop rates, and more — providing actionable insights to enhance program reach and effectiveness.

---

## 🚀 Features

- **Interactive Dashboard**: Offers multiple visualization types (charts, graphs, etc.) for intuitive data exploration.
- **Data Tables**: Structured views for detailed dataset inspection.
- **Analytics Page**: In-depth statistical analysis and trends to inform strategic decisions.
- **Responsive Design**: Features a collapsible sidebar for optimal usability across devices.
- **Dark/Light Theme Support**: Enhances user experience with customizable visual themes.

---

## 🛠 Tech Stack

- **React 18**: Frontend framework for building dynamic user interfaces.
- **TypeScript**: Ensures type safety and improved code maintainability.
- **Material UI (MUI)**: Provides a modern, accessible component library for consistent UI design.
- **React Router**: Enables seamless navigation between dashboard, tables, and analytics pages.
- **Vite**: High-performance build tool for fast development and optimized production builds.

---

## 🎯 Purpose

This project aims to empower the **National Education Equity Lab** with data-driven strategies to promote educational equity by identifying opportunities for program expansion in underserved communities.

---


## Getting Started

## 📦 Installation

1. Clone the repository
   ```
   git clone https://github.com/<your-username>/EduEquityAnalytics.git
   ```
   
2. Navigate to the project directory:
   ```
   cd EduEquityAnalytics
   ```
3. Install dependencies
   ```
   # In the main folder
   npm install
   
   # Navigate to the dashboard folder
   cd data-analytics-dashboard
   npm install
   ```

### Running the Application

1. Start the development server
   ```
   cd data-analytics-dashboard
   npm run dev
   ```
   or
   ```
   cd data-analytics-dashboard
   npx vite
   ```

2. Open your browser and navigate to `http://localhost:5173`

## Project Structure

```
data-analytics-dashboard/
├── src/
│   ├── assets/          # Static assets like images, icons
│   ├── components/      # Reusable UI components
│   ├── pages/           # Page components
│   ├── App.tsx          # Main application component
│   ├── main.tsx         # Application entry point
│   └── index.css        # Global styles
├── index.html           # HTML template
├── tsconfig.json        # TypeScript configuration
└── package.json         # Project dependencies and scripts
```

## Development

### Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run preview` - Preview the production build locally
