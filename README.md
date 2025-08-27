Tickets Partner 🎫
Tickets Partner (also known as RV.RA-ICP) is a modern, decentralized ticket booking platform that seamlessly integrates with Telegram for effortless event discovery and purchasing. Built on the Internet Computer Protocol (ICP), our platform leverages blockchain technology for secure, transparent, and tamper-proof ticketing. Users can purchase tickets for events using cryptocurrencies (including ICP via Plug Wallet), traditional payment methods, or other supported options—all within a unified ecosystem.
As participants in the ICP WCHL25 Hackathon (Qualification Round) on DoraHacks , we're transforming our initial landing page into a fully functional, ICP-hosted website. This evolution incorporates Plug Wallet for seamless ICP payments, Internet Identity (II) for secure authentication, and AI-powered features via coffee.ai to enhance user experience and event recommendations. Our goal is to create a scalable, decentralized ticketing solution that empowers event organizers, protects users from fraud, and fosters a vibrant Web3 community.
🌟 Features
For Users

Decentralized Ticket Purchasing: Buy tickets securely using ICP via Plug Wallet, with NFT-based tickets stored on the blockchain for verifiable ownership and anti-counterfeiting.
Internet Identity (II) Integration: Passwordless, secure login using biometric or hardware-based authentication for enhanced privacy and user control.
Telegram Bot Integration: Discover, browse, and purchase tickets directly within Telegram for a frictionless experience.
Multiple Payment Methods: Support for ICP (via Plug Wallet), USDT, BTC, SOL, and traditional banking options.
QR Code & NFT Tickets: Receive digital tickets as QR codes or NFTs for easy check-in and secondary market trading.
AI-Powered Recommendations: Leveraging coffee.ai for personalized event suggestions based on user preferences, past purchases, and real-time trends.
Referral System: Earn ICP rewards or discounts by referring friends.
Event Discovery: Browse, search, and filter events with real-time notifications.
Cross-Platform Access: Seamless experience across web, Telegram mini-app, and upcoming iOS/Android apps.

For Event Organizers

Decentralized Event Creation: Create and manage events on ICP canisters for immutable records and global accessibility.
Multiple Ticket Types: Define pricing tiers, capacities, and NFT-based exclusives.
Promotional Tools: Generate discount codes, free tickets, and ICP-based referral links.
Real-Time Analytics: Track sales, attendance, and engagement with blockchain-verified data.
AI Insights: Use coffee.ai to optimize event promotion and predict attendance.

For Administrators

Event Moderation: Approve or reject events with decentralized governance tools.
Payment Management: Handle confirmations for ICP and traditional payments.
User Analytics: Access comprehensive, privacy-preserving statistics.
Notification System: Broadcast updates via Telegram or in-app alerts.

🚀 Technology Stack
Blockchain & Decentralization

Internet Computer Protocol (ICP): Hosts the full website and backend logic in canisters for high scalability, low costs, and true decentralization.
Plug Wallet: Enables seamless ICP payments and wallet integration.
Internet Identity (II): Provides secure, decentralized authentication.
NFT Standards: For unique, verifiable tickets on the ICP blockchain.

Frontend

React 18 with JSX (embedded in static HTML for ICP canister deployment).
Tailwind CSS for responsive, modern styling.
Framer Motion for smooth animations.
React Slick for carousels.
Heroicons for icons.
React Router DOM for navigation (simulated in static setup).

Backend & Integrations

ICP Canisters: Handle core logic, data storage, and smart contracts for events and tickets.
Node.js with Express.js (transitional; migrating to full ICP).
Firebase Firestore (transitional database; integrating with ICP for full decentralization).
Telegram Bot API for bot integration.
NOWPayments API for multi-crypto payments (USDT, BTC, ETH, SOL, LTC).
Monobank API for traditional Ukrainian banking.
coffee.ai: AI engine for event recommendations, personalization, and analytics.

Payment Processing

Plug Wallet & ICP: Native cryptocurrency payments with low fees and instant settlement.
NOWPayments: Support for additional cryptos.
Monobank: Fiat integration for Ukrainian users.
Manual Verification: PDF uploads for custom payments (with blockchain verification).

