<h1 align="center" id="title">Event Coupon Management</h1>

<p align="center"><img src="https://socialify.git.ci/D-Majumder/Event-Coupon-Management/image?custom_description=A+fully+responsive+web+application+for+the+farewell+event+at+Global+Knowledge+Campus.+This+platform+provides+an+easy+registration+process+for+event+attendees+and+generates+unique+QR-code+coupons+for+those+confirmed+to+attend.+A+secure+manager+portal+is+included+for+coupon+verification%E2%80%94both+through+live+QR+scanning+as+well+as+manual+input%E2%80%94with+real-time+statistics+on+attendance+and+coupon+usage.&amp;description=1&amp;language=1&amp;name=1&amp;owner=1&amp;stargazers=1&amp;theme=Light" alt="project-image"></p>

<p id="description">A fully responsive web application for the farewell event at Global Knowledge Campus. This platform provides an easy registration process for event attendees and generates unique QR-code coupons for those confirmed to attend. A secure manager portal is included for coupon verification—both through live QR scanning as well as manual input—with real-time statistics on attendance and coupon usage.</p>

<p align="center"><img src="https://img.shields.io/badge/Event-Coupon-Red" alt="shields"></p>

<h2>🚀 Demo</h2>

[https://bcacoupon.pages.dev/](https://bcacoupon.pages.dev/)

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Event Registration and Login Attendees can register and log in with their details (name roll number phone number email password and meal preference). The system automatically marks attendance as “yes” to generate a coupon.
*   Coupon Generation For every registered attendee a unique coupon ID is generated. A QR code is created using the QRCode.js library and the coupon ID is also displayed in clear readable black text.
*   Manager Portal Managers can log in using their credentials access a dedicated dashboard for coupon verification and use the following verification methods: Live QR Code Scanner: Utilizes the HTML5 QR Code library (via the unversioned URL) to scan and verify coupons. Manual Coupon Validation: Provides an input box where a manager can manually enter a coupon ID to validate it.
*   Real-Time Statistics A statistics page displays real-time data: Total number of attendees (coupons generated) Coupons scanned Coupons not scanned A detailed list of registrants including their meal preference and whether their coupon has been scanned (using visual indicators such as a green check (✓) or a red cross (❌))
*   User-Friendly Navigation Every page includes navigation buttons for a smooth user experience. The Thank You page serves as the landing page after logout and contains links back to the registration/login and manager portals.

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the Repository</p>

```
git clone https://github.com/yourusername/your-repo-name.git cd your-repo-name
```

<p>2. Configure Firebase</p>

```
const firebaseConfig = {   apiKey: "YOUR_API_KEY"   authDomain: "YOUR_PROJECT_ID.firebaseapp.com"   projectId: "YOUR_PROJECT_ID"   storageBucket: "YOUR_PROJECT_ID.appspot.com"   messagingSenderId: "YOUR_SENDER_ID"   appId: "YOUR_APP_ID" };
```

<p>3. Add Favicon</p>

```
Place your favicon.ico file in the root of the project.
```

<p>4. Customize Allowed Roll Numbers (Optional):</p>

<h2>🛡️ License:</h2>

This project is licensed under the MIT
