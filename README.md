**E-Commerce Store**

The goal of this project is to develop a modern E-Commerce Store web application with a dedicated admin interface. The platform will enable users to browse products, add items to their cart, place orders and make payments.

For store management, an admin dashboard will be provided with powerful features for:
-- Managing products and categories
-- Analyzing sales and performance metrics

This project aims to deliver a smooth and intuitive shopping experience for users, along with a robust and user-friendly toolset for administrators.

**How to install and run the application**

Cloning the repository
```shell
git clone https://github.com/voshiks/e-commerce-store.git
cd e-commerce-store
```

Installing dependencies
```shell
npm install
cd frontend
npm install
cd ..
```

Environment configuration
Create a .env file in the root directory:
```shell
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

Running the application

In the root directory, start the backend:
```shell
npm run build
npm run start
```

In a new terminal, start the frontend:
```shell
cd frontend
npm run dev
```

Open your browser and go to http://localhost:5173/
