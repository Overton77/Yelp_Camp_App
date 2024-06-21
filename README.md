# YelpCamp

This is a Yelp-like application built with Node.js, EJS templates, Cloudinary, and MongoDB. The application has production-grade security and middleware.

## Features

- User authentication
- Create, edit, and delete campgrounds
- Upload images using Cloudinary
- Secure access to resources

## Prerequisites

- Node.js 18 or higher
- MongoDB Atlas account and cluster
- Cloudinary account

## API Keys and Environment Variables

Make sure you have the following API keys and environment variables set up:

- `CLOUDINARY_SECRET`
- `CLOUDINARY_API`
- `CLOUDINARY_URL`
- `CLOUDINARY_CLOUD_NAME`
- `MAPBOX_TOKEN`
- `DB_URL`

Example `.env` file:

```plaintext
CLOUDINARY_SECRET=your_cloudinary_secret
CLOUDINARY_API=your_cloudinary_api_key
CLOUDINARY_URL=your_cloudinary_url
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
MAPBOX_TOKEN=your_mapbox_token
DB_URL=your_mongodb_atlas_url
```

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Overton77/Yelp_Camp.git

   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root of your project and add the API keys and database URL.

4. **Seed the database**:

   ```bash
   npm run seed:db
   ```

5. **Run the application**:

   ```bash
   npm run start
   ```

## Usage

1. Open your web browser and go to:

   ```arduino
   http://localhost:3000
   ```

2. Sign up for an account and start using the application by creating, editing, and deleting campgrounds.
