# BiteBuddy

BiteBuddy is a web application designed to connect food enthusiasts by allowing users to share and discover food listings. Whether you're looking to share surplus food, find local eateries, or explore culinary experiences, BiteBuddy makes it easy with an intuitive interface, integrated maps, and secure authentication.

## Features

- **Food Listings**: Create and view detailed food listings with descriptions, locations, and more.
- **Interactive Maps**: Integrated Google Maps to visualize food locations and navigate easily.
- **User Authentication**: Secure login and registration using Firebase Authentication.
- **User Profiles**: Manage personal profiles and track your listings.
- **Responsive Design**: Built with Tailwind CSS for a seamless experience across devices.

## Technologies Used

- **Frontend**: Next.js, React
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Maps**: Google Maps API (@react-google-maps/api)
- **Backend**: Firebase (Authentication, Firestore)
- **Linting**: ESLint

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YashPandya10/BitBuddy_Web_Dev.git
   cd bitebuddy
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. Set up Firebase:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Enable Authentication and Firestore.
   - Add your Firebase config to `lib/firebase.js`.

4. Set up Google Maps API:
   - Get an API key from [Google Cloud Console](https://console.cloud.google.com/).
   - Add the API key to your environment variables or directly in `components/GoogleMapsProvider.jsx`.

### Running the Development Server

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

The page auto-updates as you edit the file.

## Usage

- **Home Page**: Browse available food listings.
- **Add Listing**: Create a new food listing with details and location.
- **Map View**: View listings on an interactive map.
- **Profile**: Manage your account and listings.
- **Login**: Authenticate to access personalized features.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## Team

- Yashkumar Pandya
- Dev Chattrala

Developed by Yashkumar Pandya
