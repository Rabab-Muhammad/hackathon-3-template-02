Avion - E-Commerce Platform

Overview

Avion is a modern e-commerce platform specializing in furniture and unique decor items. Built using Next.js, Tailwind CSS, and shadcn/ui, the platform ensures a seamless shopping experience with a fully responsive design. The backend is managed using Sanity CMS, with additional integrations for product data APIs, third-party services, shipment tracking, and payment processing.

Project Structure

The project follows a structured folder hierarchy for better organization and scalability:

Avion/

│-- src/

│   │-- components/ 
 # Reusable UI components

│   │-- pages/     
  # Next.js pages

│   │-- styles/   
   # Tailwind CSS styles

│   │-- utils/
       # Utility functions

│-- public/    
      # Static assets

│-- tests/   
        # Test cases and performance reports

│-- .env.example 
    # Sample environment variables

│-- README.md
        # Project documentation


Deployment Steps


To deploy the project in a staging environment, follow these steps:

Clone the Repository

git clone (https://github.com/Rabab-Muhammad/hackathon-3-template-02.git)

cd hackathon-3-template-02

Install Dependencies

npm install

Configure Environment Variables

Copy .env.example to .env.local and update necessary API keys.

Run the Project Locally

npm run dev

Deploy to Staging (Vercel)

vercel --prod

Environment Variables

Ensure the following variables are correctly set in .env.local:

NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id

NEXT_PUBLIC_SANITY_DATASET=production



NEXT_PUBLIC_API_Token

NEXT_PUBLIC_PAYMENT_GATEWAY_KEY=your_payment_key


Testing & Performance Reports

The project undergoes rigorous testing before deployment. The following tests have been conducted:

✅ Unit Tests: Ensuring individual functions work correctly.

✅ Integration Tests: Validating component interactions.

✅ Performance Tests: Checking page load speed and optimization.

✅ Security Tests: Ensuring API keys and sensitive data are secure.

Reports are stored in the tests/ folder for future reference.

GitHub Repository

All project files and documentation are organized and maintained in a GitHub repository:

📌 Repository URL: GitHub -https://github.com/Rabab-Muhammad/hackathon-3-template-02.git

Conclusion

This README serves as a complete guide to the project setup, deployment, and testing process. With a fully deployed staging environment and structured documentation, ShopSphere is now ready for the next phase of development and launch.

🔹 Developed by: Rabab
🔹 Tech Stack: Next.js, Tailwind CSS, shadcn/ui, Sanity CMS

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
