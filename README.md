# Darwesh AI - WhatsApp Chatbot

<p align="center">
  <h2 align="center">Darwesh AI WhatsApp Bot</h2>
  <p align="center">A professional WhatsApp chatbot for business interactions, product inquiries, and customer support</p>
</p>

## About This Project

Darwesh AI is a fully functional, interactive, menu-based WhatsApp chatbot tailored for business use. It provides a structured conversation flow for customer inquiries, product browsing, and support requests.

## Features

- **Text-Based Menu Navigation**: Easy-to-use number-based navigation system
- **Product Categories**: Browse products by categories and view item details
- **FAQs Section**: Quick answers to common customer questions
- **Contact Support**: Direct access to customer service
- **Purchasing Flow**: Seamless product selection and ordering process

## Technical Details

- Built with **BuilderBot** and **Baileys** for WhatsApp integration
- Runs on **Node.js** with TypeScript
- Uses in-memory data storage (no database required)
- Follows a modular conversation flow architecture

## Getting Started

### Prerequisites
- Node.js (v20+)
- Git
- npm/pnpm

### Installation

```bash
# Clone the repository
git clone [your-repo-url]

# Navigate to the project directory
cd darwesh-ai-whatsapp

# Install dependencies
npm install

# Start the development server
npm run dev
```

## Usage

1. After starting the server, scan the QR code with your WhatsApp account
2. Send a message like "hi" or "hello" to start the conversation
3. Navigate through the menu using number commands:
   - 0 - Return to Main Menu
   - 1 - View Products
   - 2 - FAQs
   - 3 - Contact Support
   - 4 - Buy products
   - 9 - Go back to previous menu

## Deployment Instructions

### Free 24/7 Hosting with Railway.app

1. **Create a Railway Account**
   - Go to [Railway.app](https://railway.app/) and sign up using GitHub
   - You'll get free credits each month

2. **Deploy from GitHub**
   - Push your code to a GitHub repository
   - In Railway dashboard, click "New Project" → "Deploy from GitHub repo"
   - Select your repository

3. **Configure Environment**
   - Railway will automatically detect your Node.js app
   - Set the following environment variables in Railway dashboard:
     - `PORT`: 3008 (or any port of your choice)
     - `NODE_ENV`: production

4. **Deploy and Monitor**
   - Railway will build and deploy your application
   - Your bot will be available 24/7
   - The QR code for WhatsApp authentication will be available in the logs

5. **Maintain Session**
   - Your bot sessions are stored in the `bot_sessions` folder
   - Railway preserves these files between deployments

## Future Enhancements

- Order tracking functionality
- Inventory synchronization
- Promotions and discount features
- Database integration

## Contact

For support or inquiries, contact us at 03168076027

## Credits

Built using [BuilderBot](https://builderbot.vercel.app/) framework