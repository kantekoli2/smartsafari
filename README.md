# SmartSafari

**SmartSafari** is a cross-platform Flutter ecosystem (Android, iOS, Web) for real-time, AI-powered safari planning and booking across East Africa.

---

## 🚀 Quick Start

1. **Clone the repo**

```bash
git clone https://github.com/kantekoli2/smartsafari.git
cd smartsafari
```

2. **Install dependencies**

```bash
flutter pub get
```

3. **Configure environment**

- Copy `.env.example` to `.env` and fill in your production keys.

4. **Run the app (choose platform)**

```bash
flutter run -d chrome   # Web
flutter run -d android  # Android
flutter run -d ios      # iOS
```

5. **Build for production**

```bash
flutter build web
flutter build apk
flutter build ios
```

---

## 🗄️ Environment Variables

Copy `.env.example` to `.env` and fill in:

- SUPABASE_URL
- SUPABASE_ANON_KEY
- AI_API_KEY (Grok/OpenAI/other)
- GOOGLE_OAUTH_CLIENT_ID

---

## 🌍 Features Overview

- Cinematic animated home banner
- Country dashboards (Kenya, Tanzania, Uganda, Rwanda)
- Real-time sync via Supabase
- Planner, Chatbot, Bookings, Profile, Business, Admin
- Payment integrations (Stripe, PayPal, M-Pesa, Airtel Money)
- Freemium model & premium enforcement
- Localization: EN, FR, SW, DE, ES
- Accessibility: WCAG-compliant
- Admin dashboard (web)
- CI/CD scripts, QA checklist, and rollback plan

---

## 🖼️ Assets

All images and videos are licensed and production-ready.  
See `/assets/` for full attribution.

---

## 🔑 API Keys

Request any integration keys not provided here from the owner.  
Never commit secrets to the repo.

---

## 🛡️ Security & Compliance

- GDPR/CCPA ready
- All third-party dependencies are audited
- See `SECURITY.md` and `DEPLOYMENT.md` for details

---

## 📋 QA & Release

- See `QA-CHECKLIST.md` for full verification
- Automated and manual tests included

---

## 🛠️ Troubleshooting

If you need to rotate the admin password or remove admin access, see `DEPLOYMENT.md`.

---

## 🤝 Contributing

Contributions, issues, and feature requests welcome!

---

© 2025 SmartSafari. All assets are used under appropriate licenses.