## Project Structure

nexademy/  
├── src/  
│   ├── app/  
│   │   ├── (_role)/  
│   │   │   ├── dashboard/  
│   │   │   │   └── *page.tsx*  
│   │   │   └── *layout.tsx*  
│   ├── components/  
│   │   ├── ui/  
│   │   │   └── *button.tsx*  
│   ├── services/  
│   │   ├── *dashboard.service.ts*  
│   │   └── *api.ts*  
│   ├── lib/  
├── *middleware.ts*  
├── *next.config.js*  
├── *tsconfig.json*  
├── *package.json*  




### Key Directories

- **src/app/**
  - Core of the application, organized by roles.
  - _role/: Placeholder for user-specific roles (e.g., admin, user).
    - **dashboard/**: Contains pages and features related to user dashboards.
    - **layout.tsx**: Defines the layout for the role.

- **src/components/**
  - Reusable UI components for the application.
  - Example: ui/button.tsx contains the button component.

- **src/services/**
  - Centralized services for API handling and business logic.
  - **dashboard.service.ts**: Contains logic for dashboard interactions.
  - **api.ts**: Centralized API configuration.

- **src/lib/**
  - Utility functions and shared libraries.

- **Root Files**
  - **middleware.ts**: Middleware configuration for handling custom logic.
  - **next.config.js**: Next.js configuration.
  - **tsconfig.json**: TypeScript configuration for type checking.
  - **package.json**: Dependencies and scripts for the project.

## Role-Driven Zoning Principles

1. **Role-based:** The application is divided into modules specific to user roles.
2. **Zoning:** Features and components are isolated into dedicated zones for better maintainability.
3. **Scalability:** New roles, components, or services can be added with minimal refactoring.

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
