## FastSell

Ecommerce store builder, allowing users to create an online store, manage products, customise their storefront and accept payments for orders.

![Dashboard](/screenshots/dashboard.png)

## Features

**[Admin]**

- User authentication
- Theme customiser
- Product editor

**[Storefront]**

- Customised online store
- Secure checkout (Stripe)

## Installation

`npm i` in root folder

## Running locally

- App : `npm run dev`
- Prisma Studio: `npx prisma studio` (in /packages/database)
- Seed data : `npm run seed`(in /packages/database)

## Set up .env files - (env-examples provided in relevant folders)

- /packages/database
- /apps/admin
- /apps/storefront

## Tech stack

- Typescript, React, NextJS, Turborepo, Tanstack Query
- Shadcn/ui, React Hot Toast, Zod, AuthJS, Cloudinary, Stripe
- Database: PostgreSQL, Prisma
- Testing/CI: Cypress, GitHub Actions

Note: This project is an extension of a project in which I was a collaborator on. The original project can be found [here](https://github.com/MitchCrystal/histreet).
