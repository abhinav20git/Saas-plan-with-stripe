<h1 align="center">Saas Plan with Stripe</h1>
![Screenshot (192)](https://github.com/user-attachments/assets/96349d1f-5667-41bb-855e-10eff0f00ffb)
![Screenshot (193)](https://github.com/user-attachments/assets/e896fad6-962c-48f6-926e-ed0169a7fcc8)
![Screenshot (194)](https://github.com/user-attachments/assets/ecf09424-87d6-4b32-a490-a59d484e1c77)
![Screenshot (194)](https://github.com/user-attachments/assets/853c7ccb-48d0-45f3-a34a-b7e27b8f6a1d)
![Screenshot (196)](https://github.com/user-attachments/assets/ce9e51a0-f349-4647-a4db-03d9bb52ff42)

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

```shell
npm install
```

### Start the app

```shell
npm run dev
```

