TP Tickets Partner (RV.RA-ICP)

Overview

TP Tickets Partner, branded as RV.RA-ICP, is a decentralized platform for creating events and selling tickets, leveraging the Internet Computer Protocol (ICP) blockchain for secure, transparent, and fraud-proof transactions. The platform allows users to purchase tickets for concerts, theaters, sports, festivals, and other events, primarily in Kyiv, Ukraine, with plans for broader expansion. Tickets are issued as NFTs, ensuring uniqueness and authenticity, and are accessible via QR codes for seamless entry. The platform supports a Telegram web application (@TP_TicketsPartner_bot) for convenient access without installation and has now expanded to a fully functional website.

Features





Event Discovery: Browse a wide range of events, including concerts, theater shows, festivals, conferences, and more, with filters for categories, dates, and locations.



Secure Payments: Multiple payment options, including Visa/MasterCard, PayPal, Bank Transfers, NOWPayments, and Plug Wallet for cryptocurrency transactions, all secured by blockchain technology.



NFT Tickets: Each ticket is a unique NFT stored on the ICP blockchain, ensuring transparency and preventing fraud.



QR Code Entry: Tickets are delivered with QR codes, accessible via the Telegram bot or downloadable from the website, for easy event entry.



User Accounts: Manage profiles, view purchased tickets, and download tickets with QR codes from the "My Account" section.



Cart System: Add multiple tickets to a cart for a streamlined checkout process.



Responsive Design: The website is optimized for mobile, tablet, and desktop devices, featuring a modern, neon-themed UI with Tailwind CSS and React.



Decentralized Technology: Built on the ICP blockchain with Internet Identity for secure user authentication and Plug Wallet integration for crypto payments.

Installation

To run the TP Tickets Partner website locally, follow these steps:





Clone the Repository:

git clone https://github.com/your-username/tp-tickets-partner.git
cd tp-tickets-partner



Serve the Website: Since the website is a static single-page application, you can serve it using any static file server. For example, using http-server:

npm install -g http-server
http-server .

Alternatively, you can open index.html directly in a browser for basic functionality, but a server is recommended for proper asset loading.



Dependencies: The website uses the following external libraries, loaded via CDN:





React and ReactDOM: https://cdnjs.cloudflare.com/ajax/libs/react/18.2.0/umd/react.production.min.js



QRCode.js: https://cdn.jsdelivr.net/npm/qrcode.react@3.1.0/lib/qrcode.min.js



Tailwind CSS: https://cdn.tailwindcss.com



Google Fonts (Poppins): https://fonts.googleapis.com/css2?family=Poppins

No additional installation is required for these dependencies as they are loaded at runtime.

Usage





Access the Website: Open the website in a browser or deploy it to a hosting service (e.g., Netlify, Vercel, or ICP canister for decentralized hosting).



Navigation:





Home: View featured events, top categories, and search for events.



Events: Browse all events with filters for category, date, and search by title or city.



About Us: Learn about the platform’s mission and technology.



Payment Methods: View supported payment options.



My Account: Manage profile information and view purchased tickets (requires login).



Cart: Add tickets to the cart and proceed to checkout.



Login/Register: Create an account or log in using email or Plug Wallet (note: Plug Wallet integration requires additional setup with @psychedelic/plug-connect).



Purchasing Tickets:





Select an event and choose "Add to Cart" or "Buy Now."



"Buy Now" instantly adds the ticket to your account with a QR code.



Cart items can be checked out in bulk, with tickets added to "My Account" and sent to the Telegram bot (@TP_TicketsPartner_bot).



Tickets can be downloaded as text files containing event details and QR codes.



Telegram Integration: Use the Telegram bot (@TP_TicketsPartner_bot) to receive QR codes for purchased tickets and access the web app directly.

File Structure





index.html: The main HTML file containing the React-based single-page application with Tailwind CSS styling and JavaScript logic for event browsing, user authentication, cart management, and ticket purchasing.



README.md: This file, providing an overview and instructions for the project.

Future Plans





Mobile Apps: Develop iOS and Android applications to enhance accessibility.



Expanded Event Coverage: Include more cities and event types beyond Kyiv.



Advanced Blockchain Integration: Fully implement Plug Wallet and Internet Identity for seamless decentralized authentication and payments.



Multilingual Support: Add support for additional languages to cater to a global audience.

Contact





Email: citointrues@gmail.com



Telegram: @TP_TicketsPartner_bot



Phone: +380934307551



Address: Ukraine, 03022, Kyiv city, Zdanovska Yuliya St., building 49, building 10, apartment 306
