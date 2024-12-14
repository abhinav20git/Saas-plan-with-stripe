<h1 align="center">Saas Plan with Stripe</h1>
![Screenshot (192)](https://github.com/user-attachments/assets/7772412d-1fa0-40c5-b7b4-2b273e97440f)
![Screenshot (193)](https://github.com/user-attachments/assets/ca943157-72f7-483c-b2e5-2cb1b204669c)
![Screenshot (194)](https://github.com/user-attachments/assets/df276d31-4a90-466a-b47d-55865dee3eb3)
![Screenshot (195)](https://github.com/user-attachments/assets/b8f43df7-a29b-42d0-8302-08579efe7e59)

Some Features:

-   ⚛️ Tech Stack: Next.js 14, TypeScript, Prisma, MongoDB, Stripe
-   🔐 Authentication with Kinde Auth
-   💸 Monthly and Annually Subscriptions with Stripe
-   💵 Building a Stripe Billing Portal
-   🌗 Light/Dark Mode
-   🌐 Deployment

### Setup .env file

```js
DATABASE_URL=<get_your_mongo_db_url>

KINDE_CLIENT_ID=
KINDE_CLIENT_SECRET=
KINDE_ISSUER_URL=
KINDE_SITE_URL=
KINDE_POST_LOGOUT_REDIRECT_URL=
KINDE_POST_LOGIN_REDIRECT_URL=

STRIPE_MONTHLY_PLAN_LINK=<get_from_stripe>
STRIPE_YEARLY_PLAN_LINK=<get_from_stripe>

STRIPE_MONTHLY_PRICE_ID=<get_from_stripe>
STRIPE_YEARLY_PRICE_ID=<get_from_stripe>

STRIPE_SECRET_KEY=<get_from_stripe>
STRIPE_WEBHOOK_SECRET=<get_from_stripe>
NEXT_PUBLIC_STRIPE_CUSTOMER_PORTAL_URL=<get_from_stripe>
```

### Install dependencies

npm install
```

### Start the app

npm run dev
```