Demonstration Site
A live demonstration of our fully functional website is hosted on an ICP canister. Access it via the index.html deployed on ICP for a preview of our decentralized frontend. This demo showcases event browsing, cart functionality, Plug Wallet integration, and AI-driven features. View Demo (replace with actual canister URL post-deployment).
📁 Project Structure
text├── src/
│   ├── components/
│   │   ├── Admin.jsx          # Admin dashboard
│   │   ├── Events.jsx         # Event browsing and creation
│   │   ├── Home.jsx           # Main dashboard
│   │   ├── Landing.jsx        # Evolved into full ICP-based site
│   │   ├── Partners.jsx       # Referral system
│   │   └── Tickets.jsx        # User tickets
│   ├── App.jsx                # Main application router
│   ├── firebase.js            # Firebase configuration (transitional)
│   ├── main.jsx               # React entry point
│   └── styles.css             # Global styles
├── server.js                  # Express server (transitional)
├── serviceAccountKey.json     # Firebase admin credentials (transitional)
├── index.html                 # ICP-hosted demo site with embedded React
└── package.json               # Dependencies
🛠️ Installation & Setup
Prerequisites

Node.js 16+
ICP SDK (dfx) for canister deployment
Plug Wallet for testing ICP payments
Firebase project (transitional)
Telegram Bot Token
NOWPayments API key (optional)
Monobank API key (optional)
coffee.ai API key for AI features

Environment Variables
Create a .env file with:
envTELEGRAM_BOT_TOKEN=your_bot_token
WEB_APP_URL=your_icp_canister_url
NOWPAYMENTS_API_KEY=your_nowpayments_key
NOWPAYMENTS_IPN_SECRET=your_ipn_secret
MONOBANK_API_KEY=your_monobank_key
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_PROJECT_ID=your_project_id
COFFEE_AI_API_KEY=your_coffee_ai_key
ICP_CANISTER_ID=your_canister_id
Running Locally

Install dependencies:
bashnpm install

Start development server:
bashnpm run dev

Deploy to ICP:

Install dfx: sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
Deploy canister: dfx deploy
Host index.html and assets on the canister.



Production
Deploy the full site to an ICP canister for decentralized hosting. Use Plug Wallet for testing ICP/II integrations.
🔧 Configuration
ICP & Plug Wallet Setup

Set up an ICP developer account and create a canister.
Integrate Plug Wallet using the @psychedelic/plug-connect library.
Enable II for authentication in the frontend.

AI Integration (coffee.ai)

Obtain API keys from coffee.ai.
Implement endpoints for personalized recommendations in ICP canisters.

Telegram Bot Setup

Create bot via @BotFather.
Set webhook to your ICP-hosted URL.
Configure Web App URL in bot settings.

📱 Usage
For Users

Start the bot: @TP_TicketsPartner_bot
Browse events, select tickets, and pay via Plug Wallet (ICP) or other methods.
Receive NFT/QR code tickets in Telegram or the web app.

For Event Organizers & Admins
Access via web app or bot for creation, moderation, and analytics.
🔐 Security Features

Blockchain Verification: ICP ensures immutable tickets and payments.
II Authentication: Decentralized, secure logins.
NFT Tickets: Prevent fraud with unique, on-chain assets.
Encryption: All data encrypted; payments via secure gateways.

🌍 Internationalization

Ukrainian (primary)
English (full support)

📊 Analytics & Monitoring

Blockchain-based tracking for sales and engagement.
AI-driven insights via coffee.ai.

🚀 Deployment
On ICP

Use dfx to deploy canisters.
Host static assets (index.html) on the asset canister.
Integrate with Telegram for hybrid web/bot experience.

Production Considerations

SSL via ICP's built-in support.
Rate limiting and monitoring.
Regular canister upgrades.

🤝 Contributing

Fork the repo.
Create a feature branch.
Submit a PR with tests.

📄 License
Proprietary. All rights reserved.
📞 Support

Telegram: @TicketsPartners
Bot: @TP_TicketsPartner_bot
Email: citointrues@gmail.com
Location: Kyiv, Ukraine

🔄 Version History

v1.0.0: Initial release.
Current: ICP-integrated with Plug Wallet, II, and AI features.


This project is submitted to the ICP WCHL25 Hackathon, showcasing how decentralized technologies like ICP, II, and Plug Wallet can revolutionize ticketing—making it secure, accessible, and innovative. We're excited to build a full ecosystem, including upcoming iOS/Android apps, to drive Web3 adoption in events!
