# Complex Number Calculator 💻🔢

## Overview 📋

This is a full-stack TypeScript application that implements a complex number calculator with a React frontend and Express backend. The application is built using modern web technologies with a focus on clean architecture and developer experience. 🚀

## Screenshots 📸

### 1. Initial UI Load
![Initial UI](./assets/Screenshot%202025-07-08%20184319.png)

### 2. User Input Section
![User Input](./assets/Screenshot%202025-07-08%20184340.png)

### 3. Result Display Section
![Result Display](./assets/Screenshot%202025-07-08%20184403.png)

### 4. Final View with Output
![Final Output](./assets/Screenshot%202025-07-08%20193210.png)


## System Architecture 🛠️

### Frontend Architecture 🌐
- **Framework**: React with TypeScript ⚛️
- **UI Library**: Radix UI components with shadcn/ui design system 🎨
- **Styling**: Tailwind CSS for responsive design 💅
- **State Management**: React Hook Form for form handling, TanStack Query for server state 🗂️
- **Routing**: Wouter for client-side routing 🗺️
- **Build Tool**: Vite for development and production builds ⚙️

### Backend Architecture 🖥️
- **Runtime**: Node.js with Express.js framework 🌐
- **Language**: TypeScript with ES modules 📝
- **Database**: PostgreSQL with Drizzle ORM 🗄️
- **Session Management**: connect-pg-simple for PostgreSQL session storage 🔐
- **Development**: tsx for TypeScript execution in development 🛠️

### Database Strategy 💾
- **ORM**: Drizzle ORM for type-safe database operations 🔧
- **Database**: PostgreSQL (configured for Neon Database) 🗄️
- **Migrations**: Drizzle Kit for schema management 📊
- **Schema**: Shared schema definitions between frontend and backend 🔗

## Key Components 🛡️

### Frontend Components 🌟
- **Calculator Page**: Main interface for complex number calculations with real-time preview 📊
- **Complex Math Library**: Utilities for complex number operations (addition, subtraction, multiplication, division) 🧮
- **UI Components**: Comprehensive set of reusable components from shadcn/ui 🎨
- **Form Handling**: Zod schema validation with React Hook Form integration ✅

### Backend Components 🏗️
- **Storage Interface**: Abstracted storage layer with in-memory implementation 💾
- **API Routes**: RESTful endpoints (currently minimal setup) 🌐
- **Session Management**: PostgreSQL-backed session storage 🔐
- **Error Handling**: Centralized error handling middleware ⚠️

### Shared Components 🤝
- **Schema Definitions**: Shared database schema and validation rules 🔗
- **Type Definitions**: Common TypeScript interfaces and types 📝

## Data Flow 📥📤

1. **User Input**: User enters complex numbers in the calculator interface 👨‍💻
2. **Form Validation**: Zod schemas validate input before processing ✅
3. **Client-side Calculation**: Complex number operations performed in browser 🧮
4. **State Management**: TanStack Query manages calculation history and results 🗂️
5. **Real-time Updates**: Form inputs update preview displays instantly ⏱️
6. **History Tracking**: Calculation results stored in component state 📜

## External Dependencies 📦

### Core Dependencies 🧩
- **@neondatabase/serverless**: PostgreSQL database connectivity 🗄️
- **@radix-ui/***: Headless UI components for accessibility 🎨
- **@tanstack/react-query**: Server state management 🗂️
- **drizzle-orm**: Type-safe database operations 🔧
- **wouter**: Lightweight React router 🗺️

### Development Dependencies 🛠️
- **Vite**: Fast build tool with HMR ⚙️
- **tsx**: TypeScript execution for development 📝
- **esbuild**: Fast JavaScript bundler for production 🚀

### Third-party Services 🌐
- **Neon Database**: Serverless PostgreSQL hosting 🗄️
- **Replit**: Development environment with specialized plugins 💻

## Deployment Strategy 🚀

### Development 🛠️
- **Hot Module Replacement**: Vite provides instant updates during development ⏱️
- **TypeScript Compilation**: Real-time type checking without emit 📝
- **Database Migrations**: Drizzle Kit handles schema changes 📊
  
### Production Build 🏭
- **Frontend**: Vite builds optimized React application to `dist/public` ⚙️
- **Backend**: esbuild bundles Express server to `dist/index.js` 🚀
- **Static Assets**: Frontend assets served by Express in production 🌐

### Environment Configuration ⚙️
- **Database**: Requires `DATABASE_URL` environment variable 🗄️
- **Sessions**: PostgreSQL session store for user state 🔐
- **Build Process**: Unified build script for both frontend and backend 📜
