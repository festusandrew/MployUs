PROJECT DOCUMENTATION: MPLOYUS PLATFORM

1. EXECUTIVE OVERVIEW
MployUs is a comprehensive healthcare staffing and workforce management platform built for healthcare organizations, locum agencies, care management facilities, and recruitment enterprises. The platform provides automated scheduling, compliance tracking, AI-powered matching, locum management, and end-to-end recruitment tools designed to streamline staffing operations and reduce administrative overhead.

2. SYSTEM ARCHITECTURE AND TECH STACK
Frontend Framework: React 19 with TypeScript
Build Tool: Vite 6
Styling Engine: Tailwind CSS v4
UI Icon Set: Lucide React
Animations: Motion library
AI Integration: Google GenAI SDK (@google/genai)
Backend Infrastructure: Express server integration with Dotenv configuration

3. PROJECT STRUCTURE AND DIRECTORY LAYOUT
Root Directory:
- package.json: Dependencies, environment scripts, and project metadata.
- vite.config.ts: Vite bundler and development server configuration settings.
- tsconfig.json: TypeScript compiler configuration.
- index.html: HTML template entry point.
- .env.example: Template for required environment variables.

Source Directory (src):
- App.tsx: Root application component managing active views, modal states, and global navigation flow.
- main.tsx: React DOM root renderer and application entry point.
- types.ts: TypeScript interfaces and type definitions for state, navigation, modules, and case studies.
- index.css: Global CSS rules and Tailwind imports.
- components: Visual components categorized into core landing sections, dedicated service pages, and interactive dialog modals.

4. CORE LANDING COMPONENTS
Navbar Component:
Handles top-level navigation, product section links, service page switching, view state management, and primary calls-to-action for demo booking and trial registration.

Hero Component:
Presents primary value propositions, dynamic preview cards, interactive feature tabs, and primary action triggers.

Social Proof Component:
Displays partner organization logos, user testimonials, enterprise metrics, and social validation elements.

Problem Statement Component:
Illustrates traditional healthcare recruitment challenges versus modern automated solution workflows.

Solution Overview Component:
Comprehensive breakdown of core platform capabilities including locum management, care coordination, and candidate placement.

Product Modules Component:
Interactive grid displaying individual software modules with detail modal view triggers.

Features Grid Component:
Visual grid highlighting key technical features such as automated compliance checks and real-time shift scheduling.

Benefits Component:
Quantitative and qualitative benefits structured for administrators, staff, and healthcare providers.

Pricing Component:
Structured pricing tiers and feature comparison breakdowns.

FAQ Component:
Interactive accordion providing answers to frequently asked questions regarding platform onboarding, security, and integration.

Final CTA Component:
Conversion section offering quick access to demo scheduling and free trial access.

Footer Component:
Site-wide links, legal notices, contact information, and newsletter subscription forms.

5. DEDICATED SERVICE PAGES (src/components/pages)
Care Management Page:
Dedicated view focused on residential care, home care, and nursing home staff scheduling and shift management.

Locum Provision Page:
Specialized page covering temporary healthcare staffing, locum doctor placement, and emergency shift coverage workflows.

Product Design Page:
Showcases UI/UX design services and custom software design tailored specifically for healthcare software.

Recruitment Service Page:
Presents full-service managed recruitment and talent acquisition solutions.

Recruitment Software Page:
Details applicant tracking system capabilities, candidate pipelines, and automated hiring workflows.

Web Development Page:
Outlines technical web application engineering services for medical and staffing enterprises.

6. INTERACTIVE MODAL DIALOGS (src/components/modals)
Book Demo Modal:
Multi-step interactive form enabling visitors to request personalized platform demonstrations.

Free Trial Modal:
Registration dialog for requesting instant access to evaluation accounts.

Video Modal:
Embedded video player presenting platform feature walk-throughs and demonstrations.

Case Study Modal:
Detailed case study viewer showcasing client implementation metrics and operational results.

Module Detail Modal:
In-depth modal window breaking down specific platform modules and feature specifications.

7. DATA MODELS AND TYPES (src/types.ts)
Navigation Types:
Defines ActiveTab and PageView state values for smooth single-page navigation.

Module Types:
Structural definitions for software feature modules including title, description, key benefits, and technical specifications.

Case Study Types:
Structure for metrics, testimonial quotes, and client profiles.

Form Types:
Data definitions for demo requests, trial signups, and inquiry submissions.

8. DEVELOPMENT AND EXECUTION INSTRUCTIONS
Prerequisites:
Node.js (version 18 or higher recommended) and npm package manager.

Starting Development Server:
Run command: npm run dev
Starts the local development server on port 3000 with host binding.

Building for Production:
Run command: npm run build
Compiles TypeScript and bundles static assets into the dist folder.

TypeScript Type Checking:
Run command: npm run lint
Executes TypeScript compiler verification without emitting build output.

Previewing Production Build:
Run command: npm run preview
Serves the compiled production bundle locally for testing.

9. REPOSITORY AND SOURCE CONTROL
Git Remote: https://github.com/festusandrew/MployUs.git
Target Branch: main
