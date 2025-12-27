# StoreIt - Cloud Storage Platform

StoreIt is a comprehensive cloud storage platform that enables users to securely upload, manage, share, and organize their files. The application provides a seamless experience for handling various file types including documents, images, videos, and audio files, with a focus on performance, security, and user experience.

## Core Features

### File Management

• Upload files up to 50MB with drag-and-drop support

• Real-time file processing and thumbnail generation

• Advanced search and filtering capabilities

• Sort files by date, name, or size

• Rename, delete, and download files

• File sharing with granular access control

### User Experience

• Responsive design optimized for all devices

• Interactive dashboard with storage analytics

• Visual storage usage breakdown with charts

• Recently uploaded files quick access

• Type-based file organization (Documents, Images, Media, Others)

### Security & Authentication

• Email-based OTP authentication

• Session management with secure cookies

• User-specific file access control

• Shared file permissions system

## Technical Stack

### Frontend Technologies

• Next.js 15: React framework with App Router for server-side rendering and optimal performance

• TypeScript: Type-safe development ensuring code reliability and maintainability

• React 19: Latest React features for building interactive user interfaces

• TailwindCSS: Utility-first CSS framework for responsive design

• shadcn/ui: High-quality, accessible component library built on Radix UI

• Recharts: Data visualization library for storage analytics

### Backend & Infrastructure

• Appwrite: Backend-as-a-Service for authentication, database, and storage

• Node Appwrite SDK: Server-side integration with Appwrite services

• Next.js Server Actions: Server-side data mutations and API routes

### Form Handling & Validation

• React Hook Form: Performant form state management

• Zod: TypeScript-first schema validation

• @hookform/resolvers: Integration between React Hook Form and Zod

### UI/UX Libraries

• Radix UI: Unstyled, accessible component primitives

• React Dropzone: Drag-and-drop file upload functionality

• Lucide React: Consistent icon system

• class-variance-authority: Type-safe component variants

• tailwind-merge: Intelligent Tailwind class merging

## Key Technical Implementations

### Authentication Flow

• Email-based passwordless authentication using Appwrite's token system

• OTP verification with 6-digit codes

• Secure session management with HTTP-only cookies

• User profile creation and management

### File Operations

• Multipart file upload with InputFile API

• Automatic file type detection and categorization

• Cloud storage integration with Appwrite Storage

• Database document creation for file metadata

• Revalidation paths for immediate UI updates

### State Management

• Server-side data fetching with Next.js App Router

• Client-side state with React hooks

• Form state management with React Hook Form

• Toast notifications for user feedback

### Data Operations

• Server actions for secure backend operations

• Query optimization with Appwrite Query API

• Conditional queries based on user permissions

• Parallel data fetching for dashboard metrics

## Performance Optimizations

• Server-side rendering for fast initial page loads

• Image optimization with Next.js Image component

• Code splitting and lazy loading

• Debounced search inputs to reduce API calls

• Efficient file type filtering and sorting

• Turbopack for faster development builds

## Security Measures

• Server-side authentication validation

• HTTP-only secure cookies

• CSRF protection with SameSite cookies

• User-scoped database queries

• File access control based on ownership and sharing

• Environment variable protection for sensitive keys

## Responsive Design

• Mobile-first approach with TailwindCSS

• Adaptive navigation (sidebar for desktop, sheet for mobile)

• Touch-optimized file interactions

• Responsive grid layouts for file cards

• Viewport-aware chart rendering
