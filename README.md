# Invoicerr

> A modern, open-source invoicing application designed to simplify billing and financial management for freelancers and small businesses.

## 🎯 Philosophy

Invoicerr is built on the principle that invoicing should be **simple, transparent, and efficient**. We believe that:

- **Simplicity First**: Creating and managing invoices shouldn't require a degree in accounting. Our interface is intuitive and straightforward.
- **Open Source**: Transparency builds trust. Our codebase is open for inspection, contribution, and self-hosting.
- **Privacy-Focused**: Your financial data belongs to you. We prioritize data privacy and give you control over where your information lives.
- **Extensible**: Built with modern architecture to allow customization and integration with other tools.
- **Community-Driven**: We value feedback and contributions from our users and developers.

## 🚀 Features

- **Invoice Management**: Create, edit, and send professional invoices
- **Client Management**: Organize and track client information
- **Payment Tracking**: Monitor payment status and history
- **Multi-Currency Support**: Handle invoices in different currencies
- **PDF Export**: Generate professional PDF invoices
- **Customizable Templates**: Personalize invoice appearance to match your brand
- **Dashboard & Analytics**: Get insights into your business performance
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🛠️ Technology Stack

### Frontend
- **Framework**: React.js with TypeScript
- **State Management**: Redux Toolkit
- **UI Library**: Tailwind CSS / Material-UI
- **Build Tool**: Vite
- **Testing**: Jest + React Testing Library

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js / NestJS
- **Database**: PostgreSQL
- **ORM**: Prisma / TypeORM
- **Authentication**: JWT / OAuth 2.0
- **API**: RESTful API / GraphQL

### Infrastructure
- **Containerization**: Docker
- **CI/CD**: GitHub Actions

## 📋 Project Status

### ✅ Done
- [x] Project architecture design
- [x] Repository structure setup
- [x] Basic authentication system
- [x] Database schema design
- [x] Core API endpoints
- [x] Invoice creation and management UI
- [x] PDF generation service
- [x] Email notification system
- [x] Multi-language support (i18n)

### 🚧 In Progress
- [ ] Payment gateway integration
- [ ] Comprehensive test coverage

### 📝 TODO
- [ ] Recurring invoices functionality
- [ ] Expense tracking module
- [ ] Time tracking integration
- [ ] Advanced reporting and analytics
- [ ] API documentation (OpenAPI/Swagger)
- [ ] Third-party integrations (Stripe, PayPal, etc.)
- [ ] Multi-tenant support
- [ ] Role-based access control (RBAC)
- [ ] Automated backup system

## 🤝 Contributing

We welcome contributions from the community! Whether it's:

- 🐛 Bug reports
- 💡 Feature requests
- 📝 Documentation improvements
- 🔧 Code contributions

Please check our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## 📦 Getting Started

### Prerequisites
- Docker
- Docker Compose

### Installation

```bash
# Clone the repository
git clone https://github.com/invoicerr-app/invoicerr.git

# Navigate to the project directory
cd invoicerr

# Edit environment variables in docker-compose.yml
# Configure your settings as needed

# Start the application
docker compose up

# The application will be available at http://localhost (port 80 by default)
```

## 📄 License

This project is dual-licensed:
- **[AGPL-3.0 License](https://github.com/invoicerr-app/invoicerr?tab=AGPL-3.0-1-ov-file)** - For open source use
- **[Commercial License](https://github.com/invoicerr-app/invoicerr/blob/main/LICENSE.COMMERCIAL.md)** - For commercial/proprietary use

See the respective LICENSE files for details.

## 💬 Support

Need help? Have questions?

- 🐛 Issues: [GitHub Issues](https://github.com/invoicerr-app/invoicerr/issues)

---

**Made with ❤️ by the Invoicerr Team**