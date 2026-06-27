# CPU Scheduling Simulator

An interactive, visual CPU scheduling simulator built with React, TypeScript, and Tailwind CSS. This application allows users to simulate and compare various CPU scheduling algorithms with real-time visualization, performance metrics, and animated Gantt charts.

## Features

- **Multiple Scheduling Algorithms** — Simulate FCFS, SJF (Preemptive & Non-preemptive), Priority Scheduling, and Round Robin
- **Interactive Process Management** — Add, edit, and remove processes with arrival time, burst time, and priority
- **Real-time Gantt Chart** — Visualize CPU execution timeline with animated transitions
- **Performance Metrics** — Calculate and display average waiting time, turnaround time, and CPU utilization
- **Responsive Design** — Fully responsive UI built with Tailwind CSS and shadcn/ui components
- **Smooth Animations** — Powered by Framer Motion for engaging user interactions
- **Data Visualization** — Charts and graphs using Recharts for metric comparison

## Tech Stack

- **Framework:** React 19 + TypeScript
- **Build Tool:** Vite
- **Styling:** Tailwind CSS + shadcn/ui (New York style)
- **Animations:** Framer Motion
- **Charts:** Recharts
- **State Management:** React Query (TanStack Query)
- **Forms:** React Hook Form + Zod validation
- **Icons:** Lucide React + React Icons
- **Routing:** Wouter

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm, yarn, or pnpm

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd cpu-scheduler
Install dependencies:
bash
npm install
Set required environment variables:
bash
export PORT=3000
export BASE_PATH=/
Start the development server:
bash
npm run dev
Open your browser and navigate to http://localhost:3000
Available Scripts
Table
Script	Description
npm run dev	Start the Vite development server with HMR
npm run build	Build the project for production
npm run serve	Preview the production build locally
npm run typecheck	Run TypeScript type checking without emitting files
Project Structure
plain
cpu-scheduler/
├── src/
│   ├── components/          # React components
│   │   └── ui/             # shadcn/ui components (buttons, inputs, dialogs, etc.)
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # Utility functions and helpers
│   ├── main.tsx            # Application entry point
│   └── index.css           # Global styles and Tailwind directives
├── index.html              # HTML entry point
├── vite.config.ts          # Vite configuration
├── tsconfig.json           # TypeScript configuration
├── components.json         # shadcn/ui configuration
└── package.json            # Dependencies and scripts
Key Dependencies
@radix-ui/ — Unstyled, accessible UI primitives (dropdowns, dialogs, sliders, etc.)
recharts — Composable charting library for metrics visualization
framer-motion — Production-ready motion library for animations
@tanstack/react-query — Powerful data synchronization and caching
react-hook-form — Performant, flexible form handling
zod — TypeScript-first schema validation
lucide-react — Beautiful, consistent icon set
wouter — Minimalist routing for React
Configuration
shadcn/ui
The project uses the New York style with neutral base colors and CSS variables. Components are aliased under @/components/ui and utilities under @/lib/utils.
Path Aliases
@/ → ./src/
@assets/ → ../../attached_assets/
Environment Variables
Table
Variable	Required	Description
PORT	Yes	Development/preview server port
BASE_PATH	Yes	Base URL path for the application
NODE_ENV	No	Set to production to disable Replit dev plugins
REPL_ID	No	Replit environment identifier (auto-detected)


