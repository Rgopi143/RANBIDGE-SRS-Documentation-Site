

# RANBIDGE SRS Documentation Site

A modern, interactive web application for generating and managing Software Requirements Specification (SRS) documents. Built with React, TypeScript, and powered by AI for intelligent document generation.

## 🚀 Features

- **AI-Powered SRS Generation**: Generate comprehensive SRS documents using Google's Gemini AI
- **Multiple Service Templates**: Pre-built templates for various services including:
  - Web Development
  - Mobile Development  
  - UI/UX Design
  - Software Development
  - IT Consulting
  - Digital Marketing
- **Interactive Form Builder**: Dynamic forms with real-time validation
- **Document Viewer**: Preview and download generated SRS documents
- **Admin Panel**: Secure admin login for managing configurations
- **Responsive Design**: Mobile-first design with Tailwind CSS
- **Email Integration**: Automatic email notifications for generated documents

## 🛠️ Technology Stack

- **Frontend**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **AI Integration**: Google Gemini API
- **Email Service**: EmailJS integration
- **Icons**: Lucide React

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager
- Google Gemini API key

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rgopi143/RANBIDGE-SRS-Documentation-Site.git
   cd RANBIDGE-SRS-Documentation-Site
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   ```
   Add your Gemini API key to `.env.local`:
   ```
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173`

## 📁 Project Structure

```
├── components/          # Reusable React components
│   ├── Footer.tsx      # Footer component
│   ├── Header.tsx      # Navigation header
│   ├── Hero.tsx        # Hero section
│   ├── SRSForm.tsx      # Main SRS form component
│   ├── SRSViewer.tsx    # Document preview viewer
│   └── ServiceSRSForm.tsx # Service-specific forms
├── pages/               # Page components
│   ├── AdminLogin.tsx   # Admin login page
│   ├── Contact.tsx      # Contact page
│   ├── Documentation.tsx # Documentation page
│   ├── Services.tsx     # Services overview
│   └── [Service]SRS.tsx # Service-specific SRS pages
├── services/            # API and business logic
│   ├── emailService.ts  # Email handling
│   ├── geminiService.ts # AI integration
│   ├── serviceChecklistConfigs.ts # Service configurations
│   └── serviceSRSTemplates.ts # SRS templates
├── types.ts             # TypeScript type definitions
├── App.tsx             # Main application component
├── index.html          # HTML template
├── index.tsx           # Application entry point
└── vite.config.ts      # Vite configuration
```

## 🔧 Configuration

### Environment Variables

Create a `.env.local` file in the root directory:

```env
VITE_GEMINI_API_KEY=your_gemini_api_key_here
```

### Getting Gemini API Key

1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Copy the key and add it to your `.env.local` file

## 📧 Email Configuration

The app uses EmailJS for sending emails. To configure:

1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Create an email service
3. Update the email service configuration in `services/emailService.ts`

## 🎯 Usage

1. **Select a Service**: Choose from available services on the main page
2. **Fill the Form**: Complete the interactive SRS form with project details
3. **Generate SRS**: Click generate to create your SRS document using AI
4. **Preview & Download**: Review the generated document and download as needed
5. **Email Options**: Send the SRS document via email if configured

## 🔐 Admin Features

Access the admin panel to:
- Manage service configurations
- Update SRS templates
- Monitor document generation
- Configure email settings

## 🚀 Deployment

### Build for Production

```bash
npm run build
```

### Deploy to Vercel

1. Connect your GitHub repository to Vercel
2. Add environment variables in Vercel dashboard
3. Deploy automatically on push to main branch

### Deploy to Netlify

1. Build the project: `npm run build`
2. Upload the `dist` folder to Netlify
3. Add environment variables in Netlify dashboard

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-feature`
3. Commit changes: `git commit -am 'Add new feature'`
4. Push to branch: `git push origin feature/new-feature`
5. Submit a pull request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support and inquiries:
- **Email**: rgopinathreddyvari38@gmail.com
- **GitHub**: Create an issue in the repository
- **Website**: [RANBIDGE Solutions](https://ranbidge.com)

## 🏢 About RANBIDGE

RANBIDGE Solutions Pvt Ltd is a leading technology company specializing in:
- Web & Mobile Development
- UI/UX Design
- IT Consulting
- Digital Marketing
- Custom Software Solutions

Visit our website to learn more about our services and solutions.

---

**Built with ❤️ by RANBIDGE Solutions**
