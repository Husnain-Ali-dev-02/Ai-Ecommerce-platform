🛍️ AI-Powered E-Commerce Ecosystem
A bleeding-edge E-commerce platform built with the latest React 19 and Next.js 15 features. This project integrates an AI Agentic layer using the Vercel AI SDK and Clerk Agent Toolkit to provide a truly intelligent shopping experience.

🚀 Technical Highlights
1-AI Agent Architecture: Powered by @ai-sdk/openai and @ai-sdk/cohere, featuring a smart assistant that doesn't just talk but interacts with your store's logic.

2-Headless Commerce: Utilizes Sanity CMS as a powerful content backend with full Typegen support for end-to-end type safety.

3-Next-Gen Performance: Uses the React Compiler (Babel plugin) and Biome for lightning-fast builds and ultra-clean code formatting.

4-State Management: Lightweight and reactive state handling using Zustand.

5-Server Actions & Agents: Leveraging @clerk/agent-toolkit for secure, AI-driven user interactions.

🛠️ Tech Stack
Frontend & UI
1-Framework: Next.js 15 (App Router), React 19

2-Styling: Tailwind CSS 4, Radix UI primitives, Lucide Icons

3-Components: Embla Carousel (for smooth product sliders), Sonner (for sleek notifications)

4-Animation: Framer Motion (via tw-animate-css)

5-Backend & Data
Content: Sanity.io (Headless CMS)

6-Authentication: Clerk (Advanced Agent-compatible auth)

7-Payments: Stripe

8-Validation: Zod

9-AI Layer
SDK: Vercel AI SDK (React hooks & Provider logic)

10-Models: OpenAI & Cohere integration

11-Formatting: React Markdown for AI-generated responses

📂 Project Structure
sanity/: Advanced schema definitions and content structures.

components/: Radix-based UI components (Alerts, Dialogs, Selects, etc.).

hooks/: Custom Zustand stores and AI SDK implementations.

⚙️ Installation & Setup
Clone & Install:

Bash

git clone https://github.com/Husnain-Ali-dev-02/Ai-Ecommerce-platform.git
npm install
Generate Sanity Types:

Bash

npm run typegen
Environment Variables: Create a .env file with:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY

SANITY_API_READ_TOKEN

OPENAI_API_KEY / COHERE_API_KEY

STRIPE_SECRET_KEY

Dev Mode:

Bash

npm run dev
🧹 Code Quality
1-This project uses Biome for linting and formatting, ensuring a high standard of code consistency without the overhead of ESLint/Prettier.

2-What makes this "Top-Notch"?
Identifies React 19/Next 15: This shows you are an early adopter of the latest tech.

3-AI-SDK Specifics: It mentions Cohere and OpenAI, which are explicitly in your dependencies.

4-Sanity Typegen: It includes the typegen script, which is crucial for professional Sanity workflows.

5-Biome/React Compiler: Highlighting these shows you care about modern tooling and performance.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
