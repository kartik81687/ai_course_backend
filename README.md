# AI Course Backend

An enterprise-level backend service for AI course platform with support for 1M+ concurrent users.

## Features

- 🔒 Secure Authentication & Authorization
- 💳 Multiple Payment Gateways (Stripe, Flutterwave)
- 📧 Email Notifications
- 🤖 AI Integration with Google's Generative AI
- 🎥 YouTube Content Integration
- 🖼️ Unsplash Image Integration
- 📊 MongoDB Database
- ⚡ Express.js Server

## Prerequisites

- Node.js >= 16.0.0
- MongoDB
- Stripe Account
- Flutterwave Account
- Google AI API Key
- SMTP Server Configuration

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

# Stripe Configuration
STRIPE_SECRET_KEY=your_stripe_secret_key

# Flutterwave Configuration
FLUTTERWAVE_PUBLIC_KEY=your_flutterwave_public_key
FLUTTERWAVE_SECRET_KEY=your_flutterwave_secret_key

# Email Configuration
SMTP_HOST=your_smtp_host
SMTP_PORT=your_smtp_port
SMTP_USER=your_smtp_user
SMTP_PASS=your_smtp_password

# Google AI Configuration
GOOGLE_AI_API_KEY=your_google_ai_api_key

# Frontend URLs (for CORS)
FRONTEND_URL=your_frontend_url
```

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables
4. Start the development server:
   ```bash
   npm run dev
   ```

## Scripts

- `npm start` - Start production server
- `npm run dev` - Start development server with hot reload
- `npm test` - Run tests

## Security Features

- CORS protection
- Rate limiting
- Helmet security headers
- JWT authentication
- Input validation
- Secure password hashing

## API Documentation

[Add your API documentation here]

## Performance Optimizations

- Connection pooling for MongoDB
- Rate limiting for API endpoints
- Caching strategies
- Efficient error handling
- Load balancing ready

## Contributing

[Add contribution guidelines here]

## License

ISC 