# Airbnb Clone

Airbnb Clone is a web application that allows users to list, discover and book unique accommodations around the world. Users can also become hosts and earn money by renting out their spaces to travelers.

## Features

- User authentication and authorization with email and password or social login (Facebook, Google, etc.)
- User profile with photo, bio, reviews and verifications
- Host dashboard with listings management, calendar, reservations, earnings and statistics
- Listing creation with photos, amenities, location, price and availability
- Listing search with filters, map and pagination
- Listing details with description, photos, amenities, location, reviews and booking
- Booking system with instant or request booking, payment integration (Stripe), cancellation policy and confirmation email
- Review system with rating and feedback for hosts and guests
- Messaging system with real-time chat between hosts and guests
- Notifications system with email and SMS alerts for bookings, messages and reviews
- Wishlist system with saving and sharing favorite listings

## Technologies

- Front-end: React, Redux, Bootstrap, Sass, Leaflet
- Back-end: Node.js, Express, MongoDB, Mongoose, Socket.io, Passport
- Testing: Jest, Enzyme, Supertest
- Deployment: Heroku, Netlify

## Installation

To run this project locally, you need to have Node.js and MongoDB installed on your machine.

1. Clone this repository: `git clone https://github.com/your_username/airbnb-clone.git`
2. Install dependencies: `npm install`
3. Create a .env file in the root directory and add the following environment variables:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_PUBLIC_KEY=your_stripe_public_key
SENDGRID_API_KEY=your_sendgrid_api_key
TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
FACEBOOK_APP_ID=your_facebook_app_id
FACEBOOK_APP_SECRET=your_facebook_app_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```

4. Start the server: `npm run dev`
5. Start the client: `npm run client`
6. Open http://localhost:3000 in your browser

## Demo

You can view a live demo of this project here: https://airbnb-clone.netlify.app/

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
