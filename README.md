# AI Assistant Doctor

An AI-powered medical diagnosis assistant that helps doctors analyze medical images and provide preliminary diagnoses.

## Features

- Drag-and-drop interface for medical image upload
- AI-powered image analysis using ChexAgent
- Secure user authentication
- PDF report generation
- Real-time analysis results

## Project Structure

```
ai-assistant-doctor/
│
├── client/                    # Frontend - Vanilla JS App
│   ├── index.html             # Main HTML page
│   ├── styles/                # CSS files
│   ├── scripts/               # JavaScript files
│   └── assets/                # Icons, logos, etc.
│
├── server/                    # Backend - Express.js App
│   ├── app.js                 # Main Express server setup
│   ├── routes/                # API endpoints
│   ├── controllers/           # Route handlers
│   ├── services/              # Firebase, AI model integration
│   ├── utils/                 # Helper functions
│   └── config/                # Configuration files
│
└── reports/                   # Generated PDF/HTML reports
```

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the root directory with your Firebase credentials
4. Start the development server:
   ```bash
   npm run dev
   ```

## Environment Variables

Create a `.env` file with the following variables:

```
FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_auth_domain
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
FIREBASE_APP_ID=your_app_id
FIREBASE_MEASUREMENT_ID=your_measurement_id
FIREBASE_DATABASE_URL=your_database_url
```

## License

MIT 