# SwapCircle

## 📖 Overview
SwapCircle is a campus clothing exchange platform that enables students to buy, sell, and swap clothing items within their university community. The platform promotes sustainable fashion and helps students save money while refreshing their wardrobes.

## ✨ Features
- **User Authentication**: Secure login and registration for students
- **Item Listings**: Post clothing items for sale or swap
- **Search & Filter**: Find items by category, size, brand, and more
- **Campus Verification**: Ensure transactions happen within trusted university communities
- **Favorites**: Save items you're interested in
- **User Profiles**: View seller ratings and transaction history

## 🛠️ Tech Stack
### Frontend
- **Framework**: Next.js 15.5.6 (with Turbopack)
- **UI Library**: React 19.1.0
- **Styling**: Tailwind CSS v4
- **Linting**: ESLint with Next.js config

### Backend
- **Framework**: FastAPI (Python)
- **Database**: MongoDB
- **Configuration**: Pydantic Settings
- **Architecture**: RESTful API with async/await support

## 🗂️ Project Structure
```
SwapCircle/
├── Frontend/                 # Next.js frontend application
│   ├── src/
│   │   ├── app/             # Next.js App Router pages
│   │   │   ├── page.js      # Home page
│   │   │   └── product/     # Product detail pages
│   │   ├── components/      # React components
│   │   │   ├── AuthModal.js
│   │   │   ├── Header.js
│   │   │   ├── Footer.js
│   │   │   ├── HeroSection.js
│   │   │   ├── ListingCard.js
│   │   │   ├── ListingsGrid.js
│   │   │   ├── ProductDetail.js
│   │   │   └── ValueProposition.js
│   │   ├── contexts/        # React contexts (Auth, Notifications)
│   │   ├── services/        # API service layer
│   │   ├── utils/           # Utility functions
│   │   └── styles/          # Global styles and theme
│   ├── public/              # Static assets
│   ├── package.json
│   ├── next.config.mjs      # Next.js configuration
│   ├── tailwind.config.js   # Tailwind CSS configuration
│   └── eslint.config.mjs    # ESLint configuration
│
├── Backend/                 # FastAPI backend application
│   ├── main.py              # FastAPI application entry point
│   ├── config.py            # Configuration and settings
│   ├── database/
│   │   └── connection.py    # MongoDB connection helpers
│   ├── models/              # Pydantic data models
│   │   ├── user_model.py
│   │   ├── item_model.py
│   │   ├── swap_request_model.py
│   │   ├── transaction_model.py
│   │   └── rating_model.py
│   ├── routes/              # API route handlers
│   │   ├── auth_routes.py
│   │   ├── user_routes.py
│   │   ├── item_routes.py
│   │   ├── swap_routes.py
│   │   ├── message_routes.py
│   │   ├── credit_routes.py
│   │   ├── rating_routes.py
│   │   └── notification_routes.py
│   ├── services/            # Business logic services
│   │   ├── auth_service.py
│   │   ├── user_service.py
│   │   ├── swap_service.py
│   │   ├── email_service.py
│   │   ├── image_service.py
│   │   ├── credit_service.py
│   │   └── storage_service.py
│   └── utils/               # Utility functions
│       └── constants.py
│
├── codebase/                # Code documentation
│   ├── codebase.md          # Main documentation index
│   ├── components.md        # Frontend component docs
│   ├── api-integration.md   # Frontend-Backend integration
│   ├── theme.md             # Theme and styling guide
│   ├── styling-guide.md     # Styling best practices
│   ├── backend-routes.md   # Backend API routes
│   ├── backend-services.md # Backend services
│   └── backend-models.md   # Backend data models
│
├── Documentation/           # Project documentation
│   ├── backend-architecture.md
│   ├── frontend-specs.md
│   └── project-overview.md
│
└── README.md               # This file
```

## 📚 Code Documentation

For detailed code documentation, see the [`codebase/`](./codebase/) folder:

- **[codebase.md](./codebase/codebase.md)** - Main documentation index with overview and links
- **[components.md](./codebase/components.md)** - Frontend component documentation
- **[api-integration.md](./codebase/api-integration.md)** - Frontend-Backend API integration guide
- **[theme.md](./codebase/theme.md)** - Theme, fonts, and styling information
- **[styling-guide.md](./codebase/styling-guide.md)** - Styling best practices (use utility classes, no inline styles!)
- **[backend-routes.md](./codebase/backend-routes.md)** - Complete backend API routes documentation
- **[backend-services.md](./codebase/backend-services.md)** - Backend services and business logic
- **[backend-models.md](./codebase/backend-models.md)** - Backend data models and schemas

**Before making changes to the codebase, consult the relevant documentation files in the `codebase/` folder to understand the existing implementation.**

## 🧪 Testing
```bash
# Add commands to run tests
```

## 🤝 Contributing
We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Open a Pull Request

### Code Style
- Follow the existing code style in the project
- Write clear commit messages
- Add tests for new features
- Update documentation as needed

## 👥 Team
- Aiman
- Hasnain
- Mulyn
- Rayyan
- Katia
- Kazeem
