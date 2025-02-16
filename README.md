# Vizo : Real-time Video Calling Application

This project implements a real-time video calling application called **Vizo**, built using **Next.js** for the frontend and **Zego's UIKit Prebuilt** library for video conferencing. It provides a simple and secure way for users to connect and collaborate through video calls.

## Table of Contents
- [Vizo : Real-time Video Calling Application](#vizo--real-time-video-calling-application)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Environment Variables](#environment-variables)
  - [Deployment](#deployment)
  - [Contributing](#contributing)

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone <repository_url>
   ```

2. **Install dependencies:**

   ```bash
   npm install  # or yarn install or pnpm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root of your project and populate it with the required environment variables (see [Environment Variables](#environment-variables)).

4. **Run the development server:**

   ```bash
   npm run dev  # or yarn dev or pnpm dev
   ```

   This will start the Next.js development server. The application should be accessible at `http://localhost:3000` (or the port you configured).

## Features

- **Real-time video calling:** Powered by Zego's UIKit Prebuilt for seamless video and audio communication.
- **Room-based calls:** Users can join or create rooms using unique room IDs.
- **User identification:** Displays user names in the video call.
- **Shareable links:** Easy sharing of room links.
- **Secure token generation:** Zego Kit Token generation is handled server-side for enhanced security.

## Technologies Used

- **Next.js 13**
- **React**
- **Zego UIKit Prebuilt** (`@zegocloud/zego-uikit-prebuilt`)
- **UUID** (`uuid`)
- **Zustand** (used for state management)
- **Tailwind CSS** (used for styling)

## Environment Variables

Create a `.env` file in the root directory and add the following environment variables:

```bash
ZEGO_APP_ID=<your_zego_app_id>
ZEGO_SERVER_SECRET=<your_zego_server_secret>
```

## Deployment

You can deploy this Next.js application to any platform that supports Node.js and Next.js, such as Vercel, Netlify, or AWS. Make sure to configure the environment variables on your deployment platform.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
