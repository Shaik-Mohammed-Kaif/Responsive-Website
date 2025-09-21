# Gourmet Delight – Modern Restaurant Website

**Developed by:** S Mohammed Kaif  
**GitHub URL:** [[https://github.com/Shaik-Mohammed-Kaif/Gourmet-Delight](https://github.com/Shaik-Mohammed-Kaif/Responsive-Website)]
**Live Demo:** [https://gourmet-delight-dining.lovable.app/](https://gourmet-delight-dining.lovable.app/)

---

## Project Info

**Description:**  
Gourmet Delight is a modern, fully-responsive restaurant website built with React, TypeScript, Tailwind CSS, and shadcn-ui.  
It features a beautifully designed landing page, animated hero sections, food menu with images and prices, a reservation system, and smooth hover/scroll animations.

---

## Features

### Frontend
- Animated hero banner with gradient motion background  
- Navigation bar with sections: Home, Menu, About Us, Contact, Reservations  
- Menu grid with food items (image, name, price)  
- Hover effects and smooth animations on menu cards  
- Reservation form for table bookings (Name, Email, Date, Time)  
- Responsive design for mobile and desktop  
- Checkout simulation using alert messages  

### Backend
- Node.js + Express API (optional integration)  
- REST API routes for menu items and reservations:  
  - `GET /api/menu` → Returns list of food items  
  - `POST /api/reservations` → Save reservation to database  
  - `GET /api/reservations` → View all reservations (Admin)  
- MongoDB schemas for Menu and Reservations  

### UI/UX
- Professional typography and spacing  
- Smooth scroll animations  
- Interactive buttons and hover effects  
- Slow-motion background animation for hero section  
- Product cards with shadow and zoom-in on hover  

---

## Technologies Used

- **Frontend:** React.js, TypeScript, Tailwind CSS, shadcn-ui, Framer Motion  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB Atlas (optional)  
- **Tools:** Vite, npm, GitHub, Lovable  
- **Images:** Unsplash / Pexels free images for menu items  

---

## Project Structure

```text
Gourmet-Delight/
├─ src/
│  ├─ assets/           # Images
│  ├─ components/       # UI components
│  ├─ pages/            # Page components
│  ├─ hooks/            # Custom hooks
│  └─ lib/ utils.ts     # Utility functions
├─ public/              # Static files
├─ package.json          # Node dependencies
├─ tailwind.config.ts    # Tailwind config
├─ vite.config.ts        # Vite config
└─ README.md

# Clone the repository
git clone (https://github.com/Shaik-Mohammed-Kaif/Responsive-Website)
cd Gourmet-Delight

# Install dependencies
npm install

# Start development server
npm run dev
