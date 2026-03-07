# 🚀 saas-subscription-demo - Manage SaaS Subscriptions Easily

[![Download](https://img.shields.io/badge/Download-Get%20the%20App-brightgreen)](https://github.com/akamsniper/saas-subscription-demo)

## 📋 About saas-subscription-demo

This is a full-stack demo application for managing SaaS (Software as a Service) subscriptions. It has user login, subscription checkout using Stripe (in test mode), and a simple dashboard to view and manage your subscription. It runs on Windows and uses modern web technologies in the background such as Next.js and NestJS. You don’t need to know programming to run this app.

It includes features like:
- User authentication (login and registration).
- Checkout process with Stripe in test mode.
- Protected pages so only logged-in users can access the dashboard.
- A simple dashboard to see subscription status.
- Webhooks support to update subscription data automatically.

## 🎯 Who Should Use This?

This app is suited for anyone interested in trying a demo of a SaaS subscription flow. You may be a small business owner or someone testing SaaS setups. It requires no technical skills to run on Windows.

## 🖥️ System Requirements

Make sure your computer meets these requirements before proceeding:

- Windows 10 or higher.
- At least 4 GB of free RAM.
- At least 500 MB of free disk space.
- Internet connection for authentication and Stripe checkout.
- A modern web browser (such as Edge, Chrome, or Firefox).

## ⬇️ Download and Install the App

1. Click the big green badge above or use this link to visit the download page:

   [https://github.com/akamsniper/saas-subscription-demo](https://github.com/akamsniper/saas-subscription-demo)

2. Once on the page, look for the **Releases** section on the right sidebar or scroll down to find download options.

3. Download the latest Windows installer file (for example, it may have `.exe` at the end). If a pre-built installer is not available, skip to the manual setup steps in the next section.

4. After downloading, open the installer file by double-clicking it. Windows may ask for permission; click **Yes** to continue.

5. Follow the on-screen steps in the installer. Default settings are fine unless you want to change the install folder.

6. When installation completes, the app should launch automatically or create a shortcut on your desktop.

7. If the app does not open automatically, find and open **SaaS Subscription Demo** from your Start menu.

## 🛠️ Manual Setup (If no installer is available)

This app depends on programs called Node.js and Git to work. If you do not have these installed, follow the steps:

1. Download Node.js:
   - Go to https://nodejs.org/
   - Click the **LTS** (Long Term Support) version for Windows.
   - Download the installer and run it.
   - Follow the setup instructions and accept all defaults.

2. Download Git:
   - Visit https://git-scm.com/download/win
   - Download and run the installer.
   - Accept the default options during setup.

3. Download the app files:
   - Return to the main app page: https://github.com/akamsniper/saas-subscription-demo
   - Click the green **Code** button near the top.
   - Choose **Download ZIP**.
   - Once downloaded, right-click the ZIP file and choose **Extract All**.
   - Extract into a folder you can easily find, such as `Documents\saas-subscription-demo`.

4. Open the Command Prompt:
   - Press `Win + R`, type `cmd`, and press Enter.

5. Navigate to the folder where you extracted the files. For example, if in Documents:

   ```
   cd %USERPROFILE%\Documents\saas-subscription-demo
   ```

6. In the Command Prompt, type this to install necessary files:

   ```
   npm install
   ```

   Wait until this finishes. It may take a few minutes.

7. To start the app, enter this command:

   ```
   npm run dev
   ```

8. Open your browser and go to:

   ```
   http://localhost:3000
   ```

   You should see the login screen of the app.

## 🔑 How to Use the App

1. On the homepage, click **Sign Up** if you have no account. Fill in your email and password, then register.

2. After logging in, you will see the dashboard where you can view your subscription details.

3. To subscribe, choose the Stripe checkout option on the dashboard. You can make a test payment since this uses Stripe’s test mode.

4. When payment completes, the app will update your subscription status automatically.

5. Use the dashboard to check your active subscription or access protected content.

## 👨‍💻 Troubleshooting

- If the installer does not run, check that your Windows security settings allow apps from unknown sources.
- If the app won’t start in manual mode, confirm Node.js and Git are installed by running:

  ```
  node -v
  git --version
  ```

- If the browser shows an error accessing `http://localhost:3000`, make sure the server is running in the Command Prompt window.

- If checkout fails, confirm you are using the Stripe test card numbers provided on the app’s payment page.

## ⚙️ Technical Info (For Reference)

This app uses Next.js for frontend and NestJS for backend. It runs a REST API server to handle user login and subscription data. Stripe handles payments with webhooks to update subscription state in real time. The app stores data using a local database or mock data for demo purposes.

## 📂 Topics Covered

- Authentication with login/signup flows.
- SaaS subscription management.
- Stripe checkout integration in test mode.
- Full-stack development using Next.js and NestJS.
- Protected pages based on user login.
- Simple webhooks handling.

---

[![Download](https://img.shields.io/badge/Download-Get%20the%20App-brightgreen)](https://github.com/akamsniper/saas-subscription-demo)