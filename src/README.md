# Source Directory Structure

This directory contains the organized source code for the Next.js application.

## Directory Overview

```
src/
├── actions/          # Server actions for data mutations
│   ├── auth.action.ts
│   └── article.action.ts
├── app/              # Next.js App Router pages and routes
├── assets/           # Static assets (images, fonts, etc.)
├── components/       # Reusable UI components
├── hooks/            # Custom React hooks
├── layouts/          # Layout components (Sidebar, Navbar, Footer, etc.)
├── sections/         # Feature-specific sections
│   └── article/
│       ├── components/  # Article-specific components
│       ├── view/        # Article views/pages
│       └── index.ts     # Article section exports
├── styles/           # Global styles and CSS files
├── utils/            # Utility functions and helpers
└── _mock/            # Mock data for development/testing
```

## Guidelines

- **actions/**: Place all server actions here (Next.js Server Actions)
- **components/**: Shared, reusable components used across the app
- **layouts/**: Layout-related components (headers, footers, sidebars)
- **sections/**: Feature-specific code organized by domain
- **styles/**: Global CSS, theme files, and style utilities
- **utils/**: Helper functions, constants, and utilities
- **_mock/**: Mock data for development and testing purposes
