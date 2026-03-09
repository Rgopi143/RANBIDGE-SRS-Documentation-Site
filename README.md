

# RANBIDGE SRS Documentation Portal

A comprehensive web application for generating Software Requirements Specification (SRS) documents tailored to various service types. Built with React, TypeScript, and modern web technologies.

## 🚀 Features

### Core Functionality
- **Dynamic SRS Generation**: Create professional SRS documents customized for different service types
- **Multi-Service Support**: Specialized templates for:
  - Web Development
  - Mobile Development  
  - Software Development
  - UI/UX Design
  - Digital Marketing
  - IT Consulting
- **Interactive Forms**: Step-by-step guided form completion with validation
- **Real-time Preview**: Live preview of generated SRS documents
- **PDF Export**: Download generated SRS documents as PDF files
- **Email Integration**: Send SRS documents directly to clients via EmailJS

### User Experience
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional interface built with TailwindCSS
- **Service-Specific Workflows**: Tailored question sets and requirements for each service type
- **Progress Tracking**: Visual progress indicators through form steps
- **Admin Panel**: Secure access for managing templates and configurations

## 🛠️ Tech Stack

- **Frontend**: React 19.2.3 with TypeScript
- **Build Tool**: Vite 6.2.0
- **Routing**: React Router DOM 7.12.0
- **Styling**: TailwindCSS
- **Icons**: Lucide React
- **AI Integration**: Google Gemini API for intelligent SRS generation
- **Email Service**: EmailJS for document delivery
- **PDF Generation**: Custom PDF export functionality

## 📋 Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager
- Google Gemini API Key
- EmailJS account (for email functionality)

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/Rgopi143/RANBIDGE-SRS-Documentation-Site.git
cd RANBIDGE-SRS-Documentation-Site
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Environment Setup
Create a `.env` file in the root directory:
```env
VITE_GEMINI_API_KEY=your_gemini_api_key_here
VITE_EMAILJS_PUBLIC_KEY=your_emailjs_public_key
VITE_EMAILJS_SERVICE_ID=your_emailjs_service_id
VITE_EMAILJS_TEMPLATE_ID=your_emailjs_template_id
```

### 4. Run Development Server
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### 5. Build for Production
```bash
npm run build
```

### 6. Preview Production Build
```bash
npm run preview
```

## 📁 Project Structure

```
RANBIDGE-SRS-Documentation-Site/
├── components/              # Reusable UI components
│   ├── Header.tsx         # Navigation header
│   ├── Footer.tsx         # Site footer
│   ├── Hero.tsx           # Hero section
│   ├── SRSForm.tsx        # Main SRS form component
│   ├── SRSViewer.tsx      # SRS document viewer
│   └── ServiceSRSForm.tsx # Service-specific form
├── pages/                  # Page components
│   ├── Services.tsx       # Services showcase
│   ├── Documentation.tsx  # Documentation page
│   ├── Contact.tsx        # Contact page
│   ├── AdminLogin.tsx     # Admin login
│   └── [Service]SRS.tsx   # Service-specific SRS pages
├── services/              # Business logic services
│   ├── geminiService.ts   # AI integration
│   ├── emailService.ts    # Email functionality
│   ├── serviceSRSTemplates.ts # SRS templates
│   └── serviceChecklistConfigs.ts # Service configurations
├── types.ts               # TypeScript type definitions
├── App.tsx               # Main application component
├── index.tsx             # Application entry point
└── vite.config.ts        # Vite configuration
```

## 🔧 Configuration

### Gemini API Setup
1. Visit [Google AI Studio](https://aistudio.google.com/)
2. Create a new API key
3. Add the API key to your `.env` file

### EmailJS Setup
1. Create an [EmailJS](https://www.emailjs.com/) account
2. Create an email service and template
3. Add your credentials to the `.env` file

## 🎯 Available Services

The application supports SRS generation for the following services:

1. **Web Development**
   - Website types (Business, E-commerce, Portfolio, Blog, etc.)
   - Page requirements and functionality
   - Technology stack preferences

2. **Mobile Development**
   - Platform selection (iOS, Android, Cross-platform)
   - App categories and features
   - UI/UX requirements

3. **Software Development**
   - Desktop applications
   - Enterprise software solutions
   - Custom software requirements

4. **UI/UX Design**
   - Design systems and components
   - User research requirements
   - Brand guidelines and preferences

5. **Digital Marketing**
   - Campaign requirements
   - Target audience specifications
   - Marketing channels and KPIs

6. **IT Consulting**
   - Consulting scope and objectives
   - Technical requirements
   - Deliverables and timelines

## 🔐 Features in Detail

### SRS Generation Process
1. **Client Information**: Basic contact and project details
2. **Service Selection**: Choose the appropriate service type
3. **Requirements Gathering**: Service-specific questions and checklists
4. **Technical Specifications**: Technology stack and preferences
5. **Review and Export**: Preview, edit, and download the final SRS

### Export Options
- **PDF Download**: Professional PDF format with proper formatting
- **Email Delivery**: Direct sending to client email addresses
- **Print-Ready**: Optimized layout for physical printing

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support and inquiries:
- **Email**: contact@ranbidge.com
- **Website**: [RANBIDGE Solutions](https://ranbidge.com)
- **GitHub Issues**: [Report issues here](https://github.com/Rgopi143/RANBIDGE-SRS-Documentation-Site/issues)

## 🔄 Version History

- **v1.0.0** - Initial release with core SRS generation functionality
- Support for 6 service types
- PDF export and email integration
- Responsive design and modern UI

---

**Built with ❤️ by RANBIDGE Solutions Pvt. Ltd.**
