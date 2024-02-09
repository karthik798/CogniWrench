# CogniWrench

> [!NOTE]  
> The project is deployed on Vercel's free plan, causing initial load delays as the node sleeps during inactivity. This is due to the free plan's dormancy feature.

> [!IMPORTANT]  
> The OpenAI and ReplicateAI are on a free plan, so at the time of your visit, it may not be working due to the expiration of the free trial.

## Features

- Tailwind design
- Tailwind animations and effects
- Full responsiveness
- Clerk Authentication (Email, Google, 9+ Social Logins)
- Client form validation and handling using react-hook-form
- Server error handling using react-toast
- Image Generation Tool (Open AI)
- Video Generation Tool (Replicate AI)
- Code Generation Tool (Open AI)
- Music Generation Tool (Replicate AI)
- Stripe Integration
- Free tier with API limiting

### Database (PlanetScale - MySQL)

To generate the Prisma Client based on your schema

```shell
npx prisma generate

```

To apply these migrations

```shell
npx prisma db push

```

---

### Start the app

```shell
npm run dev
```

---
