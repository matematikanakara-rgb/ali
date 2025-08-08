# Insurance Policy Management System

## Overview

This is a full-stack insurance policy management system built with React, Express, and PostgreSQL. The application provides role-based access control for insurance employees and managers, enabling them to track policies, monitor performance metrics, and manage customer data. The system features a modern UI built with shadcn/ui components and implements comprehensive policy lifecycle management with performance analytics.

## User Preferences

Preferred communication style: Simple, everyday language.
Development approach: Focus on core functionality first, advanced AI features to be added in future updates.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite for development and production builds
- **UI Library**: shadcn/ui components built on Radix UI primitives
- **Styling**: Tailwind CSS with custom design tokens and CSS variables
- **State Management**: TanStack React Query for server state management
- **Routing**: Wouter for client-side routing
- **Form Handling**: React Hook Form with Zod schema validation

### Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules
- **API Design**: RESTful API with role-based route protection
- **Authentication**: Replit Auth integration with OpenID Connect
- **Session Management**: Express sessions with PostgreSQL store
- **Request Logging**: Custom middleware for API request/response logging

### Data Storage Solutions
- **Primary Database**: PostgreSQL with connection pooling via Neon serverless
- **ORM**: Drizzle ORM for type-safe database queries and migrations
- **Schema Management**: Centralized schema definitions with Zod validation
- **Session Storage**: PostgreSQL-backed session store for authentication persistence

### Authentication and Authorization
- **Provider**: Replit Auth with OIDC integration
- **Strategy**: Passport.js with custom OpenID Connect strategy
- **Role System**: Employee and Manager roles with hierarchical permissions
- **Session Security**: Secure HTTP-only cookies with CSRF protection
- **Route Protection**: Middleware-based authentication checks for API endpoints

### Core Data Models
- **Users**: Profile management with role-based access (employee/manager)
- **Policies**: Complete policy lifecycle with customer information and status tracking
- **Insurance Types**: Dynamic insurance type management with admin protection
- **Performance Metrics**: Monthly performance tracking per user with aggregated statistics
- **Manager Notes**: Employee note system with persistent/temporary options
- **Activity Logs**: Comprehensive audit trail for all system actions
- **Quotes**: Daily motivational quotes system for employee engagement
- **Admin Settings**: Secure admin password management system

### Application Features
- **Policy Management**: Full CRUD operations with status tracking and expiration monitoring
- **Performance Dashboard**: Role-based dashboards with metrics visualization and charts
- **Team Management**: Manager oversight with note system and policy distribution
- **Dynamic Insurance Types**: Admin-protected insurance type management system
- **Motivational System**: Daily quotes for employee engagement
- **Activity Tracking**: Comprehensive audit trail for all system actions
- **Mobile PWA**: Full mobile compatibility with offline support and home screen installation
- **Admin Security**: 4-digit PIN protection for administrative functions
- **Manager Notes**: Persistent and temporary note system for employee management
- **Responsive Design**: Mobile-first responsive interface optimized for all devices

## External Dependencies

### Core Framework Dependencies
- **React Ecosystem**: React 18, React DOM, React Hook Form, TanStack React Query
- **UI Components**: Radix UI primitives, Lucide icons, shadcn/ui component library
- **Styling**: Tailwind CSS, class-variance-authority, clsx utilities
- **TypeScript Support**: Full TypeScript integration with strict type checking

### Backend Services
- **Database**: Neon PostgreSQL serverless database with connection pooling
- **Authentication**: Replit Auth service with OpenID Connect protocol
- **Session Store**: PostgreSQL-backed session storage via connect-pg-simple

### Development Tools
- **Build System**: Vite with React plugin and TypeScript support
- **Database Tools**: Drizzle Kit for migrations and schema management
- **Code Quality**: ESBuild for production bundling, TSX for development runtime
- **PWA Tools**: Service Worker implementation for offline functionality
- **Mobile Optimization**: Safe area handling and touch-friendly interfaces
- **Replit Integration**: Cartographer plugin and runtime error overlay for development

## Project Status

### ✅ COMPLETED PROJECT - January 2025

#### Final Implementation Features:
- ✓ Complete insurance policy management system with CRUD operations
- ✓ Role-based authentication system (Manager/Employee roles)
- ✓ Dynamic insurance types management with 4-digit admin PIN protection
- ✓ Manager notes system (persistent/temporary, 200 character limit)
- ✓ Performance tracking and analytics dashboard
- ✓ Daily motivational quotes system for employee engagement
- ✓ Full mobile PWA implementation with offline support
- ✓ iOS/Android safe area handling and native app experience
- ✓ Touch-optimized interface with accessibility compliance
- ✓ Service worker for caching and offline functionality
- ✓ Home screen installation capability
- ✓ Comprehensive activity logging and audit trail

#### Technical Achievement:
- ✅ Production-ready build system
- ✅ Zero LSP diagnostics/errors
- ✅ Full mobile compatibility (web/Android/iOS)
- ✅ PostgreSQL database with Drizzle ORM
- ✅ Replit Auth integration with secure sessions
- ✅ PWA manifest and service worker implementation
- ✅ Responsive design across all device sizes

#### System Status: **READY FOR DEPLOYMENT**
- Build: ✅ Successful
- Tests: ✅ All features functional
- Preview: ✅ Working correctly
- Database: ✅ Schema synchronized
- Mobile: ✅ PWA fully operational

#### Future Enhancements (Next Phase):
- AI-powered insurance recommendation engine
- Advanced reporting and export capabilities
- Email/SMS notification system
- Multi-language support

### Validation and Utilities
- **Schema Validation**: Zod for runtime type validation and form schemas
- **Date Handling**: date-fns for date manipulation and formatting
- **Performance**: Memoizee for function memoization and caching
- **Development**: WebSocket support for Neon database connections