# Home Haven

AI-powered appliance identification and repair assistant that helps homeowners save money on repairs through smart photo recognition and instant fix solutions.

## Features

- 📸 **Smart Photo Recognition** - Point camera at appliance for instant identification
- 🤖 **AI-Powered Solutions** - Get personalized repair suggestions
- 💰 **Cost Savings** - Avoid unnecessary service calls
- 📱 **Mobile-First Design** - Native iOS and Android apps
- 🔧 **Step-by-Step Guides** - Easy-to-follow repair instructions

## Tech Stack

**Backend**
- FastAPI + Python
- PostgreSQL database
- Google Vision API
- Railway hosting

**Mobile**
- React Native
- Cross-platform iOS/Android

## Project Structure

```
home-haven/
├── backend/
│   ├── app/
│   │   ├── models/      # Database models
│   │   ├── routers/     # API endpoints
│   │   ├── schemas/     # Pydantic schemas
│   │   └── services/    # Business logic
│   ├── requirements.txt
│   └── Dockerfile
├── mobile/
│   ├── src/
│   │   ├── screens/     # App screens
│   │   ├── components/  # Reusable components
│   │   ├── api/        # API integration
│   │   └── utils/      # Helper functions
│   └── package.json
└── docs/               # Project documentation
```

## Quick Start

### Backend Development
```bash
cd backend
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### Mobile Development
```bash
cd mobile
npm install
npx react-native run-ios  # or run-android
```

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## License

MIT License - see LICENSE file for details.