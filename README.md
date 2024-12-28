## Technologies Used

- **Next.js**: React-based framework for fast, server-side rendered applications.
- **Prismic CMS**: Headless CMS used to manage dynamic content.
- **Three.js**: 3D JavaScript library to render the soda can and other 3D elements.
- **Tailwind CSS**: Utility-first CSS framework for responsive design.
- **GSAP (GreenSock Animation Platform)**: High-performance animations for smooth transitions and interactions.
- **Zustand**: Lightweight state management for React.
- **Vercel**: Deployment platform optimized for Next.js applications.

---

## Setup & Installation

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (version 16 or above)
- Git
- Prismic account

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/codedalex/fizzi-3d-website.git
   cd fizzi-3d-website
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Create a `.env.local` file:**

   Set up your environment variables for Prismic and Vercel:

   ```bash
   NEXT_PUBLIC_PRISMIC_ENDPOINT=<Your Prismic API URL>
   PRISMIC_ACCESS_TOKEN=<Your Prismic Access Token>
   ```

4. **Start the development server:**

   ```bash
   npm run dev
   ```

5. **Access the site:**

   Visit `http://localhost:3000` in your browser to see the site live.

---