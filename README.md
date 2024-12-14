<h1 align="center">Saas Plan with Stripe</h1>

![image](https://github.com/user-attachments/assets/5cf3028a-d438-4130-965d-b91133158cb6)

![image](https://github.com/user-attachments/assets/7ebb032a-61c4-48b9-8ef8-d755f0d0869f)

![image](https://github.com/user-attachments/assets/6f006946-918e-45d5-8a38-34f49de2c87e)

![image](https://github.com/user-attachments/assets/d9666d29-1b60-4ce0-b5bb-1bcad8c0c1d8)

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

