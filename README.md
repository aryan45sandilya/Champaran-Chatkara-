# 🍛 Champaran Chatkara

A modern, full-featured restaurant website for authentic Bihari cuisine, bringing the traditional flavors of Champaran to the digital world.

![Next.js](https://img.shields.io/badge/Next.js-16.1.6-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-19.2.4-blue?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-blue?style=flat-square&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.1-38bdf8?style=flat-square&logo=tailwind-css)

## 📖 About

Champaran Chatkara is a family-owned restaurant serving authentic Bihari dishes for over 25 years. Located in Kaushambi, Ghaziabad, we specialize in traditional recipes passed down through generations, featuring signature dishes like Litti Chokha and Champaran Mutton.

This website provides a modern digital presence with an admin panel for managing menu items, categories, and best sellers.

## ✨ Features

- 🏠 **Modern Landing Page** - Beautiful hero section with restaurant information
- 📱 **Responsive Design** - Fully responsive across all devices
- 🍽️ **Dynamic Menu System** - Browse menu items by categories
- 👨‍💼 **Admin Dashboard** - Manage menu items, categories, and best sellers
- 🖼️ **Image Management** - Upload and crop images with Firebase Storage
- 🔐 **Authentication** - Secure admin login system
- 🎨 **Beautiful UI** - Built with Radix UI and Tailwind CSS
- 📊 **Database Integration** - Supabase for data management
- 🤖 **AI Integration** - Google Genkit for AI-powered features

## 🛠️ Tech Stack

### Frontend
- **Framework:** Next.js 16.1.6 (with Turbopack)
- **UI Library:** React 19.2.4
- **Language:** TypeScript 5.9.3
- **Styling:** Tailwind CSS 3.4.1
- **UI Components:** Radix UI
- **Forms:** React Hook Form + Zod validation
- **Icons:** Lucide React

### Backend & Services
- **Database:** Supabase
- **Storage:** Firebase Storage
- **AI:** Google Genkit
- **Authentication:** Custom auth with Supabase

### Development Tools
- **Package Manager:** npm
- **Linting:** ESLint
- **Type Checking:** TypeScript

## 🚀 Getting Started

### Prerequisites

- Node.js 20+ installed
- npm or yarn package manager
- Supabase account and project
- Firebase project for storage

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Champaran-Chatkara-Website.git
   cd Champaran-Chatkara-Website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env.local` file in the root directory:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to [http://localhost:9002](http://localhost:9002)

## 📜 Available Scripts

- `npm run dev` - Start development server on port 9002 with Turbopack
- `npm run build` - Build the production application
- `npm start` - Start the production server
- `npm run lint` - Run ESLint for code quality
- `npm run typecheck` - Run TypeScript type checking
- `npm run genkit:dev` - Start Genkit AI development server
- `npm run genkit:watch` - Start Genkit with watch mode
- `npm run seed:menu` - Seed menu data to database
- `npm run seed:simple` - Seed simplified menu data

## 📁 Project Structure

```
Champaran-Chatkara-Website/
├── src/
│   ├── app/                    # Next.js app directory
│   │   ├── admin/             # Admin dashboard pages
│   │   ├── menu/              # Menu page
│   │   └── page.tsx           # Landing page
│   ├── components/            # React components
│   │   ├── admin/            # Admin-specific components
│   │   ├── landing/          # Landing page sections
│   │   └── ui/               # Reusable UI components
│   ├── contexts/             # React contexts
│   ├── data/                 # Static data files
│   ├── hooks/                # Custom React hooks
│   ├── lib/                  # Utility functions and configs
│   └── ai/                   # AI/Genkit integration
├── public/                   # Static assets
└── package.json             # Project dependencies
```

## 🍽️ Restaurant Specialties

- Authentic Bihari recipes with 25+ years of experience
- Traditional cooking methods using clay pots and slow fire
- Fresh ingredients sourced locally from Bihar
- Family-friendly atmosphere with warm hospitality
- Signature dishes prepared with generations of love

## 🔐 Admin Access

The admin dashboard is protected and requires authentication. Access it at `/admin/login` to manage:
- Menu items (add, edit, delete)
- Categories
- Best sellers
- Image uploads

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

**Champaran Chatkara**
- 📍 Location: Kaushambi, Ghaziabad
- 📞 Phone: [Your Phone Number]
- 📧 Email: [Your Email]

---

*Experience the authentic taste of Bihar at Champaran Chatkara - where every bite feels like home-cooked love.* ❤️
