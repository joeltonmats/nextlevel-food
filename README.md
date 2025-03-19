# NextLevel Food App

This repository contains the code and resources for the "NextLevel Food App". It is a simple application to understand the basics of the Next.js Framework.

## Tech Stack

- **Next.js**: A React framework for server-side rendering and static site generation
- **React**: A JavaScript library for building user interfaces
- **@aws-sdk/client-s3**: AWS SDK for JavaScript S3 Client for interacting with Amazon S3
- **better-sqlite3**: A simple, fast, and efficient SQLite3 library for Node.js
- **CSS Modules**: A CSS file in which all class and animation names are scoped locally by default

## Getting Started

To get started with this project, clone the repository and install the dependencies:

```bash
git clone git@github.com:joeltonmats/nextlevel-food.git
cd nextlevel-food
npm install
```

### Development Mode

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Production Mode

```bash
npm run build
npm start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## AWS S3 Configuration

For this project, it is necessary to create your own `.env.local` file and set the proper values for the keys. Example:

```bash
AWS_REGION = "sa-east-1";
AWS_ACCESS_KEY_ID = ABC;
AWS_SECRET_ACCESS_KEY = +DEF;
```

Additionally, create a new S3 bucket and replace the proper files. These steps are necessary to upload and show the images.
