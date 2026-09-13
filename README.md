# Event Coupon Management

A responsive web application for the farewell event at Global Knowledge Campus.

## Live demo

https://bcacoupon.pages.dev/

## Overview

This platform provides a registration process for event attendees and generates unique QR-code coupons for confirmed attendees. A secure manager portal is included for coupon verification — both through live QR scanning and manual input — with real-time statistics on attendance and coupon usage.

## Features

- **Event registration and login** — attendees register and log in with their details (name, roll number, phone number, email, password, and meal preference). The system automatically marks attendance as confirmed to generate a coupon.
- **Coupon generation** — a unique coupon ID is generated per attendee, with a QR code created via the QRCode.js library, and the coupon ID also shown in readable text.
- **Manager portal** — managers log in and access a dashboard for coupon verification via:
  - **Live QR code scanner** — using the HTML5 QR Code library.
  - **Manual coupon validation** — an input box to manually enter and validate a coupon ID.
- **Real-time statistics** — a statistics page shows total attendees (coupons generated), coupons scanned, coupons not scanned, and a detailed registrant list with meal preference and scan status.
- **Navigation** — every page includes navigation; a thank-you page serves as the post-logout landing page with links back to registration/login and the manager portal.

## Tech stack

HTML, JavaScript, Firebase (for registration/coupon data), QRCode.js, HTML5 QR Code scanning library.

## Setup

```bash
git clone https://github.com/D-Majumder/Event-Coupon-Management.git
cd Event-Coupon-Management
```

Configure your own Firebase project and replace the placeholder config in the source:

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

Place your own `favicon.ico` in the project root, then serve the folder with any static file server.

## License

This project is licensed under the **MIT License**. See [LICENSE](./LICENSE) for the full text.
